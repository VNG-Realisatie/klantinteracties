---
layout: page-with-side-nav
title: Architectuur API-standaarden voor Klantinteracties
date: 02-06-2022
---

# Architectuur

De drie API-standaarden voor Klantinteracties kennen een verschillende oorsprong. Met de API-standaarden voor Klanten en Contactmomenten 'verzelfstandigen' we in feite objecten uit de het [Informatiemodel Zaken (RGBZ)](https://www.gemmaonline.nl/index.php/RGBZ_2.0_in_ontwikkeling) en (op termijn) de [Zaken API-standaard](https://vng-realisatie.github.io/gemma-zaken/standaard/zaken/index). Op deze manier kunnen eenvoudiger buiten de context van zaken worden gebruikt. Daarbij geldt de volge
- 'klant' vervangt op termijn [betrokkene](https://www.gemmaonline.nl/index.php/Rgbz_2.0/doc/objecttype/betrokkene) waar betrokkenen die betrokkene
- Een contactmoment [klantcontact](https://www.gemmaonline.nl/index.php/Rgbz_2.0/doc/objecttype/klantcontact)
De reden hiervoor is dat gegevens over klanten en beschrijvingen van interacties tussen deze klanten

![Bedrijfs- en dataobjecten bij levering producten en diensten](./assets/objecten-bij-levering-producten-en-diensten.svg){:height="100%" width="100%"}<br>
*Figuur 1 - Bedrijfs- en dataobjecten bij levering producten en diensten. Bedrijfsobjecten (midden) en dataobjecten die deze bedrijfsobjecten realiseren in de huidige (boven) en toekomstige situatie (beneden). Bedrijfsobjecten waarvoor in de huidige situatie geen gestandaardiseerde vastlegging mogelijk is, zijn lichtgeel gekleurd. In donkerblauw de elementen die onderdeel zijn van het klantinteracties-project. Nog te realiseren elementen zijn juist in lichtblauw en grijs weergegeven. Verdeling van dataobjecten over geïllustreerde registers en API-interfaces onder voorbehoud van splitsing of samenvoeging. [Bekijk deze afbeelding op volledig formaat](./assets/objecten-bij-levering-producten-en-diensten.png).*
