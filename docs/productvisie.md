---
layout: page-with-side-nav
title: Productvisie standaard voor Klantinteracties
date: 18-04-2023
---

# Standaard voor klantinteracties

## Domein en ontwikkelingen

Het woord klantinteractie valt uiteen in twee woorden: ‘klant’ en ‘interactie’. Samen beschrijven die heel precies met welk doel deze standaard ontwikkeld wordt: het vastleggen en beschikbaar stellen van informatie over inwoners en ondernemers die belang hebben bij de producten en diensten die gemeente levert – of korter, de ‘klanten’ van de gemeente, en de interacties die zij met de gemeente hebben. Dit met als doelen enerzijds het door de gemeente contact kunnen opnemen met klanten via opgegeven (voorkeurs)kanalen, en anderzijds inzicht bieden in (de inhoud van) eerdere interacties tussen klanten en de gemeente.

Een traject voor standaardiseren van bij interacties met klanten voorkomende gegevens komt niet uit de lucht vallen. Al bij het ontwikkelen van de API-standaarden voor Zaakgericht werken constateerden we dat het gestandaardiseerd vastleggen van gegevens over contact tussen klant en gemeente niet afhankelijk zou moeten zijn van het antwoord op de vraag of die klant ‘toevallig’ betrokken is bij een lopende zaak. Ook de inhoud van een mail die over levering van een product dat niet zaakgericht wordt verstrekt, of een weergave van gesprek dat niet het aanmaken van een zaak rechtvaardigt, kan voor een klant immers heel relevant zijn.

Maar met alleen het ‘uit zaken lichten’ van concepten die met klantinteracties te maken hebben, zijn we er niet. We willen ook aansluiten bij veranderde verwachtingen van inwoners en ondernemers over overheidsdienstverlening en de onder invloed daarvan bij gemeenten ontstane behoeften. Deze behoefteverandering is onder meer terug te zien in het ontstaan van nieuwe uitgangspunten voor dienstverlening, aansluitend bij een omnichannel-aanpak of gebruikersonderzoek over gemeentelijke inwonerportalen.

Een op het domein klantinteracties gerichte standaard moet goed aansluiten op de hedendaagse dienstverleningspraktijk. Dat proberen we op twee manieren te waarborgen:
1. We werken bij de ontwikkeling nauw samen met gemeenten en hun leveranciers, valideren bij hen onze inzichten, en sluiten aan bij de ontwikkeling van [MijnZaken-services](https://vng.nl/artikelen/mijnzaken-service-track-trace-voor-de-overheidsdienstlevering);
2. we beproeven en illustreren de beoogde werking van de standaard aan de hand van heel concrete en van gemeentelijke behoefte afgeleide casussen.

## Doelgroep en systemen

Inwoners en ondernemers vormen de uiteindelijke doelgroep van de standaard voor klantinteracties. Zij krijgen, doordat hun gemeente deze standaarden toepast, via meer kanalen toegang tot een completere set informatie over interacties met de gemeente. Een tweede belangrijke doelgroep zijn medewerkers van gemeentelijke klantcontactcentra, die dankzij de standaard voor klantinteracties toegang krijgen tot een completer klantbeeld, waardoor zij inwoners en ondernemers sneller, beter en vaker zonder ruggenspraak met vakafdelingen kunnen helpen. Medewerkers van deze afdelingen vormen een laatste groep belanghebbende gebruikers. Zij hoeven minder vragen zelf te beantwoorden omdat informatie over hun interacties met klanten (voor zover gewenst en toegestaan) eenvoudig door die klanten zelf of medewerkers van het klantcontactcentrum kan worden ingezien.

De standaard voor klantinteracties is een gegevensstandaard. Dit betekent dat doelgroepen IT-systemen gebruiken om gegevens over klanten en hun interacties (gestandaardiseerd) vast te leggen. Daartoe moet de standaard in deze systemen geïmplementeerd worden. In dit geval is sprake van een standaard met beperkte doelen, die voor een deel overlappen met de doelen waarvoor gemeenten bijvoorbeeld CRM- of KCC-ondersteunende systemen verwerven. Belangrijk te benadrukken is dat dat de standaard voor klantinteracties niet beoogt de functionaliteit die deze systemen doorgaans leveren volledig af te dekken. Onderdelen als kennisbanken, dashboards of andere rapportagetooling zijn voor de werking en waarde van deze systemen zeer belangrijk, maar vallen buiten de beoogde doelen – en dus het bereik – van de standaard voor Klantinteracties. Naast deze ‘frontoffice’-systemen ligt implementatie ook voor de hand in taakspecifieke en generieke afhandelsystemen van de gemeente.

## API-referentiearchitectuur (ARA)

In de tweede helft van 2022 zijn we gestart met de ontwikkeling van een API-referentiearchitectuur (ARA). Deze is gericht op het ontwikkelen van bruikbare, doelmatige en goed op elkaar aansluitende API-standaarden. Een aantal vraagstukken die we hierbij tegenkwamen, zijn tijdens vruchtbare werksessies met gemeenten en hun leveranciers diepgaand besproken.

De eerste contouren van ARA zijn reden om bij de ontwikkeling van standaarden voor Klantinteracties aan een drietal onderwerpen extra aandacht te besteden:
1. Weloverwogen kiezen van domeingrenzen, nadrukkelijke aandacht voor mogelijke (consistentie)problematiek bij het overschrijden daarvan en eventuele mitigerende maatregelen;
2. expliciet beschrijven van keuzes gemaakt ten aanzien van API-ontwerporiëntatie (gegevensgedreven of handelingsgedreven) en API-architectuur (REST ‘volgens het boekje’ versus een meer vrije interpretatie, of iets heel anders als GraphQL);
3. illustreren van implementatie van deze standaarden volgens verschillende patronen (gegevens in één centraal register, decentrale implementatie met façade-API, …).

Ontwerpbeslissingen die aan deze ontwerpen raken en waarvan de gevolgen verder reiken dan de standaard voor klantinteracties alleen, leggen we voor aan vertegenwoordigers van gemeenten en leveranciers in de ARA-klankbordgroep.