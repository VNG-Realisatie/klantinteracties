---
layout: page-with-side-nav
title: Functies voor Klantinteracties
date: 02-06-2022
---

# Functies

## Relatie

| Code - Naam | Hoofdobject | Gerelateerde objecten | Opmerkingen |
| :--- | :--- | :--- | :--- |
| [F7927 - Zoek relatie](./artefacten/7927.md) | `relatie` | | |
| [F0138 - Vraag relatie op](./artefacten/0138.md) | `relatie` | `contactgegevens` |
| [F7554 - Registreer relatie](./artefacten/7554.md) | `relatie` | `contactgegevens` |
| [F6580 - Registreer contactgegevens bij relatie](./artefacten/6580.md) | `relatie` | `contactgegevens` |

## Klantcontact

| Code - Naam | Hoofdobject | Gerelateerde objecten | Opmerkingen |
| :--- | :--- | :--- | :--- |
| [F2173 - Registreer klantcontact](./artefacten/2173.md) | `klantcontact` | `bijlage`, `informatieobject` | Buiten familie |
| [F2130 - Koppel klantcontact aan interne taak](./artefacten/2130.md) | `klantcontact` - `interne taak` | | |
| [F1888 - Koppel klantcontact aan zaak](./artefacten/1888.md) | `klantcontact` - `zaak` | | Buiten familie |
| [F8618 - Vraag klantcontact op](./artefacten/8618.md) | `klantcontact` | | |

## Interne taak

| Code - Naam | Hoofdobject | Gerelateerde objecten | Opmerkingen |
| :--- | :--- | :--- | :--- |
| [F2120 - Registreer interne taak](./artefacten/2120.md) | `interne taak` | `contactgegevens` | |
| [F5694 - Registreer contactgegevens bij interne taak](./artefacten/5694.md) | `interne taak` | `contactgegevens` | |
| [F5241 - Markeer interne taak als gedaan](./artefacten/5241.md)  | `interne taak` | `interne taak - zaak` | |
| [F3839 - Vraag openstaande interne taken op](./artefacten/3839.md) | `interne taak` | `klantcontact` | |
