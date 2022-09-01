---
layout: page-with-side-nav
title: Begrippen bij API-standaarden voor Klantinteracties
date: 21-06-2022
---

# Begrippen

Hieronder wordt een aantal begrippen dat binnen de de API-standaarden voor Klantinteracties of de documentatie daarbij wordt gebruikt gedefinieerd en nader toegelicht.

_Aan het consistent maken van deze defintities met die in de [GEMMA-architectuur](https://gemmaonline.nl) wordt gewerkt._

## Contactmoment

#### Definitie

Een aaneengesloten periode (bij gebruik van een synchroon communicatiemiddel zoals de telefoon) of een atomair moment (bij gebruik van een asynchroon communicatiemiddel zoals e-mail of een chatbericht) waarbij tussen de gemeente en een klant informatie wordt uitgewisseld.

#### Toelichting

Een contactmoment kan dus onderdeel zijn van een [interactie](#interactie) - als dat contactmoment bijvoorbeeld het leverproces van een product of dienst betreft - of de hele interactie omvatten - bijvoorbeeld wanneer de klant telefonisch een vraag stelt die meteen beantwoord kan worden.

## Interactie

#### Definitie

Periode, startend bij de eerste en eindigend na de laatste informatie-uitwisseling tussen de gemeente en een klant over een specifiek ondewerp.

#### Toelichting

Een interactie kan dus één of meerdere [contactmomenten](#contactmoment) omvatten.

## Klant

#### Definitie

Een persoon of organisatie waarmee de gemeente contact heeft gehad of (mogelijk) gaat hebben.

#### Toelichting

Deze kan de vraag oproepen waarom we een eigenlijk een klantenregister nodig hebben. Gegevens over personen of organisaties zijn toch al vastgelegd en opvraagbaar in basisregistraties? Dat klopt. Maar in de Basisregistratie Personen en het Nationaal Handelsregister vind je van een inwoner of ondernemer geen e-mailadres, telefoonnumer of bankrekeningnummer. Terwijl gemeenten deze gegevens vaak wel nodig hebben, bijvoorbeeld voor het beantwoorden van vragen en het verwerken van aanvragen of meldingen.

Gegevens die in een basisregistratie niet kunnen worden opgenomen, maar wel ‘horen’ bij een in een basisregistratie geregistreerd subject of object noemen we wel  ‘aangehaakte’ of ‘plus’gegevens. Klantgegevens zijn hiervan een voorbeeld. Ze zijn immers direct te relateren aan een (natuurlijk of niet-natuurlijk) persoon. De relatie tussen zo'n persoon in een basisregistratie en een ‘klant’ kan in het klantenregister dan ook concreet worden vastgelegd.

We onderscheiden twee ‘typen’ klanten, te weten:

#### **Aangehaakte klant**
Een klant waarvan:
  1. tijdens de interactie tussen de klant en de gemeente middels identificatie, authenticatie en controle van autorisaties vast is komen te staan dat de klant gemachtigd is om als of namens een persoon of organisatie te handelen, én
  2. als onderdeel van de klantgegevens identificerende gegevens van de persoon of organisatie als of namens wie de klant handelt zijn vastgelegd, zodanig dat de gemeente op basis van deze gegevens in de toekomst kan vaststellen dat zij contact heeft met de persoon of organisatie die de eerder vastgelede klantgegevens heeft verstrekt, óf met een persoon of organisatie die gemachtigd is deze in te zien of te wijzigen.

  De kenmerken van Aangehaakte klanten hebben een tweetal consequenties voor vastlegging, verstrekking en gebruik van bijbehorende gegevens:
  1. __Vastleggen of verstrekken mag alleen aan degenenen die daartoe gerechtigd zijn.__ Het vastleggen van identificerende gegevens mag alleen plaatsvinden nadat met voldoende zekerheid (dus middels een authenticatiemiddel van voldoende betrouwbaarheidsniveau) is vastgesteld dat degene die deze gegevens wil (laten) vastleggen gemachtigd is dit te (laten) doen. Voordat eerder geregistreerde gegevens aan de klant verstrekt worden, moet opnieuw met voldoende zekerheid zijn vastgesteld of degene aan wie deze verstrekt worden gemachtigd is de klantgegevens in te zien.
  2. __Aangehaakte klanten zijn geschikt voor hergebruik - en dus voor gebruik in een klantbeeld.__ Door de voorwaarden voor registratie weten we wie die de klantgegevens heeft laten vastleggen, en kunnen we vaststellen dat deze persoon daartoe gerechtigd was. Daarom kunnen deze gegevens worden beschouwd als betrouwbaar. Bovendien zijn deze klantgegevens meestal op basis van een gegarandeerd unieke sleutel (Burgerservicenummer, RSIN of KvK-nummer) op te vragen. Ze zijn hiermee geschikt voor hergebruik. _De voorwaarden waaronder dit hergebruik is toegestaan zijn ondewerp van onderzoek._

#### **Zelfstandige klant**
Een klant waarvan als onderdeel van de klantgegevens __geen__ identificerende gegevens van de persoon of organisatie zijn vastgelegd op basis waarvan de gemeente in de toekomst kan vaststellen dat zij contact heeft met de persoon of organisatie die de eerder vastgelede klantgegevens heeft verstrekt óf met een persoon of organisatie die gemachtigd is die in te zien of te wijzigen.
De kenmerken van Zelfstandige klanten hebben een tweetal consequenties voor vastlegging, verstrekking en gebruik van bijbehorende gegevens:
  1. __Vastleggen kan zonder voorwaarden, maar verstrekken mag alleen binnen de context van de interactie waarvoor klantgegevens zijn verstrekt.__ Aan het vastleggen van klantgegevens zonder identificerende gegevens zijn geen voorwaarden verbonden. Aan het verstrekken daarvan wel. Dat mag alleen gebeuren in het kader van de interactie waarvoor de klantgegevens zijn ingewonnen. Het ontbreken van (voldoende) identificerende gegevens betekent immers dat niet is na te gaan wie opdracht heeft gegeven tot het vastleggen van de klantgegevens - en dus ook niet of degene aan wie de klantgegevens later in een andere context worden verstrekt gemachtigd is die in te zien. Dit betekent dat het niet mogelijk is van een zelfstandige klant na registratie een aangehaakte klant te maken en ook dat voor een volgende interactie opnieuw klantgegevens moeten worden ingewonnen.
  2. __Aangehaakte klanten zijn ongeschikt voor hergebruik - en dus voor gebruik in een klantbeeld.__ De beperkingen die gelden voor vestrekking van klantgegevens zonder identitificerende betekenen dat deze niet geschikt zijn voor hergebruik. Dit betekent weer dat ze geen onderdeel kunnen zijn van een klantbeeld. Dat zou immers voor iedere zelfstandige klant beperkt zijn tot één interactie.

## Klantgegevens

#### Definitie

Alle gegevens die middels de Klanten API kunnen worden vastgelegd, gewijzigd en verwijderd.

## Identificerende gegevens

#### Definitie

Klantgegevens die middels de Klanten API kunnen worden vastgelegd met als expliciet doel het (later) te kunnen vaststellen wie deze gegevens heeft (laten) vastleggen. Nader bepaald gaat het om de attributen `subject`, `subjectType` en `subjectIdentificatie`.
