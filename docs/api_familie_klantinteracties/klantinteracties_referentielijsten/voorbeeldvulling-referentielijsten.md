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

## Kanalen

Vraag uitgezet bij Paul Jansen 


| Code | Naam | indicatieActief |
| :----------- | :----------- | :----------- |

## Landen

Voor de referentielijst landen wordt verwezen naar de landelijke tabel 34 zoals die wordt gepubliceerd door de RVIG. 
De inhoud van deze tabel is beschikbaar op de site van het RVIG onder [Landelijke tabellen](https://publicaties.rvig.nl/Landelijke_tabellen/) 

Als `landcode` wordt de "Code" van de landelijke tabel 34 overgenomen
Als `landnaam` wordt de "Omschrijving" van de landelijke tabel 34 overgenomen 
Als `ingangsdatumLand` wordt de waarde van "Datum Ingang" van de landelijke tabel 34 overgenomen maar wel volgens de volgens de NEN-ISO 8601:2019-standaard genoteerd.
Als `einddatumLand` wordt de waarde van "Datum Einde" van de landelijke tabel 34 overgenomen maar wel volgens volgens de NEN-ISO 8601:2019-standaard

## Soorten digitaal adres

Voor de soorten digitaal adres is er geen landelijk standaard waarop we kunnen terugvallen. 

Voorstel voor vulling van de referentielijst "Soorten digitaal adres" 

| Code | Naam | 
| :----------- | :----------- |
| 1  | Telefoon | 
| 2  | E-mail |
| 3  | Whatsapp |
| 4  | Brief | 
| 5  | Web formulier | 
| 6  | Chat-applicatie | 
| 7  | Baliebezoek | 
| 8  | Bezoek op afspraak |
| 9  | Facebook | 
| 10 | Instagram | 


## Talen

Er is een internationale Standaard beschikbaar de ISO 639:2023 standaard. Deze standaard heeft recentelijk de volgende lijst standaarden vervangen : 
ISO 639-1:2002 - Codes for the representation of names of languages — Part 1: Alpha-2 code
ISO 639-5:2008 - Codes for the representation of names of languages — Part 5: Alpha-3 code for language families and groups
ISO 639-3:2007 - Codes for the representation of names of languages — Part 3: Alpha-3 code for comprehensive coverage of languages
ISO 639-2:1998 - Codes for the representation of names of languages — Part 2: Alpha-3 code
ISO 639-4:2010 - Codes for the representation of names of languages — Part 4: General principles of coding of the representation of names of languages and related entities, and application guidelines

Voor de talenlijst die hier benodigd is zou ISO 639-1:2002 waarschijnlijk afdoende zijn. 
De ISO 639:2023 standaard zou aangeschft moeten worden. Hoe gaan we hier mee om ? (https://standards.iteh.ai/catalog/standards/iso/ead9cc68-1fda-4225-add7-a24dabf3f742/iso-639-2023)

Voorstel is om vooralsnog de ISO 639-1:2002 lijst te hanteren. Die is [hier](https://nl.wikipedia.org/wiki/Lijst_van_ISO_639-codes) op te halen. 

Alleen die talen waar een waarde in de kolom "639-1" staat worden opgenomen. 

Als `code` wordt de twee-letterige code in de kolom "639-1"uit de Tabel op [Wikipedia, Lijst van ISO 639-codes]https://nl.wikipedia.org/wiki/Lijst_van_ISO_639-codes) overgenomen.


Als `naam` wordt de "Taalnaam" overgenomen.

IndicatieActief wordt standaard op "true" gezet.

## Externe registers







## Soorten object



## Soorten object-ID