---
layout: page-with-side-nav
title: API ontwerpvarianten
date: 14-04-2023
---

# Inleiding

Er zijn diverse ontwerpvarianten voor de API te bedenken. Om hier een idee over op te doen zijn de functies rondom de Partij uitgewerkt in een aantal varianten. 
Hiermee willen we verkennen en inzicht krijgen in welke consequenties de diverse ontwerpvarianten met zich mee brengen.

## Variant 1

In deze ontwerpvariant is er voor gekozen om relatief dicht bij een REST-like API te blijven. De spoecificatie kan [hier](./variant1/swagger-ui) bekeken worden in swaggerui.

## Variant 2

In deze ontwerpvariant wordt een eerste stap richting RPC gezet. De endpoints zijn genoemd naar de in te vullen functie. 
Er wordt nog wel gebruik gemaakt van de geeigende HTTP-request varianten. De spoecificatie kan [hier](./variant2/swagger-ui) bekeken worden in swaggerui.

## Variant 3

In deze ontwerpvariant zijn de vier benoemde functies in vier post-enpoints vormgegeven.De endpoints zijn genoemd naar de in te vullen functie. 
De spoecificatie kan [hier](./variant3/swagger-ui) bekeken worden in swaggerui.

## Variant 4

In deze ontwerpvariant zijn de vier benoemde functies in één POST endpoint. M.b.v. polymorfie is het mogelijk om aan te geven welke functie er aangeroepen wordt en kan de bijbehorende requestbody gevuld worden. 
De spoecificatie kan [hier](./variant4/swagger-ui) bekeken worden in swaggerui.
