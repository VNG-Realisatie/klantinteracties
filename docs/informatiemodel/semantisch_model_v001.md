---
layout: page-with-side-nav
title: Semantisch informatiemodel versie 0.0.1.
date: 03-07-2023
---

# Semantisch informatiemodel Versie 1

## Modellering in Enterprise Architect
Binnen VNG Realisatie wordt Enterprise Architect (EA) gebruikt voor de vastlegging van semantische informatiemodellen (SIM). Onderstaand figuur geeft de modellering van het SIM versie 1 weer zoals deze in EA is gemodelleerd.

<img src="assets/sim_ea_v1.png" alt="SIM in Enterprise Architect" width="1000"/>

De wijzigingen die in versie 2 zijn doorgevoerd t.o.v. deze versie zijn: 
  -	Alle objecten hebben een ID gekregen.
  -	De gaat over relaties zijn opnieuw gemodelleerd. 
    -	Klantcontact Bij Zaak is vervallen
    -	Object Van Klantcontact is toegevoegd
    -	Gaat over relaties tussen Klantcontact en respectievelijk Zaak, Klanttaak en Ander Object lopen nu via Object Van Klantcontact
    -	Ook de gaatOver relatie tussen Klantcontact en Interne Taak loopt nu via Object van klantcontact.
  -	Klanttaak
    -	Klanttaak is buiten het domein van klantinteracties geplaatst 
    -	De relatie ontstaan uit tussen Klanttaak en Zaak ligt daarmee buiten het domein van Klantinteracties en is dus uit het informatiemodel verwijderd.  
    -	De relatie tussen Klanttaak en Partij is verwijderd want deze relatie ligt buiten het domein van Klantinteracties.
  -	Inhoudsdeel
    -	Bijlage is hernoemd naar Inhoudsdeel 
    -	Aan Inhoudsdeel zijn de attributen Soort inhoudsdeel en Tekst toegevoegd.
    -	De Indicatie weer te geven is verwijderd.  
    -	Het Object (nog uit te werken) dat met de betreft relatie aan het klantcontact was gekoppeld is nu via het inhoudsdeel gerelateerd aan het klantcontact en hernoemd naar Overig Object.
    -	Er is een relatie (is)  toegevoegd tussen het Inhoudsdeel en het Ander object. Daarmee kan een gestructureerd object gerelateerd worden zonder dat dat vanuit deze standaard wordt voorgeschreven. 
  -	Digitaal Adres
    -	Aan het Digitaal Adres is het attribuut Indicatie actief toegevoegd
  -	Partij
    -	Aan Partij is het attribuut Soort partij toegevoegd
    -	Bij Partij is het subtype Contactpersoon toegevoegd. 
    -	Het object Werkt voor met de bijbehorende relaties is nu gemodelleerd als de werkte voor relatie van de Contactpersoon naar de Organisatie.
    -	De relaties vertegenwoordigt en wordt vertegenwoordigd door is vervangen door een recursieve relatie  vertegenwoordigde op Partij
  -	Interne taak
    -	Bij Interne taak komt indicatie geautomatiseerd verwerken te vervallen. Als een Interne Taak gekoppeld is (via uit te voeren door)  aan een geautomatiseerde actor dan is dat dus een geautomatiseerd te verwerken taak.  
    -	Dat een Interne taak  geleid kan hebben tot een Zaak hebben wordt niet als relevant voor klantinteracties gezien en de relatie is ontstaat uit tussen Interne taak en Zaak is verwijderd.
    -	Dat een Interne Taak is ontstaan uit een Klantcontact wordt nu vastgelegd middels het attribuut  ontstaan uit klantcontact in het Object van klantcontact.  De relatie ontstaan uit  is verwijderd. 
  -	Klantcontact
    -	Bij Klantcontact is het attribuut Initiatiefnemer hernoemd naar Initiator. 
    -	Bij Klantcontact is het attribuut  Vertrouwelijk opgenomen om aan te geven dat een Klantcontact  vertrouwelijk behandeld moet worden. Welke consequenties het vertrouwelijk zijn heeft moet nog in beeld gebracht worden. 
    -	De relatie met  met Actor  is hernoemd naar heeft als betrokkene en de De kardinaliteit bij de Actor is veranderd van 1 naar 1..*. Dit omdat er meerdere Actoren bij een Klantcontact betrokken kunnen zijn (bv. Bij een keukentafelgesprek) 
    -	De relatie Is betrokken bij (tussen Klantcontact en Betrokkene bij klantcontact) is van richting veranderd en heet nu Heeft als betrokkene. (Deze relatie is nog onderwerp van nadere analyse) 
    -	Het attribuut Inhoud is verwijderd. Alle inhoud wordt nu opgenomen in Inhoudsdelen. 
  -	Actor    
    -	De attributen Indicatie actief en Soort actor  zijn toegevoegd. De gewijzigde relaties zijn al eerder benoemd. 


