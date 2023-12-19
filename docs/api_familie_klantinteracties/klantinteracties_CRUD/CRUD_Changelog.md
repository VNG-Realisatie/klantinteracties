# API-specificaties van de CRUD variant

## Status: in ontwikkeling

Deze variant wordt verder uitgewerkt in samenwerking met enkele gemeenten. 
Uitgangspunten in deze variant is dat er een CRUD-API wordt uitgewerkt waar geen "convenience"- faciliteiten in opgenomen zijn.
Op deze manier krijgen we de technische basis-functies in beeld en kunnen we eventueel in vervolgstappen kiezen op welke wijze we "convenience"-voorzieningengaan toevoegen om performance of developer-experience te optimaliseren. 


De specificatie kan worden bekeken in [Swagger](./swagger-ui.md) of in [Redoc](./redoc.md).

## Changelog

***Versie 0.0.3-oas3.1***

  Mismatch met het informatiemodel rechtgetrokken: 
  - Bij het componenten `interneTaak` is de property *toegewezenOp* vervangen door de property *verwerktOp*. De property *verwerktOp*  is niet required waar *toegewezenOp* dat wel was.
  - De query-parameter *toegewezenOp* vervangen door de query-parameter *verwerktOp* bij de endpoint *../internetaken*.
    
  Foute verwijzing hersteld
  - In de resource partij verwees de propery voorkeurstaal naar "#/components/schemas/Taal". Dat is nu aangepast naar "#/components/schemas/Identificatiecode".
  
***Versie 0.0.2-oas3.1***

  - Bij de componenten `medewerker`, `organisatorischeEenheid` en `geautomatiseerdeActor` is een groeperende property toegevoegd (actortype).
    - Ratio: Door deze toevoeging is op eenvoudige wijze onderscheid te maken tussen de properties van het supertype (`Actor`) en de properties die bij de subtypes horen van de polymorfe resource `Actor`
  - Bij de componenten `persoon`, `contactpersoon` en `organisatie` is een groeperende property togevoegd (partijtype).
    - Ratio: Door deze toevoeging is op eenvoudige wijze onderscheid te maken tussen de properties van het supertype (`Partij`) en de properties die bij de subtypes horen van de polymorfe resource `Partij`
  - de property "objectidentificator" van de component `bijlage` is hernoemd naar "bijlageidentificator" (de bijbehorende query-parameter ook)
  - de property "objectidentificator" van de component `onderwerpobject` is hernoemd naar "onderwerpobjectidentificator" (de bijbehorende query-parameter ook)
  - de property "actoridentifcator" van de component `actor` is hernoemd naar "actoridentificator" (herstel typefout) (de bijbehorende query-parameter ook)
  - De omschrijving bij het datatype Boolean aangepast zodat duidelijk is dat waarmee true en false corresponderen.
  - Tikfout verbeterd in de operationid van de get ../betrokkenenbijklantcontact (getbetrokkenenbijklantcontact)
  - De datatypen van het type "string" zonder format zijn voorzien van een minLength: 1
    - Dit betekent dat als een property met dit datatype in de requestbody of de responsebody is opgenomen, dan moet deze ook daadwerkelijk een waarde met een minimale lengte van 1 hebben.
    - Dit betekent ook dat als een property "required" is dat er dan verplicht ook een waarde moet worden toegekend aan die property. (Voor alle properties van een ander type dan "string" wordt dit afgedwongen door de type-declaratie.)
  - Verwijzingen naar de code van een referentielijst zijn nu opgenomen als properties in plaats van een geneste code in de property die conform de referentielijst is genoemd.
    - Referentielijstcomponenten zijn verwijderd.
    - Naamgevingsconventie :  codeNaamReferentielijst
    - Voorbeeld oude situatie :
      ```
      Identificator:
      type: "object"
      description: "Gegevens die een object in een extern register uniek identificeren."
      required:
      - "objectId"
      - "objecttype"
      - "register"
      - "soortObjectId"
      properties:
        objectId:
          $ref: "#/components/schemas/Identificatiecode"
        objecttype:
          $ref: "#/components/schemas/SoortObject"
          description: "Type van het object."
        register:
          $ref: "#/components/schemas/ExternRegister"
          description: "Binnen het landschap van registers unieke omschrijving van\
              \ het register waarin het object is geregistreerd."
        soortObjectId:
          $ref: "#/components/schemas/SoortObjectId"
          description: "Naam van de eigenschap die het object identificeert."
        ```
    - Voorbeeld nieuwe situatie:
    - ```
      Identificator:
        type: "object"
        description: "Gegevens die een object in een extern register uniek identificeren."
        required:
        - "objectId"
        - "codeObjecttype"
        - "codeRegister"
        - "codeSoortObjectId"
        properties:
          objectId:
            $ref: "#/components/schemas/Identificatiecode"
            description: "Identificatie zpals die in een extern register is toegekend aan het betreffende object"
          codeObjecttype:
            $ref: "#/components/schemas/Identificatiecode"
            description: "Code van het type object (Referentielijst Objecttype)."
          codeRegister:
            $ref: "#/components/schemas/Identificatiecode"
            description: "Code van het register (Referentielijst ExternRegister)."
          codeSoortObjectId:
            $ref: "#/components/schemas/Identificatiecode"
            description: "Code van het soort objectId (Referentielijst soortObjectId)."
        ```
        
