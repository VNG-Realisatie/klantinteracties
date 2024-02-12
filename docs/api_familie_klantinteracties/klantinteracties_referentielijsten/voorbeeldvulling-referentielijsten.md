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

Er is een internationale Standaard beschikbaar de ISO 639:2023 standaard. Deze standaard heeft recentelijk de volgende lijst standaarden vervangen : 
ISO 639-1:2002 - Codes for the representation of names of languages — Part 1: Alpha-2 code
ISO 639-5:2008 - Codes for the representation of names of languages — Part 5: Alpha-3 code for language families and groups
ISO 639-3:2007 - Codes for the representation of names of languages — Part 3: Alpha-3 code for comprehensive coverage of languages
ISO 639-2:1998 - Codes for the representation of names of languages — Part 2: Alpha-3 code
ISO 639-4:2010 - Codes for the representation of names of languages — Part 4: General principles of coding of the representation of names of languages and related entities, and application guidelines

Voor de talenlijst die hier benodigd is zou ISO 639-1:2002 waarschijnlijk afdoende zijn. 
De ISO 639:2023 standaard zou aangeschaft moeten worden. Hoe gaan we hier mee om ? (https://standards.iteh.ai/catalog/standards/iso/ead9cc68-1fda-4225-add7-a24dabf3f742/iso-639-2023)

Voorstel is om vooralsnog de ISO 639-1:2002 lijst te hanteren. Die is [hier](https://nl.wikipedia.org/wiki/Lijst_van_ISO_639-codes) op te halen. 

Alleen die talen waar een waarde in de kolom "639-1" staat worden opgenomen. 

Als `code` wordt de twee-letterige code in de kolom "639-1"uit de Tabel op [Wikipedia, Lijst van ISO 639-codes]https://nl.wikipedia.org/wiki/Lijst_van_ISO_639-codes) overgenomen.

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
| 3  | Naampersoon | 5 |
| 4  | Vestiging | 5 | 
| 5  | Kadastraal Onroerende Zaak | 2 | 
| 6  | Persoon | 2 |
| 7  | Nummeraanduiding | 3 |
| 8  | Pand | 3 |
| 9  | WOZ-object | 4 |
| 10 | Bezwaar | 4 | 
| 11 | Biljet | 4 | 
| 12 | Zaak | 6 | 
| 13 | Betrokkene | 6 | 
| 14 | Informatieobject | 7 |

## Soort object-ID

| Code | Naam | ExternRegisterId |
| :----------- | :----------- | :----------- |
| 1  | BurgerServiceNummer (BSN) | 1 |  
| 2  | Rechtspersonen en Samenwerkingsverbanden Identificatienummer (RSIN) | 2 |
| 3  | Naampersoon | 5 |
| 4  | Vestiging | 5 | 
| 5  | Kadastraal Onroerende Zaak | 2 | 
| 6  | Persoon | 2 |
| 7  | Nummeraanduiding | 3 |
| 8  | Pand | 3 |
| 9  | WOZ-object | 4 |
| 10 | Bezwaar | 4 | 
| 11 | Biljet | 4 | 
| 12 | Zaak | 6 | 
| 13 | Betrokkene | 6 | 
| 14 | Informatieobject | 7 |
