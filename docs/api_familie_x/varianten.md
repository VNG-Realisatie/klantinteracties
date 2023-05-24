---
layout: page-with-side-nav
title: API ontwerpvarianten
date: 14-04-2023
---

# Inleiding

Er zijn diverse ontwerpvarianten voor de API te bedenken. Om hier een idee over op te doen zijn de functies rondom de Partij uitgewerkt in een aantal varianten. 
Hiermee willen we verkennen en inzicht krijgen in welke consequenties de diverse ontwerpvarianten met zich mee brengen.

## Variant 1

In deze ontwerpvariant is er voor gekozen voor een REST API.  
De specificatie kan worden bekeken in [Swagger](./variant1/swagger-ui) of in [Redoc](./variant1/redoc).

## Variant 2

In deze ontwerpvariant wordt een eerste stap richting RPC gezet. De endpoints zijn genoemd naar de in te vullen functie. 
Er wordt nog wel gebruik gemaakt van de geeigende HTTP-request varianten. 
De specificatie kan worden bekeken in [Swagger](./variant2/swagger-ui) of in [Redoc](./variant2/redoc).

## Variant 3

In deze ontwerpvariant zijn de vier benoemde functies in vier post-enpoints vormgegeven.De endpoints zijn genoemd naar de in te vullen functie. 
De specificatie kan worden bekeken in [Swagger](./variant3/swagger-ui) of in [Redoc](./variant3/redoc).

## Variant 4

In deze ontwerpvariant zijn de vier benoemde functies in één POST endpoint. M.b.v. polymorfie is het mogelijk om aan te geven welke functie er aangeroepen wordt en kan de bijbehorende requestbody gevuld worden. 
De specificatie kan worden bekeken in [Swagger](./variant4/swagger-ui) of in [Redoc](./variant4/redoc).

## Variant 5

In deze ontwerpvariant zijn de vier benoemde verder gedetailleerd, maar wel in één POST endpoint opgenomen. M.b.v. polymorfie is het mogelijk om aan te geven welke functie er aangeroepen wordt en kan de bijbehorende requestbody gevuld worden. 
De specificatie kan worden bekeken in [Swagger](./variant5/swagger-ui) of in [Redoc](./variant5/redoc).
