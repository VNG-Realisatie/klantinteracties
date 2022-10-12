---
layout: page-with-side-nav
title: API-standaarden voor Klantinteracties
date: 09-06-2022
---

# <span style="color:#C21807; font-style:italic">Ontwikkeling API-standaarden voor Klantinteracties gepauzeerd</span>

<span style="color:#7C0A02">In 2017 zijn gemeenten, VNG en leveranciers onder de naam ‘Common Ground’ een nieuwe informatiekundige weg ingeslagen. Eén gevolg was het ontwikkelen van nieuwe API-standaarden die aansluiten bij het vijflagenmodel en de REST-architectuurstijl volgen.</span>

<span style="color:#7C0A02">Naar aanleiding van de eerste ervaringen met implementatie van deze standaarden is een aantal vraagstukken ontstaan dat niet gaat over individuele standaarden, maar raakt aan alle API-standaarden voor gemeenten.</span>

<span style="color:#7C0A02">Het gaat hierbij om concrete opgaven als het bepalen van de aanpassingen van API-standaarden om aan te kunnen sluiten bij eerder dit jaar ontwikkelde oplossingen voor toegangsbeheer. Maar ook om het beantwoorden van meer fundamentele vragen bij thema’s als performance (bij het bevragen van gegevens uit meerdere bronnen ineens) en consistentie (tussen gegevens in meerdere bronnen).</span>

<span style="color:#7C0A02">Het antwoord op deze vragen vormt een gezamenlijke basis of ‘fundament’ waarop we de komende jaren bij de ontwikkeling van API-standaarden verder kunnen bouwen.</span>

<span style="color:#7C0A02">Omdat zo’n fundament een voorwaarde is voor doelmatige, op elkaar aansluitende API-standaarden van goede kwaliteit, én omdat op het gebied van API-ontwikkeling de komende tijd veel van gemeenten en de VNG wordt verwacht, gaan we met méér mensen méér tijd steken in de ontwikkeling daarvan. Dit betekent dat de ontwikkeling van de API-standaarden voor Klantinteracties (Klanten, Contactmomenten en Verzoeken) vanaf september 2022 wordt gepauzeerd. We verwachten de ontwikkeling van deze API-standaarden in 2023 weer op te nemen, en de tweede helft van dat jaar productieversies van deze standaarden te kunnen uitbrengen.</span>

<span style="color:#7C0A02">We begrijpen dat veel van jullie wachten op productieversies van de API-standaarden voor Klantinteracties. Tegelijkertijd willen we ook, voor zover als mogelijk, de toepasbaarheid daarvan kunnen garanderen. Het werk dat we de komende maanden aan het ‘fundament’ verrichten gaat hieraan een belangrijke bijdrage leveren.</span>

<span style="color:#7C0A02">Vragen hierover? mail naar mailto:standaarden.ondersteuning@vng.nl.</span>

# API-standaarden voor Klantinteracties

In 2021 zijn de [API-standaarden voor Zaakgericht werken](https://vng-realisatie.github.io/gemma-zaken/) vastgesteld. Als 'spin-off' van dat ontwikkeltraject zijn ook de eerste stappen gezet in de ontwikkeling van drie daaraan gerelateerde API-standaarden waarmee gemeenten gegevens over interacties met inwoners en ondernemers op gestandaardiseerde wijze kunnen registreren, bewerken en verwijderen. De drie (concept)standaarden samen noemen we de 'API-standaarden voor Klantinteracties'. In 2022 werken we aan productiewaardige versies van deze standaarden.

## Om welke standaarden gaat het?
De set API-standaarden voor Klantinteracties bestaat uit drie API-standaarden voor het vastleggen van informatie over interacties tussen de gemeente en inwoners en ondernemers. Gedurende het ontwikkelproces wordt de documentatie per standaard geactulaliseerd en overgeheveld van de [GitHub-omgeving van de API-standaarden voor Zaakgericht werken](https://vng-realisatie.github.io/gemma-zaken/standaard/contactmomenten/index) naar deze omgeving. Voor de standaarden waarvoor dit nog niet is gebeurd, wordt hieronder verwezen naar de (concept)documentatie in de Zaakgericht werken-omgeving.
- [Klanten API-standaard](./api-standaarden/klanten/specificaties.md)
- [Contactmomenten API-standaard](https://vng-realisatie.github.io/gemma-zaken/standaard/contactmomenten/index)
- [Productaanvragen API-standaard](https://vng-realisatie.github.io/gemma-zaken/standaard/contactmomenten/index) - achter de link nog 'Verzoeken API' genoemd
- [Informatiemodellen](./informatiemodellen.md)

### Status van de API-standaarden

Aan de API-standaarden voor Klantinteracties wordt op dit moment gewerkt. 1.0-versies van de Klanten, Contactmomenten en Productaanvragen API's worden later in 2022 verwacht.

## Werkingsgebied

Een aantal gegevens die met de API-standaarden voor Klantinteracties beschikbaar worden gesteld waren eerder onderdeel van de zaken API (zie ook [Architectuur](./architectuur.md). Dit betekent dat (op termijn) systemen die betrokken zijn bij het zaakgericht werken de API-standaarden voor Klantinteracties moeten gaan gebruiken. De API-standaarden voor Klantinteracties zijn verder relevant voor (andere) informatiesystemen die een rol spelen bij [klant en keteninteractie](https://www.gemmaonline.nl/index.php/GEMMA2/0.9/id-1022e062-af16-4ca9-8ee8-434ebd880977). Om gebruik mogelijk te maken zijn aanbieders (of providers) voor de API's voor Klantinteracties nodig. Deze aanbieders moeten de op deze pagina's beschreven API-standaard(en) volledig implementeren. Onderdeel van het ontwikkeltraject is te bepalen en in de GEMMA-architectuur aan te duiden welke [GEMMA-referentiecomponenten](https://www.gemmaonline.nl/index.php/Overzicht_alle_referentiecomponenten) voor de Klantinteracties API's als aanbieder kunnen of moeten optreden.

Hoewel deze API-standaarden ontwikkeld zijn voor gebruik door gemeenten en hun softwareleveranciers zijn die ook voor overheidsorganisaties buiten het gemeentelijk domein toepasbaar.

## Worden deze API-standaarden verplicht?

De API-standaarden voor Klantinteracties hangen nauw samen met de API-standaarden voor Zaakgericht werken. Omdat voor de toepassing van die standaarden een ['pas toe of leg uit'-principe](https://vng.nl/brieven/standaardverklaring-per-142021-api-standaarden-voor-zaakgericht-werken) geldt, is het het streven om ook de API-standaarden voor Klantinteracties op termijn meer verplichtend vast te stellen. Hiertoe zal na oplevering van de eerste productie-versie van de API-standaard een traject worden opgestart richting het College van Dienstverleningszaken van de VNG.

### Bijdragen aan het project

Gemeenten en leveranciers worden aangemoedigd om bij te dragen aan het project. Onderstaande links geven informatie over hoe u uw bijdrage kan leveren.
- Hoe u kunt [bijdragen](https://github.com/VNG-Realisatie/Tutorial/blob/master/CONTRIBUTING.md)
- [Daadwerkelijk bijdragen](https://vng-realisatie.github.io/API-Kennisbank/docs/hoe-kun-je-bijdragen)
- [Omgangsvormen](https://github.com/VNG-Realisatie/Tutorial/blob/master/CODE_OF_CONDUCT.md)
- Mis je functionaliteit die voor jou belangrijk is? Heb je een issue (fout of bug) gezien in een van onze API’s? Of heb je een wens of suggestie? [Bijdragen aan VNGR API standaarden kan in verschillende vormen.](https://vng-realisatie.github.io/API-Kennisbank/docs/hoe-kun-je-bijdragen)

## Beheer en ondersteuning

Contact: mailto:standaarden.ondersteuning@vng.nl

## Licentie

Copyright &copy; VNG Realisatie 2022
