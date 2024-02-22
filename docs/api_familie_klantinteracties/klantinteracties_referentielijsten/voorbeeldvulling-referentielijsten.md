---
layout: page-with-side-nav
title: Voorbeeldvulling voor referentilijsten bij klantinteracties
date: 29-01-2024
---

# Inleiding

In principe staat het iedere gemeente vrij om de referentielijsten op te stellen naar eigen inzicht. 
In dit document wordt voor sommige referentielijsten een basisvulling voorgesteld die aan te vullen is mert gemeentespecifieke waarden. 
Daarnaast wordt er voor sommige referentielijsten een voorstel gedaan voor de hele inhoud van de referentielijst. 

We adviseren om deze vulling van referentielijsten over te nemen aangezien dit voor de leveranciers een basis kan vormen. 
Tevens is het een goede zaak als gemeenten onderling voor dezelfde referentielijst waarden ook dezelfde codes gebruikten.

# Referentielijsten

Per referentielijst wordt aangegeven of, en welke (basis-)vulling er is gedefinieerd en op welke wijze er gemeente-specifieke waarden kunnen worden toegevoegd. 

## Kanaal

Vraag uitgezet bij Paul Jansen 


| Code | Naam | indicatieActief |
| :----------- | :----------- | :----------- |

## Land

Voor de referentielijst landen wordt verwezen naar de landelijke tabel 34 zoals die wordt gepubliceerd door de RVIG. 
De inhoud van deze tabel is beschikbaar op de site van het RVIG onder [Landelijke tabellen](https://publicaties.rvig.nl/Landelijke_tabellen/) 

Als `landcode` wordt de "Code" van de landelijke tabel 34 overgenomen
Als `landnaam` wordt de "Omschrijving" van de landelijke tabel 34 overgenomen 
Als `ingangsdatumLand` wordt de waarde van "Datum Ingang" van de landelijke tabel 34 overgenomen maar wel volgens de volgens de NEN-ISO 8601:2019-standaard genoteerd.
Als `einddatumLand` wordt de waarde van "Datum Einde" van de landelijke tabel 34 overgenomen maar wel volgens volgens de NEN-ISO 8601:2019-standaard

## Soort digitaal adres

Voor de soorten digitaal adres is er geen landelijk standaard waarop we kunnen terugvallen. 

Voorstel voor vulling van de referentielijst "Soorten digitaal adres" 

| Code | Naam | 
| :----------- | :----------- |
| 1  | Telefoon | 
| 2  | E-mail |
| 3  | Whatsapp |
| 4  | Facebook | 
| 5  | Instagram | 
| 6  | SMS | 


## Taal

Voor de voorbeeldvulling van de talenlijst wordt een selectie de ISO 639-2 lijst gebruikt zoals die gepubliceerd is door de [Library of Congress](https://www.loc.gov/standards/iso639-2/php/code_list.php). Van deze lijst wordt de drie-letterige code toegepast als code in de referentielijst. Waar er voor een taal 2 codes zijn gedefinieerd wordt de (T)-variant gebruikt in de referentielijst. 

Voor het samenstellen van de lijst worden de volgende criteria gehanteerd :
- De door de overheid [erkende talen van Nederland](https://www.rijksoverheid.nl/onderwerpen/erkende-talen/vraag-en-antwoord/erkende-talen-nederland).
- [De officiële talen van de Europese Unie](https://european-union.europa.eu/principles-countries-history/languages_nl)
- De meest-gesproken talen in Nederland.

Dat leidt tot de volgende voorbeeldvulling van de referentielijst

| **Code** | **Naam** | **IndicatieActief** | 


Als `naam` wordt de "Taalnaam" overgenomen.

IndicatieActief wordt standaard op "true" gezet.

## Extern register

De basisvulling ven de referentielijst "Externe registers" omvat alleen de landelijke voorzieningen voor basisregistraties en een voorbeeld van enkele veelvoorkomende gemeentelijke registers. Registers hebben bij verschillende gemeenten verschillende namen. Daarbij komen per gemeente ook meerdere registers van hetzelfde type voor zoals bij Zakenregisters. 

Met de voorbeelvulling willen we ook voorbeelden geven van de samenhang tussen de referentielijsten "Extern register" , "Soort Object" en "Soort ObjectId".

| Code | Naam | Locatie | 
| :----------- | :----------- | :----------- |
| 1  | BasisRegistratie Personen |  | 
| 2  | BasisRegistratie Kadaster |  |
| 3  | Basisregistratie Adressen en Gebouwen |  |
| 4  | Basisregistratie Waardering Onroerende Zaken |  | 
| 5  | HandelsRegister |  | 
| 6  | Zakenregister |  |
| 7  | Documentenregister |  |
| 8  | Overige Objecten Registratie |  |

## Soort object

Met de referentielijst Soorten object wordt in kaart gebracht naar welk soort object binnen een Extern Register verwezen wordt. Hier ligt dus ook een relatie naar de referentietabel Extern Register, want een object "leeft" in een specifiek register. Er kan dus alleen verwezen worden naar objecten die daadwerkelijk in een Ectern Register voorkomen. Deze voorbeeldvulling is zeker niet compleet en kan naar behoefte aangevuld worden. 

| Code | Naam | ExternRegisterId |
| :----------- | :----------- | :----------- |
| 1  | Ingeschreven Natuurlijk Persoon | 1 |  | 
| 2  | Ingeschreven Niet-Natuurlijk Persoon | 5 |
| 3  | Informatieobject | 7 |
| 4  | Vestiging | 5 | 
| 5  | Kadastraal Onroerende Zaak | 2 | 
| 6  | Persoon | 2 |
| 7  | Nummeraanduiding | 3 |
| 8  | Pand | 3 |
| 9  | WOZ-object | 4 |
| 10 | Bezwaar | 4 | 
| 11 | Biljet | 4 | 
| 12 | Zaak | 6 | 



## Soort object-ID

| Code | Naam | SoortObjectId |
| :----------- | :----------- | :----------- |
| 1  | BurgerServiceNummer (BSN) | 1 |  
| 2  | Rechtspersonen en Samenwerkingsverbanden Identificatienummer (RSIN) | 2 |
| 3  | Vestigingsnummer | 4 | 
| 4  | Identificatie | 3 | 
| 6  | Identificatie | 5 |
| 7  | Identificatie | 6 |
| 8  | Identificatie | 8 |
| 9  | wozObjectnummer | 9 |
| 10 | identificatie | 10 | 
| 11 | identificatie | 11| 
| 12 | Zaakidentificatie | 12 | 

