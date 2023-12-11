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
| [F2158 - Wijzig partij](./artefacten/2158.md) | `partij` | `digitaal adres` & `partijidentificator` |
| [F6580 - Registreer contactgegevens bij partij](./artefacten/6580.md) | `partij` | `digitaal adres` |

## Klantcontact

| Code - Naam | Hoofdobject | Gerelateerde objecten | Opmerkingen |
| :--- | :--- | :--- | :--- |
| [F2173 - Registreer klantcontact](./artefacten/2173.md) | `klantcontact` | `betrokkenen`, `bijlage`, `informatieobject`, `interne taak`, `zaak` | Buiten familie |
| [F2130 - Koppel klantcontact aan interne taak](./artefacten/2130.md) | `klantcontact` - `interne taak` | | |
| [F1888 - Koppel klantcontact aan zaak](./artefacten/1888.md) | `klantcontact` - `zaak` | | |
| [F8618 - Vraag klantcontact op](./artefacten/8618.md) | `klantcontact` | `betrokkenen`, `bijlage`, `interne taak` | |
| [F2084 - Vraag overzicht van klantcontacten op](./artfacten/2084.md) | `klantcontact` | | |

## Interne taak

| Code - Naam | Hoofdobject | Gerelateerde objecten | Opmerkingen |
| :--- | :--- | :--- | :--- |
| [F2120 - Registreer interne taak](./artefacten/2120.md) | `interne taak` | | |
| [F5694 - Registreer contactgegevens bij interne taak](./artefacten/5694.md) | `interne taak` | `contactgegevens` | |
| [F5241 - Markeer interne taak als gedaan](./artefacten/5241.md)  | `interne taak` | `interne taak - zaak` | Buiten familie ivm validatie foreign key? |
| [F3839 - Vraag openstaande interne taken op](./artefacten/3839.md) | `interne taak` | `klantcontact` | |
