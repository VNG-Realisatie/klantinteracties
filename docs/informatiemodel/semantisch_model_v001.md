---
layout: page-with-side-nav
title: Semantisch informatiemodel versie 0.0.1.
date: 03-07-2023
---

# Semantisch informatiemodel: Oude versies

## Modellering in Enterprise Architect
Binnen VNG Realisatie wordt Enterprise Architect (EA) gebruikt voor de vastlegging van semantische informatiemodellen (SIM). 


Onderstaand figuur geeft de modellering van het SIM versie 0.0.2 weer zoals deze in EA was gemodelleerd.

<img src="assets/SIM_Klantinteracties_v002.png" alt="SIM in Enterprise Architect" width="1000"/>

De wijzigingen die in versie 0.0.3 zijn doorgevoerd t.o.v. deze versie zijn: 
  -	De definities en de MIM-egenschappen "Herkomst" en "Herkomst Definitie" zijn gecorrigeerd.
    Definities van objecttypen en attribuutsoorten die aan andere informatiemodellen zijn ontleend zijn gelijkgetrokken met de definities uit die informatiemodellen.
   	Met de "Herkomst" en de "Herkomst definitie" meta-eigenschappen wordt naar de juiste bron verwezen. 
  -	Gegevensgroeptype : Persoonsnaamgegevens is gewijzigd naar Aanspreeknaam.
  -	Attribuutsoorten :
    - Persoon.Naam is gewijzigd naar Persoon.Aanspreeknaam
    - Contactpersoon.Naam is gewijzigd naar Contactpersoon.Aanspreeknaam
    - Contactpersoon.functie is gewijzigd naar Contactpersoon.Functie

Onderstaand figuur geeft de modellering van het SIM versie 0.0.1 weer zoals deze in EA was gemodelleerd.

<img src="assets/SIM_Klantinteracties_v001.png" alt="SIM in Enterprise Architect" width="1000"/>

De wijzigingen die in versie 0.0.2 zijn doorgevoerd t.o.v. deze versie zijn: 
  -	Alle objecten hebben een ID gekregen.
  -	Partij
    -	Aan *Partij* is het attribuut *Soort partij* toegevoegd
    -	Bij *Partij* is het subtype *Contactpersoon* toegevoegd. 
    -	Het object *Werkt voor* met de bijbehorende relaties is nu gemodelleerd als de *werkte voor* relatie van de *Contactpersoon* naar de *Organisatie*.
    -	De relaties *vertegenwoordigt* en *wordt vertegenwoordigd door* is vervangen door een recursieve relatie *vertegenwoordigde* op *Partij*
  -	Interne taak
    -	Bij *Interne taak* komt *indicatie geautomatiseerd* verwerken te vervallen. Als een *Interne Taak* gekoppeld is (via uit te voeren door)  aan een *geautomatiseerde actor* dan is dat dus een geautomatiseerd te verwerken taak.
    - Dat een Interne taak  geleid kan hebben tot een Zaak hebben wordt niet als relevant voor klantinteracties gezien en de relatie is ontstaat uit tussen Interne taak en Zaak is verwijderd.​
    - Dat een Interne Taak is ontstaan uit een Klantcontact wordt nu vastgelegd middels het attribuut  ontstaan uit klantcontact in het Object van klantcontact.  De relatie ontstaan uit  is verwijderd. ​
  -	Klantcontact
    -	Bij *Klantcontact* is het attribuut *Initiatiefnemer* hernoemd naar *Initiator*. 
    -	Bij *Klantcontact* is het attribuut *Vertrouwelijk* opgenomen om aan te geven dat een *Klantcontact* vertrouwelijk behandeld moet worden. Welke consequenties het vertrouwelijk zijn heeft moet nog in beeld gebracht worden. 
    -	De relatie met *Actor* is hernoemd naar *heeft als betrokkene* en de kardinaliteit bij de *Actor* is veranderd van 1 naar 1..*. Dit omdat er meerdere *Actoren* bij een *Klantcontact* betrokken kunnen zijn (bv. Bij een keukentafelgesprek) 
    -	De relatie *Is betrokken bij* (tussen *Klantcontact* en *Betrokkene bij klantcontact*) is van richting veranderd en heet nu *Heeft als betrokkene*. (Deze relatie is nog onderwerp van nadere analyse) 
    -	Het attribuut *Inhoud* is verwijderd. Alle inhoud wordt nu opgenomen in *Inhoudsdelen*.
    -	Het attribuut *onderwerp* is verplaatst naar het object *Onderwerpdeel* als *Tekst*
    -	Het attribuut taal is toegevoegd
  - Betrokkene bij klantcontact​
    - De attributen voorkeurstaal en voorkeurskanaal zijn verwijderd.​
  -	Actor    
    -	De attributen *Indicatie actief* en *Soort actor* zijn toegevoegd. De gewijzigde relaties zijn al eerder benoemd. 
  - Onderwerpdeel
    - De *gaat over* relaties zijn opnieuw gemodelleerd. 
    -	Objecttype *Klantcontact Bij Zaak* is vervallen
    -	Objecttype  *Onderwerpdeel* is toegevoegd
    -	*Gaat over* relaties tussen *Klantcontact* en respectievelijk *Zaak*, *Klanttaak* en *Ander Object* lopen nu via Onderwerpdeel
    -	Ook de *Gaat over* relatie tussen *Klantcontact* en *Interne Taak* loopt nu via *Onderwerp*.
  -	Klanttaak
    -	*Klanttaak* is buiten het domein van klantinteracties geplaatst 
    -	De relatie *ontstaan uit* tussen *Klanttaak* en *Zaak* ligt daarmee buiten het domein van Klantinteracties en is dus uit het informatiemodel verwijderd.  
    -	De relatie tussen *Klanttaak* en *Partij* is verwijderd want deze relatie ligt buiten het domein van Klantinteracties.
  -	Inhoudsdeel
    -	*Bijlage* is hernoemd naar *Inhoudsdeel* 
    -	Aan *Inhoudsdeel* zijn de attributen *Soort inhoudsdeel* en *Tekst* toegevoegd.
    -	De *Indicatie weer te geven* is verwijderd.  
    -	Het *Object (nog uit te werken)* dat met de betreft relatie aan het *Klantcontact* was gekoppeld is nu via het *Inhoudsdeel* gerelateerd aan het *Klantcontact* en hernoemd naar *Overig Object*.
    -	Er is een relatie *is* toegevoegd tussen het *Inhoudsdeel* en het *Ander object*. Daarmee kan een gestructureerd object gerelateerd worden zonder dat dat vanuit deze standaard wordt voorgeschreven. 
  -	Digitaal Adres
    -	Aan het *Digitaal Adres* is het attribuut *Indicatie actief* toegevoegd


