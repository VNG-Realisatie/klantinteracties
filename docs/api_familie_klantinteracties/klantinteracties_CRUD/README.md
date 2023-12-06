# API-specificaties van de CRUD variant

## Status: in ontwikkeling

Deze variant wordt verder uitgewerkt in samenwerking met enkele gemeenten. 
Uitgangspunten in deze variant is dat er een CRUD-API wordt uitgewerkt waar geen "convenience"- faciliteiten in opgenomen zijn.
Op deze manier krijgen we de technische basis-functies in beeld en kunnen we eventueel in vervolgstappen kiezen op welke wijze we "convenience"-voorzieningengaan toevoegen om performance of developer-experience te optimaliseren. 

## Changelog

***Versie 0.0.2-oas3.1***

  - Bij de componenten `medewerker`, `organisatorischeEenheid` en `geautomatiseerdeActor` is een groeperende property toegevoegd (actortype).
    - Ratio: Door deze toevoeging is op eenvoudige wijze onderscheid te maken tussen de properties van het supertype (`Actor`) en de properties die bij de subtypes horen van de polymorfe resource `Actor`
  - Bij de componenten `persoon`, `contactpersoon` en `organisatie` is een groeperende property togevoegd (partijtype).
    - Ratio: Door deze toevoeging is op eenvoudige wijze onderscheid te maken tussen de properties van het supertype (`Partij`) en de properties die bij de subtypes horen van de polymorfe resource `Partij`
  - de property "objectidentificator" van de component `bijlage` is hernoemd naar "bijlageidentificator" (de bijbehorende query-parameter ook)
  - de property "objectidentificator" van de component `onderwerpobject` is hernoemd naar "onderwerpobjectidentificator" (de bijbehorende query-parameter ook)
  - de property "actoridentifcator" van de component `actor` is hernoemd naar "actoridentificator" (herstel tyepfout) (de bijbehorende query-parameter ook)
  - De omschrijving bij het datatype Boolean aangepast zodat duidelijk is dat waarmee true en false corresponderen.
  - Tikfout verbeterd in de operationid van de get ../betrokkenenbijklantcontact (getbetrokkenenbijklantcontact)
  - 

