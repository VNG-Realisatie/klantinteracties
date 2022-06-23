---
layout: page-with-side-nav
title: Ontwerpkeuzes API-standaarden voor Klantinteracties
date: 20-06-2022
---

# Ontwerpkeuzes

## Klanten

### KLOK01 - Klantgegevens kunnen identificerende gegevens omvatten

#### Relevante uitgangspunten

[Klantgegevens vormen de basis van een klantbeeld](/uitgangspunten.md#KLUIT02---Klantgegevens-vormen-de-basis-van-een-klantbeeld)

#### Keuze

Klantgevevens kunnen naast de klantgegevens zelf, ook een set identificerende gegevens omvatten.

#### Toelichting

In de Klanten API kunnen zowel klantgegevens als identificerende gegevens worden vastgelegd:

1. __Klantgegevens.__ Door de klant zelf vestrekte verstrekte gegevens die door de gemeente worden gebruikt om met die klant contact te hebben op een door haar of hem gewenste manier. Het informatiesysteem dat de Klanten API aanbiedt geldt als authentieke bron voor deze gegevens.
2. __Identificerende gegevens.__ Eén of meerdere gegevens waarmee de gemeente kan vaststellen dat klant gemachtigd is om als of namens een persoon of organisatie te handelen. Het informatiesysteem dat de Klanten API aanbiedt geldt __niet__ als authentieke bron voor deze gegevens. In plaats daarvan gelden identificerende gegevens als een ‘haakje’ naar gegevens die in een andere registratie zijn vastgelegd. Deze andere registratie kan bij de gemeente bekend en direct voor haar toegankelijk zijn, zoals in het geval van de Basisregistratie Personen of het Nationaal Handelsregister, maar het kan ook gaan om een registratie waarvan de gemeente het karakter (nog) niet kent, zoals een buitenlands persoonsregister.

Als als onderdeel van de klantgegevens (voldoende) identificerende gegevens zijn vastgelegd, spreken we van een [Aangehaakte klant](/begrippen.md#aangehaakte-klant). In andere gevallen is sprake van een [Zelfstandige klant](/begrippen.md#zelfstandige-klant).

Bij de relaties tussen klanten en (identificerende gegevens over) natuurlijke of niet-natuurlijke personen gelden de volgende kardinaliteiten:

1.	Er is (per gemeente) minimaal geen, en maximaal één klant door middel van identificerende gegevens gerelateerd aan een natuurlijk persoon.
2.	Er is (per gemeente) minimaal geen klant gerelateerd aan een niet-natuurlijk persoon, en er is geen maximum in het aantal klanten dat aan een niet-natuurlijk persoon is gerelateerd.
3.	Een klant is gerelateerd aan minimaal geen, en maximaal één natuurlijk persoon óf niet-natuurlijk persoon. Een klant kan dus niet tegelijkertijd aan een natuurlijk persoon én aan een niet-natuurlijk persoon zijn gerelateerd.
