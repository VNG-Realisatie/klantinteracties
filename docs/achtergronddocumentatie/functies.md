---
layout: page-with-side-nav
title: Functies voor Klantinteracties
date: 02-06-2022
---

# Functies

## Partijen

| Code - Naam | Hoofdobject | Gerelateerde objecten | Opmerkingen |
| :--- | :--- | :--- | :--- |
| [F7927 - Zoek partij](./artefacten/7927.md) | `partij` | `digitaal adres`, `partij-identificator` | |
| [F0138 - Vraag partij op](./artefacten/0138.md) | `partij` | `digitaal adres`, `Partij-identificator` |
| [F7554 - Registreer partij](./artefacten/7554.md) | `partij` | `partij-identificator` |
| [F2158 - Wijzig partij](./artefacten/2158.md) | `partij` |  |

## Klantcontact

| Code - Naam | Hoofdobject | Gerelateerde objecten | Opmerkingen |
| :--- | :--- | :--- | :--- |
| [F2173 - Registreer klantcontact](./artefacten/2173.md) | `klantcontact` | `betrokkenebijklantcontact`, `actorklantcontact` | |
| [F3896 - Zoek klantcontact](./artefacten/3896.md) | `klantcontact` | | |
| [F8618 - Vraag klantcontact op](./artefacten/8618.md) | `klantcontact` | `betrokkenen`, `bijlage`, `interne taak` | |

## Interne taak

| Code - Naam | Hoofdobject | Gerelateerde objecten | Opmerkingen |
| :--- | :--- | :--- | :--- |
| [F2120 - Registreer interne taak](./artefacten/2120.md) | `interne taak` | | |
| [F5694 - Registreer contactgegevens bij interne taak](./artefacten/5694.md) | `interne taak` | `contactgegevens` | |
| [F5241 - Markeer interne taak als gedaan](./artefacten/5241.md)  | `interne taak` | `interne taak - zaak` | Buiten familie ivm validatie foreign key? |
| [F3839 - Vraag openstaande interne taken op](./artefacten/3839.md) | `interne taak` | `klantcontact` | |
| [F2771 - Vraag interne taak op](./artefacten/2771.md) | `interne taak` | | |

## Actor 

| Code - Naam | Hoofdobject | Gerelateerde objecten | Opmerkingen |
| :--- | :--- | :--- | :--- |
| [F5592 - Registreer actor](./artefacten/5592.md) | `actor` | | |
| [F5582 - Zoek actor](./artefacten/5582.md) | `actor` | | |
| [F6542 - Koppel actor aan klantcontact](./artefacten/5582.md) | `actorKlantcontact` | |
| [F5002 - Vraag actor op](./artefacten/5002.md) | `actor` | | |


## Betrokkene bij klantcontact

| Code - Naam | Hoofdobject | Gerelateerde objecten | Opmerkingen |
| :--- | :--- | :--- | :--- |
| [F2599 - Registreer betrokkene bij klantcontact](./artefacten/2599.md) | `betrokkeneBijKlantcontact` | | |
| [F4936 - Zoek betrokkene bij klantcontact](./artefacten/4936.md) | `betrokkeneBijKlantcontact` | | |
| [F5859 - Vraag betrokkene bij klantcontact op](./artefacten/5859.md) | `betrokkeneBijKlantcontact` | | |
| [F5859 - Wijzig betrokkene bij klantcontact](./artefacten/3246.md) | `betrokkeneBijKlantcontact` | | |

## Digitaal adres

| Code - Naam | Hoofdobject | Gerelateerde objecten | Opmerkingen |
| :--- | :--- | :--- | :--- |
| [F1995 - Registreer Digitaal adres](./artefacten/1995.md) | `Digitaal adres` | | | 
| [F6634 - Zoek Digitaal adres](./artefacten/6634.md) | `Digitaal adres` | | |

## PartijIdentificator

| Code - Naam | Hoofdobject | Gerelateerde objecten | Opmerkingen |
| :--- | :--- | :--- | :--- |
| [F5817 - Zoek Partijidentificator](./artefacten/5817.md) | `Partijidentificator` | | |

## Onderwerpobject

| Code - Naam | Hoofdobject | Gerelateerde objecten | Opmerkingen |
| :--- | :--- | :--- | :--- |
| [F9322 - Registreer onderwerpobject](./artefacten/9322.md) | `Onderwerpobject` | | | 

## Bijlage

| Code - Naam | Hoofdobject | Gerelateerde objecten | Opmerkingen |
| :--- | :--- | :--- | :--- |
| [F1975 - Registreer bijlage](./artefacten/1975.md) | `Bijlage` | | | 