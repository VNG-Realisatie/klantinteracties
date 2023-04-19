---
layout: page-with-side-nav
title: Veelgestelde vragen
date: 28-03-2022
---
  
# Veel gestelde vragen

## Algemeen

### Wie is de opdrachtgever?

Formeel opdrachtgever is .... 

### Wat is de opdracht?

?

### Wat gaat er concreet gemaakt worden?


### Wat betekent dit voor leveranciers?

Er komt een nieuwe API-standaard. Deze standaard dient door alle leveranciers die informatiesystemen aan gemeenten leveren waarin persoonsgegevens worden verwerkt moeten worden ingebouwd. De referentie implementaties bieden leveranciers een voorbeeld hoe deze standaard ingebouwd kan worden.

### Wat is de rol van VNG?

* Ontwikkelaar en beheerder van de API-standaard
* Communicatie naar, en afstemming met gemeenten en leveranciers
* Toetsen aan en aanpassen van de GEMMA architectuur
* Afstemming met Common Ground
* Kwaliteitsbewaking

### Er wordt van de standaard een referentie implementatie beschikbaar gesteld. Wat houdt dat in?

De referentie implementatie is bedoeld als voorbeeld om te laten zien dat de API specificatie implementeerbaar is. Eventuele gedragsregels die niet in de OAS 3 specificatie staan kunnen dan ook gedemonstreerd worden. De referentie implementatie is geen productie waardige software. Het is een proof of concept, geen robuust geprogrammeerde component die direct uitgerold kan worden. Maar om een API implementatie te testen werkt het prima. Bovendien kunnen we door middel van de referentie-implementatie testscripts schrijven (Postman) zodat leveranciers kunnen testen of hun implementaties voldoen aan de standaard.

### Is de referentie-implementatie bruikbaar in productie?

De referentieimplementatie is bedoeld voor het aantonen van de werking van de API-standaard en geschikt voor gebruik in een testomgeving. De referentieimplementatie is **niet** geschikt voor gebruik in een productie omgeving. De referentieimplementatie is hiervoor niet geschikt aangezien geen invulling is gegeven aan niet-functionele requirements zoals beschikbaarheid, performance, robuustheid etc. Ook is de ondersteuning vanuit VNG Realisatie tenaanzien van de referentieimplementatie niet ingericht op prodcutioneel gebruik.

### Wanneer wordt een Release Candidate vastgesteld als Release?

Wanneer in de release candidate geen gebreken gevonden zijn en deze daarmee voldoende stabiel is wordt deze release candidate een release. De periode voor deze stabiliteit is vastgesteld op 2 maanden, ingaande vanaf de dag waarop de release candidate uitgebracht is. Onder gebreken wordt verstaan fouten in de standaard. Eventuele verbeteringen of verduidelijkingen in documentatie waarbij geen aanpassingen in de API's noodzakelijk zijn worden niet beschouwd als reden om een nieuwe release candidate uit te brengen.

## Specifiek klantinteractie 

### Kan het beschreven informatiemodel ook toegepast worden, zonder gebruik te maken van de RESTful API?

?

### Is bij het ontwikkelen van de standaard ook gekeken naar initiatieven die al in Nederland of Europa zijn gestart.

Er is gekeken naar kaders en richtlijnen zoals deze in de zorg worden toegepast. In Europa zijn wel initiatieven gestart, maar leveren nog geen concreet product op.

### Is er een overzicht waar de wijzigingen ten opzichte van de vorige versie staan vermeld?

Op Github is opgenomen wanneer welke veranderingen zijn doorgevoerd. Zie hiervoor [Voortgang ontwikkeling API-standaard voor logging van verwerkingen](./achtergronddocumentatie/voortgang.md)
