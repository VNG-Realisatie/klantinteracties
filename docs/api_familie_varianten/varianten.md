---
layout: page-with-side-nav
title: API ontwerpvarianten
date: 14-04-2023
---

# Inleiding

In de eerste iteratie van het maken van de API-standaarden voor Klantinteracties zijn aan aantal ontwerpvarianten op hoofdlijnen uitgewerkt ter illustratie. 
Deze ontwerpvarianten zijn inmiddels (inhoudelijk) achterhaald. 

Om hier een idee over op te doen zijn de functies rondom de Partij uitgewerkt in een aantal varianten. 
Hiermee willen we verkennen en inzicht krijgen in welke consequenties de diverse ontwerpvarianten met zich mee brengen.
Varianten 1 t/m 3 gaan van gegevensgericht naar handelingsgericht. Varianten 4 en 5 zijn handelingsgerichte API-specificaties waar polymorfie is toegepast. 

## Variant 1

In deze ontwerpvariant is er voor gekozen voor een REST API.  
De specificatie kan worden bekeken in [Swagger](./variant1/swagger-ui) of in [Redoc](./variant1/redoc).

## Variant 2

In deze ontwerpvariant wordt een eerste stap richting RPC gezet. De endpoints zijn genoemd naar de in te vullen functie. 

Er wordt nog wel gebruik gemaakt van de geeigende HTTP-request varianten. 

De specificatie kan worden bekeken in [Swagger](./variant2/swagger-ui) of in [Redoc](./variant2/redoc).

## Variant 3

In deze ontwerpvariant zijn de functies in post-enpoints vormgegeven.De endpoints zijn genoemd naar de in te vullen functie. 

De specificatie kan worden bekeken in [Swagger](./variant3/swagger-ui) of in [Redoc](./variant3/redoc).

## Variant 4

In deze ontwerpvariant is functioneel gelijk aan variant 3, maar de lees- en de bijhoudingsfuncties zijn gesplitst in aparte API's 

De specificatie van de lees-API kan worden bekeken in [Swagger](./variant4-lees/swagger-ui) of in [Redoc](./variant4-lees/redoc).

De specificatie van de bijhoudings-API kan worden bekeken in [Swagger](./variant4-bijhouding/swagger-ui) of in [Redoc](./variant4-bijhouding/redoc).

## Variant 5

Door het splitsen van de lees- en de bijhoudings-API onstaat ook de mogelijkheid om bv een handelingsgerichte bijhoudinges-API te combineren met een gegevensgerichte (REST-like) lees-API. 


De specificatie van de lees-API kan worden bekeken in [Swagger](./variant5-lees/swagger-ui) of in [Redoc](./variant5-lees/redoc).

De specificatie van de bijhoudings-API (gelijk aan variant 4) kan worden bekeken in [Swagger](./variant4-bijhouding/swagger-ui) of in [Redoc](./variant4-bijhouding/redoc).


## Variant 6

In deze ontwerpvariant zijn de vier benoemde functies in één POST endpoint. M.b.v. polymorfie is het mogelijk om aan te geven welke functie er aangeroepen wordt en kan de bijbehorende requestbody gevuld worden. 

De specificatie kan worden bekeken in [Swagger](./variant6/swagger-ui) of in [Redoc](./variant6/redoc).

## Variant 7

In deze ontwerpvariant zijn de vier benoemde functies verder gedetailleerd, maar wel in één POST endpoint opgenomen. M.b.v. polymorfie is het mogelijk om aan te geven welke functie er aangeroepen wordt en kan de bijbehorende requestbody gevuld worden. 

De specificatie kan worden bekeken in [Swagger](./variant7/swagger-ui) of in [Redoc](./variant7/redoc).
