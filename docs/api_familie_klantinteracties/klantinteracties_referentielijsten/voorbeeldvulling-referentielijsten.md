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

Vraag uitgezet bij Paul Jansen / Vincent van Beek


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
| ---- | ---- | ---- | 
| ara  | Arabisch | true | 
| aze  | Azerbeidzjaans | true | 
| bel  | Belarussisch | true | 
| ber  | Berber | true | 
| bos  | Bosnisch | true | 
| bul  | Bulgaars | true | 
| ces  | Tsjechisch | true | 
| cnr  | Montenegrijns | true | 
| dan  | Deens | true | 
| deu  | Duits | true | 
| ell  | Grieks | true | 
| eng  | Engels | true | 
| est  | Estisch | true | 
| fas  | Perzisch | true | 
| fin  | Fins | true | 
| fra  | Frans | true | 
| fry  | Fries | true | 
| gle  | Iers | true | 
| hin  | Hindi | true | 
| hrv  | Kroatisch | true | 
| hun  | Hongaars | true | 
| hye  | Armeens | true | 
| isl  | IJslands | true | 
| ita  | Italiaans | true | 
| jav  | Javaans | true | 
| lav  | Lets | true | 
| lim  | Limburgs | true | 
| lit  | Litouwen | true | 
| kat  | Georgisch | true | 
| kur  | Koerdisch | true | 
| mlt  | Maltees | true | 
| mkd  | Macedonisch | true | 
| nds  | Nedersaksisch | true | 
| nld  | Nederlands | true | 
| nor  | Noors | true | 
| pap  | Papiaments | true | 
| pol  | Pools | true | 
| por  | Portugees | true | 
| rom  | Romani | true | 
| ron  | Roemeens | true | 
| rus  | Russisch | true | 
| sgn  | Gebarentaal | true | 
| slk  | Slowaaks | true | 
| slv  | Sloveens | true | 
| som  | Somalisch | true | 
| spa  | Spaans | true | 
| srn  | Sranan | true | 
| srp  | Servisch | true | 
| sqi  | Albanees | true | 
| swe  | Zweeds | true | 
| tur  | Turks | true | 
| ukr  | Oekraïens | true | 
| yue  | Kantonees  | true | 
| yid  | Jiddisch | true | 
| zho  | Mandarijn | true | 

## Extern register

De basisvulling ven de referentielijst "Externe registers" omvat alleen de landelijke voorzieningen voor basisregistraties en een voorbeeld van enkele veelvoorkomende gemeentelijke registers. Registers hebben bij verschillende gemeenten verschillende namen. Daarbij komen per gemeente ook meerdere registers van hetzelfde type voor zoals bij Zakenregisters. 

Met de voorbeelvulling willen we ook voorbeelden geven van de samenhang tussen de referentielijsten "Extern register" , "Soort Object" en "Soort ObjectId".

| Code | Naam | Locatie | 
| :----------- | :----------- | :----------- |
| 1  | Basisregistratie Personen |  | 
| 2  | Basisregistratie Kadaster |  |
| 3  | Basisregistratie Adressen en Gebouwen |  |
| 4  | Basisregistratie Waardering Onroerende Zaken |  | 
| 5  | Handelsregister |  | 
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
| 5  | Onroerende zaak | 2 | 
| 6  | Persoon | 2 |
| 7  | Nummeraanduiding | 3 |
| 8  | Pand | 3 |
| 9  | WOZObject | 4 |
| 10 | Bezwaar | 4 | 
| 11 | Biljet | 4 | 
| 12 | Zaak | 6 | 

## Soort object-ID

| Code | Naam | SoortObjectId |
| :----------- | :----------- | :----------- |
| 1  | Burgerservicenummer | 1 |  
| 2  | Rechtspersonen en Samenwerkingsverbanden Identificatienummer | 2 |
| 3  | Vestigingsnummer | 4 | 
| 4  | Identificatie | 3 | 
| 6  | Identificatie | 5 |
| 7  | Identificatie | 6 |
| 8  | Identificatie | 8 |
| 9  | WozObjectnummer | 9 |
| 10 | Identificatie | 10 | 
| 11 | Identificatie | 11| 
| 12 | Zaakidentificatie | 12 | 

