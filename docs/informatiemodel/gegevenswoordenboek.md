---
layout: page-with-side-nav
title: Gegevenswoordenboek informatiemodel klantinteracties
date: 11-10-2023
---

<!DOCTYPE HTML><html>
   <head>
      <meta http-equiv="Content-Type" content="text/html; charset=UTF-8">
      <meta charset="UTF-8">
      <style type="text/css">
                    body {
                    font-family:"Calibri","Verdana",sans-serif;
                    font-size:11.0pt;
                    }
                    table {
                    width: 100%;
                    }
                    table, th, td {
                    border: none;
                    font-size:11.0pt;
                    }
                    td {
                    vertical-align: top;
                    }
                    h1, h2, h3, h4 {
                    color:#003359;
                    }
                    h1 {
                    page-break-before:always;
                    font-size:16.0pt;
                    }
                    h2 {
                    font-size:12.0pt;
                    }
                    h3 {
                    font-size:12.0pt;
                    }
                    tr.tableheader {
                    font-style: italic;
                    }
                    a.anchor {
                    color: inherit;
                    text-decoration: none;
                    }
                    a.anchor:hover {
                    color: inherit;
                    text-decoration: underline;
                    }
                    a.link {
                    color: inherit;
                    text-decoration: none;
                    }
                    a.link:hover {
                    color: blue;
                    text-decoration: underline;
                    }
                </style>
   </head>
   <body>
      <p>BASISMODEL
         :
         SIM Klantinteracties
         :
         2.0.0
         :
         2023-10-11T14:31:36Z</p>
      <p>
         ID: EAPK_272B109E_0738_42bd_9D43_C4F87B5E8B8D</p>
      <div><strong>Domein: Model</strong><div>
            <h1>Objecttypen </h1>
            
            <div><a class="anchor" name="global_class_Model_Klantcontact"></a><h2> Klantcontact</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Klantcontact</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Contact tussen een klant of een vertegenwoordiger van een klant en de gemeente over
                           een onderwerp.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%">ID</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Indicatie abstract object</b></td>
                        <td width="70%">Nee</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           ID
                           </td>
                        <td width="50%">Unieke (technische) identificatiecode van het klantcontact.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Nummer
                           </td>
                        <td width="50%">Uniek identificerend nummer dat tijdens communicatie tussen mensen kan worden gebruikt
                           om het specifieke klantcontact aan te duiden.</td>
                        <td width="10%">
                           Identificerend nummer
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Kanaal
                           </td>
                        <td width="50%">Communicatiekanaal dat bij het klantcontact werd gebruikt.</td>
                        <td width="10%">
                           Kanaal
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Onderwerp
                           </td>
                        <td width="50%">Datgene waarover het klantcontact ging.</td>
                        <td width="10%">
                           Omschrijving-lang
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Inhoud
                           </td>
                        <td width="50%">Informatie die tijdens het klantcontact werd overgebracht of uitgewisseld, voor zover
                           die voor betrokkenen of actoren relevant is.</td>
                        <td width="10%">
                           Tekst
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Initiator
                           </td>
                        <td width="50%">Degene die het klantcontact initieerde.</td>
                        <td width="10%">
                           Initiator
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Indicatie contact gelukt
                           </td>
                        <td width="50%">Geeft, indien bekend, aan of de poging contact tussen de gemeente en inwoner(s) of
                           organisatie(s) tot stand te brengen succesvol was.</td>
                        <td width="10%">
                           Indicatie ja nee onbekend
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Taal
                           </td>
                        <td width="50%">Taal die bij het klantcontact werd gesproken of geschreven.</td>
                        <td width="10%">
                           Taal
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Vertrouwelijk
                           </td>
                        <td width="50%">Geeft aan of onderwerp, inhoud en kenmerken van het klantcontact vertrouwelijk moeten
                           worden behandeld.</td>
                        <td width="10%">
                           Indicatie Ja Nee
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Plaatsgevonden op
                           </td>
                        <td width="50%">Datum en tijdstip waarop het klantontact plaatsvond. Als het klantcontact een gesprek
                           betrof, is dit het moment waarop het gesprek begon. Als het klantcontact verzending
                           of ontvangst van informatie betrof, is dit bij benadering het moment waarop informatie
                           door gemeente verzonden of ontvangen werd.</td>
                        <td width="10%">
                           Datumtijd
                           </td>
                        <td width="10%">1</td>
                     </tr>
                  </tbody>
               </table>
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht relaties</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Relatienaam met kardinaliteiten</i></td>
                        <td><i>Definitie</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Klantcontact
                           [ 0 .. * ]
                           
                           had betrokken
                           
                           
                           Actor
                           
                           [ 1 .. * ]
                           </td>
                        <td width="50%">Actor die bij een klantcontact betrokken was.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Klantcontact
                           [ 1 ]
                           
                           had
                           
                           
                           Betrokkene bij klantcontact
                           
                           [ 0 .. * ]
                           </td>
                        <td width="50%">Persoon of organisatie die betrokken was bij een klantcontact.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Klantcontact
                           [ 1 ]
                           
                           ging over
                           
                           
                           Onderwerpobject
                           
                           [ 0 .. * ]
                           </td>
                        <td width="50%">Onderwerpobject dat tijdens een klantcontact aan de orde kwam.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Klantcontact
                           [ 1 ]
                           
                           omvatte
                           
                           
                           Inhoudsobject
                           
                           [ 0 .. * ]
                           </td>
                        <td width="50%">Inhoudsobject dat onderdeel was van de inhoud van het klantcontact.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           
                           Onderwerpobject
                           
                           [ 0 .. * ]
                           
                           was
                           
                           Klantcontact
                           [ 0 .. 1 ]
                           </td>
                        <td width="50%">Klantcontact dat een onderwerpobject was.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           
                           Interne taak
                           
                           [ 0 .. * ]
                           
                           ontstond naar aanleiding van
                           
                           Klantcontact
                           [ 1 ]
                           </td>
                        <td width="50%">Klantcontact dat leidde tot een interne taak.</td>
                     </tr>
                  </tbody>
               </table>
               
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Toelichting</b></td>
                     </tr>
                  </tbody>
               </table>
               <table>
                  <tbody>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="95%">Het klantcontact is bedoeld om inwoners of ondernemers die contact hebben gehad met
                           de gemeente op een voor hen zo begrijpelijk en relevant mogelijke manier te infomeren
                           over de inhoud van dat contact. Over een klantcontact vastgelegde informatie kan bijvoorbeeld
                           (na inloggen) worden getoond op de gemeentelijke website of telefonisch worden verstrekt
                           door een medewerker van het klantcontactcentrum. Als gevolg hiervan is de volledige
                           inhoud van een klantcontact geschikt voor openbaarmaking aan betrokken inwoners.</td>
                     </tr>
                  </tbody>
               </table>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Betrokkenebijklantcontact"></a><h2> Betrokkene bij klantcontact</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Betrokkene bij klantcontact</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Ofwel betrokkenheid van een partij bij een klantcontact, eventueel aangevuld met specifiek
                           voor opvolging van dat klantcontact te gebruiken contactgegevens, ofwel voor opvolging
                           van een klantcontact te gebruiken contactgegevens van een tijdens dat klantcontact
                           niet als partij gekende persoon.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%">ID</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Indicatie abstract object</b></td>
                        <td width="70%">Nee</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           ID
                           </td>
                        <td width="50%">Unieke (technische) identificatiecode van de betrokkene bij klantcontact.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Rol
                           </td>
                        <td width="50%">Rol die de betrokkene bij klantcontact tijdens dat contact vervulde.</td>
                        <td width="10%">
                           Klantcontactrol
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Organisatienaam
                           </td>
                        <td width="50%">Naam van de organisatie waarmee de betrokkene bij klantcontact een relatie had.</td>
                        <td width="10%">
                           Naam-lang
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Contactnaam
                           :</td>
                        <td width="50%">Naam die de betrokkene bij klantcontact bij opvolging van dat contact wil gebruiken.</td>
                        <td width="10%">
                           Contactnaam
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Voorletters
                           </td>
                        <td width="50%">Een afkorting van de voornamen. Meestal de beginletter, maar in sommige gevallen de
                           beginletter gecombineerd met de tweede letter van een voornaam.</td>
                        <td width="10%">
                           Voorletters
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Voornaam
                           </td>
                        <td width="50%">De voornaam die de persoon wil gebruiken tijdens communicatie met de gemeente.</td>
                        <td width="10%">
                           Naam-kort
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Voorvoegsel achternaam
                           </td>
                        <td width="50%">Een eventueel voorvoegsel dat hoort bij de achternaam die de persoon wil gebruiken
                           tijdens communicatie met de gemeente.</td>
                        <td width="10%">
                           Voorvoegsel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Achternaam
                           </td>
                        <td width="50%">Een achternaam die de persoon wil gebruiken tijdens communicatie met de gemeente.</td>
                        <td width="10%">
                           Omschrijving-lang
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Correspondentieadres
                           :</td>
                        <td width="50%">Adres waarop de betrokkene bij klantcontact naar aanleiding van dat contact te versturen
                           post wil ontvangen.</td>
                        <td width="10%">
                           Correspondentieadres
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           NummeraanduidingID
                           </td>
                        <td width="50%">Identificatie van het adres bij de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Adresregel 1
                           </td>
                        <td width="50%">Eerste deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Adresregel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Adresregel 2
                           </td>
                        <td width="50%">Tweede deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Adresregel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Adresregel 3
                           </td>
                        <td width="50%">Derde van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Adresregel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Land
                           </td>
                        <td width="50%">Een code, opgenomen in Tabel 34, Landentabel, die het land (buiten Nederland) aangeeft
                           alwaar de ingeschrevene verblijft. </td>
                        <td width="10%">
                           Land
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Bezoekadres
                           :</td>
                        <td width="50%">Adres waarop de betrokkene bij klantcontact in naar aanleiding van dat contact af
                           te leggen bezoeken wil ontvangen.</td>
                        <td width="10%">
                           Bezoekadres
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           NummeraanduidingID
                           </td>
                        <td width="50%">Identificatie van het adres bij de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Adresregel 1
                           </td>
                        <td width="50%">Eerste deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Adresregel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Adresregel 2
                           </td>
                        <td width="50%">Tweede deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Adresregel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Adresregel 3
                           </td>
                        <td width="50%">Derde deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Adresregel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Land
                           </td>
                        <td width="50%">Een code, opgenomen in Tabel 34, Landentabel, die het land (buiten Nederland) aangeeft
                           alwaar de ingeschrevene verblijft. </td>
                        <td width="10%">
                           Land
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                  </tbody>
               </table>
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht relaties</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Relatienaam met kardinaliteiten</i></td>
                        <td><i>Definitie</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Betrokkene bij klantcontact
                           [ 0 .. * ]
                           
                           was
                           
                           
                           Partij
                           
                           [ 0 .. 1 ]
                           </td>
                        <td width="50%">Betrokkene bij klantcontact die een partij was.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Betrokkene bij klantcontact
                           [ 0 .. 1 ]
                           
                           verstrekte voor opvolging van klantcontact
                           
                           
                           Digitaal adres
                           
                           [ 0 .. * ]
                           </td>
                        <td width="50%">Digitaal adres dat een betrokkene bij klantcontact verstrekte voor gebruik bij opvolging
                           van een klantcontact.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           
                           Klantcontact
                           
                           [ 1 ]
                           
                           had
                           
                           Betrokkene bij klantcontact
                           [ 0 .. * ]
                           </td>
                        <td width="50%">Persoon of organisatie die betrokken was bij een klantcontact.</td>
                     </tr>
                  </tbody>
               </table>
               
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Toelichting</b></td>
                     </tr>
                  </tbody>
               </table>
               <table>
                  <tbody>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="95%"><br>                           Klantcontact-betrokkene kent afhankelijk van mogelijkheid
                           of wenselijkheid om in het kader van (opvolging van) de klantinteractie persoonsgegevens
                           te verwerken twee gebruiksmogelijkheden.<br>                           <br>                           1) is van de bij het klantcontact betrokken inwoner of
                           ondernemer na identificatie en/of authenticatie voldoende duidelijk wie die is of
                           vertegenwoordigt, dan wordt eerst opgezocht of deze inwoner of ondernemer reeds als
                           partij bij de gemeente bekend is. Is dat niet zo, dan kan vervolgens een partij worden
                           geregistreerd. Tussen de opgezochte of gecreëerde partij en klantcontact-betrokkene
                           wordt vervolgens een relatie gelegd. Als de betrokkene aangeeft dat alléén voor opvolging
                           van het klantcontact andere dan de bij partij geregistreerde 'default'-contactgegevens
                           gebruikt moeten, worden deze alternatieve contactgegevens vastgelegd in klantcontact-betrokkene.
                           Voor opvolging van het klantcontact gelden de in Klantcontact-betrokkene vastgelegde
                           contactgegevens dus boven gelijkaardige gegevens die bij partij zijn geregistreerd.<br>                           <br>                           2) is van de bij het klantcontact betrokken inwoner of
                           ondernemer na eventuele identificatie en/of authenticatie onvoldoende duidelijk is
                           wie die is of vertegenwoordigt, dan kan in klantcontact-betrokkene een set voor opvolging
                           van het klantcontact benodigde of gewenste contactgegevens worden geregistreerd. In
                           dit geval is er dus géén sprake van een realtie tussen klantcontact-betrokkene en
                           partij.<br>                        </td>
                     </tr>
                  </tbody>
               </table>
               </div>
            
            <div><a class="anchor" name="global_class_Model_OverigObject"></a><h2> Overig Object</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Overig Object</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Object, geregistreerd in het register voor Overige objectregistraties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Indicatie abstract object</b></td>
                        <td width="70%">Nee</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           ID
                           </td>
                        <td width="50%">Unieke identificatie van het Overig Object.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                  </tbody>
               </table>
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht relaties</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Relatienaam met kardinaliteiten</i></td>
                        <td><i>Definitie</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           
                           Inhoudsobject
                           
                           [ 0 .. 1 ]
                           
                           was
                           
                           Overig Object
                           [ 0 .. 1 ]
                           </td>
                        <td width="50%">Overig object dat een inhoudsobject was.</td>
                     </tr>
                  </tbody>
               </table>
               
               
               </div>
            
            <div><a class="anchor" name="global_class_Model_Organisatie"></a><h2> Organisatie</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Organisatie</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Geformaliseerde entiteit die geen natuurlijk persoon is en maatschappelijke activiteiten
                           uitvoert.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Indicatie abstract object</b></td>
                        <td width="70%">Nee</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Naam
                           </td>
                        <td width="50%">Naam van de organisatie.</td>
                        <td width="10%">
                           Naam-lang
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                  </tbody>
               </table>
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht relaties</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Relatienaam met kardinaliteiten</i></td>
                        <td><i>Definitie</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           
                           Contactpersoon
                           
                           [ 0 .. * ]
                           
                           werkte voor
                           
                           Organisatie
                           [ 0 .. 1 ]
                           </td>
                        <td width="50%">Organisatie waarvoor een contactpersoon werkte.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Organisatie
                           is specialisatie van
                           
                           Partij
                           
                           </td>
                        <td width="50%">Persoon of organisatie waarmee de gemeente een relatie heeft.</td>
                     </tr>
                  </tbody>
               </table>
               
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Toelichting</b></td>
                     </tr>
                  </tbody>
               </table>
               <table>
                  <tbody>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="95%">Een organisatie met rechtspersoonlijkheid, of een eenmanszaak, vennootschap onder
                           firma, maatschap of commanditaire vennootschap of andere organisatie zonder rechtspersoonlijkheid.</td>
                     </tr>
                  </tbody>
               </table>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Onderwerpobject"></a><h2> Onderwerpobject</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Onderwerpobject</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Object dat onderwerp van een klantcontact was. </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">08-06-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%">ID</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Indicatie abstract object</b></td>
                        <td width="70%">Nee</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           ID
                           </td>
                        <td width="50%">Unieke (technische) identificatiecode van het onderwerpdeel.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Objectidentificator
                           :</td>
                        <td width="50%">Gegevens die een onderwerpobject in een extern register uniek identificeren.</td>
                        <td width="10%">
                           Identificator
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Objecttype
                           </td>
                        <td width="50%">Type van het object.</td>
                        <td width="10%">
                           Soort object
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Soort Object ID
                           </td>
                        <td width="50%">Naam van de eigenschap die het object identificeert.</td>
                        <td width="10%">
                           Soort object
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Object ID
                           </td>
                        <td width="50%">Waarde van de eigenschap die het object identificeert.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Register
                           </td>
                        <td width="50%">Binnen het landschap van registers unieke omschrijving van het register waarin het
                           object is geregistreerd.</td>
                        <td width="10%">
                           Extern register
                           </td>
                        <td width="10%">1</td>
                     </tr>
                  </tbody>
               </table>
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht relaties</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Relatienaam met kardinaliteiten</i></td>
                        <td><i>Definitie</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Onderwerpobject
                           [ 0 .. * ]
                           
                           was
                           
                           
                           Klantcontact
                           
                           [ 0 .. 1 ]
                           </td>
                        <td width="50%">Klantcontact dat een onderwerpobject was.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Onderwerpobject
                           [ 0 .. * ]
                           
                           was
                           
                           
                           Ander Object
                           
                           [ 0 .. 1 ]
                           </td>
                        <td width="50%">Ander object dat een onderwerpobject was.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Onderwerpobject
                           [ 0 .. * ]
                           
                           was
                           
                           
                           Klanttaak
                           
                           [ 0 .. 1 ]
                           </td>
                        <td width="50%">Klanttaak die een onderwerpobject was.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Onderwerpobject
                           [ 0 .. * ]
                           
                           was
                           
                           
                           Zaak
                           
                           [ 0 .. 1 ]
                           </td>
                        <td width="50%">Zaak die een onderwerpobject was.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           
                           Klantcontact
                           
                           [ 1 ]
                           
                           ging over
                           
                           Onderwerpobject
                           [ 0 .. * ]
                           </td>
                        <td width="50%">Onderwerpobject dat tijdens een klantcontact aan de orde kwam.</td>
                     </tr>
                  </tbody>
               </table>
               
               
               </div>
            
            <div><a class="anchor" name="global_class_Model_Partij"></a><h2> Partij</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Partij</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Persoon of organisatie waarmee de gemeente een relatie heeft.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%">ID</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Indicatie abstract object</b></td>
                        <td width="70%">Ja</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           ID
                           </td>
                        <td width="50%">Unieke (technische) identificatiecode van de partij.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Nummer
                           </td>
                        <td width="50%">Uniek identificerend nummer dat tijdens communicatie tussen mensen kan worden gebruikt
                           om de specifieke partij aan te duiden.</td>
                        <td width="10%">
                           Partijnummer
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Interne notitie
                           </td>
                        <td width="50%">Mededelingen, aantekeningen of bijzonderheden over de partij, bedoeld voor intern
                           gebruik.</td>
                        <td width="10%">
                           Tekst
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Soort partij
                           </td>
                        <td width="50%">Geeft aan van welke specifieke soort partij sprake is.</td>
                        <td width="10%">
                           Soort partij
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Indicatie geheimhouding
                           </td>
                        <td width="50%">Geeft aan of de verstrekker van partijgegevens heeft aangegeven dat deze gegevens
                           als geheim beschouwd moeten worden.</td>
                        <td width="10%">
                           Indicatie Ja Nee
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Voorkeurskanaal
                           </td>
                        <td width="50%">Kanaal dat de partij bij voorkeur gebruikt voor contact met de gemeente.</td>
                        <td width="10%">
                           Kanaal
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Voorkeurstaal
                           </td>
                        <td width="50%">Taal waarin de partij bij voorkeur contact heeft met de gemeente.</td>
                        <td width="10%">
                           Taal
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Indicatie actief
                           </td>
                        <td width="50%">Geeft aan of de contactgegevens van de partij nog gebruikt morgen worden om contact
                           op te nemen. Gegevens van niet-actieve partijen mogen hiervoor niet worden gebruikt.</td>
                        <td width="10%">
                           Indicatie Ja Nee
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Bezoekadres
                           :</td>
                        <td width="50%">Adres waarop de partij door gemeente bezocht wil worden.</td>
                        <td width="10%">
                           Bezoekadres
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           NummeraanduidingID
                           </td>
                        <td width="50%">Identificatie van het adres bij de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Adresregel 1
                           </td>
                        <td width="50%">Eerste deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Adresregel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Adresregel 2
                           </td>
                        <td width="50%">Tweede deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Adresregel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Adresregel 3
                           </td>
                        <td width="50%">Derde deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Adresregel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Land
                           </td>
                        <td width="50%">Een code, opgenomen in Tabel 34, Landentabel, die het land (buiten Nederland) aangeeft
                           alwaar de ingeschrevene verblijft. </td>
                        <td width="10%">
                           Land
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Correspondentieadres
                           :</td>
                        <td width="50%">Adres waarop de partij post van de gemeente wil ontvangen.</td>
                        <td width="10%">
                           Correspondentieadres
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           NummeraanduidingID
                           </td>
                        <td width="50%">Identificatie van het adres bij de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Adresregel 1
                           </td>
                        <td width="50%">Eerste deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Adresregel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Adresregel 2
                           </td>
                        <td width="50%">Tweede deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Adresregel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Adresregel 3
                           </td>
                        <td width="50%">Derde van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Adresregel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Land
                           </td>
                        <td width="50%">Een code, opgenomen in Tabel 34, Landentabel, die het land (buiten Nederland) aangeeft
                           alwaar de ingeschrevene verblijft. </td>
                        <td width="10%">
                           Land
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                  </tbody>
               </table>
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht relaties</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Relatienaam met kardinaliteiten</i></td>
                        <td><i>Definitie</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Partij
                           [ 0 .. 1 ]
                           
                           had
                           
                           
                           Partij-identificator
                           
                           [ 1 .. * ]
                           </td>
                        <td width="50%">Partij-identificator die een partij had.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Partij
                           [ 0 .. * ]
                           
                           vertegenwoordigde
                           
                           
                           Partij
                           
                           [ 0 .. * ]
                           </td>
                        <td width="50%">Partij die een andere partij vertegenwoordigde.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Partij
                           [ 0 .. 1 ]
                           
                           verstrekte voor toekomstig contact
                           
                           
                           Digitaal adres
                           
                           [ 0 .. * ]
                           </td>
                        <td width="50%">Digitaal adres dat een partij verstrekte voor gebruik bij toekomstig contact met de
                           gemeente.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           
                           Betrokkene bij klantcontact
                           
                           [ 0 .. * ]
                           
                           was
                           
                           Partij
                           [ 0 .. 1 ]
                           </td>
                        <td width="50%">Betrokkene bij klantcontact die een partij was.</td>
                     </tr>
                  </tbody>
               </table>
               
               
               </div>
            
            <div><a class="anchor" name="global_class_Model_Inhoudsobject"></a><h2> Inhoudsobject</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Inhoudsobject</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Object dat tijdens een klantcontact werd gemaakt of overgebracht.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%">ID</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Indicatie abstract object</b></td>
                        <td width="70%">Nee</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           ID
                           </td>
                        <td width="50%">Unieke (technische) identificatiecode van het inhoudsdeel.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Objectidentificator
                           :</td>
                        <td width="50%">Gegevens die een inhoudsobject in een extern register uniek identificeren.</td>
                        <td width="10%">
                           Identificator
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Objecttype
                           </td>
                        <td width="50%">Type van het object.</td>
                        <td width="10%">
                           Soort object
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Soort Object ID
                           </td>
                        <td width="50%">Naam van de eigenschap die het object identificeert.</td>
                        <td width="10%">
                           Soort object
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Object ID
                           </td>
                        <td width="50%">Waarde van de eigenschap die het object identificeert.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Register
                           </td>
                        <td width="50%">Binnen het landschap van registers unieke omschrijving van het register waarin het
                           object is geregistreerd.</td>
                        <td width="10%">
                           Extern register
                           </td>
                        <td width="10%">1</td>
                     </tr>
                  </tbody>
               </table>
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht relaties</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Relatienaam met kardinaliteiten</i></td>
                        <td><i>Definitie</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Inhoudsobject
                           [ 0 .. 1 ]
                           
                           was
                           
                           
                           Informatieobject
                           
                           [ 0 .. 1 ]
                           </td>
                        <td width="50%">Informatieobject dat een inhoudsobject was.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Inhoudsobject
                           [ 0 .. 1 ]
                           
                           was
                           
                           
                           Overig Object
                           
                           [ 0 .. 1 ]
                           </td>
                        <td width="50%">Overig object dat een inhoudsobject was.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Inhoudsobject
                           [ 0 .. 1 ]
                           
                           was
                           
                           
                           Ander Object
                           
                           [ 0 .. 1 ]
                           </td>
                        <td width="50%">Ander object dat een inhoudsobject was.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           
                           Klantcontact
                           
                           [ 1 ]
                           
                           omvatte
                           
                           Inhoudsobject
                           [ 0 .. * ]
                           </td>
                        <td width="50%">Inhoudsobject dat onderdeel was van de inhoud van het klantcontact.</td>
                     </tr>
                  </tbody>
               </table>
               
               
               </div>
            
            <div><a class="anchor" name="global_class_Model_Contactpersoon"></a><h2> Contactpersoon</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Contactpersoon</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Natuurlijk persoon die werkte voor een organisatie, of natuurlijk persoon die een
                           andere persoon vertegenwoordigde.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Indicatie abstract object</b></td>
                        <td width="70%">Nee</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Contactnaam
                           :</td>
                        <td width="50%">De naam die de contactpersoon wil gebruiken tijdens contact met de gemeente.</td>
                        <td width="10%">
                           Contactnaam
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Voorletters
                           </td>
                        <td width="50%">Een afkorting van de voornamen. Meestal de beginletter, maar in sommige gevallen de
                           beginletter gecombineerd met de tweede letter van een voornaam.</td>
                        <td width="10%">
                           Voorletters
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Voornaam
                           </td>
                        <td width="50%">De voornaam die de persoon wil gebruiken tijdens communicatie met de gemeente.</td>
                        <td width="10%">
                           Naam-kort
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Voorvoegsel achternaam
                           </td>
                        <td width="50%">Een eventueel voorvoegsel dat hoort bij de achternaam die de persoon wil gebruiken
                           tijdens communicatie met de gemeente.</td>
                        <td width="10%">
                           Voorvoegsel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Achternaam
                           </td>
                        <td width="50%">Een achternaam die de persoon wil gebruiken tijdens communicatie met de gemeente.</td>
                        <td width="10%">
                           Omschrijving-lang
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                  </tbody>
               </table>
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht relaties</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Relatienaam met kardinaliteiten</i></td>
                        <td><i>Definitie</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Contactpersoon
                           [ 0 .. * ]
                           
                           werkte voor
                           
                           
                           Organisatie
                           
                           [ 0 .. 1 ]
                           </td>
                        <td width="50%">Organisatie waarvoor een contactpersoon werkte.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Contactpersoon
                           is specialisatie van
                           
                           Partij
                           
                           </td>
                        <td width="50%">Persoon of organisatie waarmee de gemeente een relatie heeft.</td>
                     </tr>
                  </tbody>
               </table>
               
               
               </div>
            
            <div><a class="anchor" name="global_class_Model_Persoon"></a><h2> Persoon</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Persoon</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Natuurlijk persoon.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Indicatie abstract object</b></td>
                        <td width="70%">Nee</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Contactnaam
                           :</td>
                        <td width="50%">De naam die de persoon wil gebruiken tijdens contact met de gemeente.</td>
                        <td width="10%">
                           Contactnaam
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Voorletters
                           </td>
                        <td width="50%">Een afkorting van de voornamen. Meestal de beginletter, maar in sommige gevallen de
                           beginletter gecombineerd met de tweede letter van een voornaam.</td>
                        <td width="10%">
                           Voorletters
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Voornaam
                           </td>
                        <td width="50%">De voornaam die de persoon wil gebruiken tijdens communicatie met de gemeente.</td>
                        <td width="10%">
                           Naam-kort
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Voorvoegsel achternaam
                           </td>
                        <td width="50%">Een eventueel voorvoegsel dat hoort bij de achternaam die de persoon wil gebruiken
                           tijdens communicatie met de gemeente.</td>
                        <td width="10%">
                           Voorvoegsel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Achternaam
                           </td>
                        <td width="50%">Een achternaam die de persoon wil gebruiken tijdens communicatie met de gemeente.</td>
                        <td width="10%">
                           Omschrijving-lang
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                  </tbody>
               </table>
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht relaties</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Relatienaam met kardinaliteiten</i></td>
                        <td><i>Definitie</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Persoon
                           is specialisatie van
                           
                           Partij
                           
                           </td>
                        <td width="50%">Persoon of organisatie waarmee de gemeente een relatie heeft.</td>
                     </tr>
                  </tbody>
               </table>
               
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Toelichting</b></td>
                     </tr>
                  </tbody>
               </table>
               <table>
                  <tbody>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="95%">Kan zowel een ingeschreven, niet ingeschreven alsook een natuurlijk persoon zijn waarvan
                           niet bekend is of die ingeschreven is of niet.</td>
                     </tr>
                  </tbody>
               </table>
               </div>
            
            <div><a class="anchor" name="global_class_Model_AnderObject"></a><h2> Ander Object</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Ander Object</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Object, geregistreerd in een ander register</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Indicatie abstract object</b></td>
                        <td width="70%">Nee</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           ID
                           </td>
                        <td width="50%">Unieke identificatie van het Ander Object</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                  </tbody>
               </table>
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht relaties</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Relatienaam met kardinaliteiten</i></td>
                        <td><i>Definitie</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           
                           Onderwerpobject
                           
                           [ 0 .. * ]
                           
                           was
                           
                           Ander Object
                           [ 0 .. 1 ]
                           </td>
                        <td width="50%">Ander object dat een onderwerpobject was.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           
                           Inhoudsobject
                           
                           [ 0 .. 1 ]
                           
                           was
                           
                           Ander Object
                           [ 0 .. 1 ]
                           </td>
                        <td width="50%">Ander object dat een inhoudsobject was.</td>
                     </tr>
                  </tbody>
               </table>
               
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Toelichting</b></td>
                     </tr>
                  </tbody>
               </table>
               <table>
                  <tbody>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="95%">Dit kan ieder object zijn dat we bij het maken van dit model niet in beeld hebben.
                           Deze constructie stelt providers in staat om bijvoorbeeld productverzoeken of ander
                           digitale objecten als onderwerp te koppelen. </td>
                     </tr>
                  </tbody>
               </table>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Digitaaladres"></a><h2> Digitaal adres</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Digitaal adres</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Niet aan een specifieke fysieke locatie verbonden contactgegevens van een persoon
                           of organisatie.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%">ID</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Indicatie abstract object</b></td>
                        <td width="70%">Nee</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           ID
                           </td>
                        <td width="50%">Unieke (technische) identificatiecode van het digitaal adres.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Soort digitaal adres
                           </td>
                        <td width="50%">Typering van het digitale adres die aangeeft via welk(e) kanaal of kanalen met dit
                           adres contact kan worden opgenomen.</td>
                        <td width="10%">
                           Soort digitaal adres
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Adres
                           </td>
                        <td width="50%">Digitaal adres waarmee een persoon of organisatie bereikt kan worden.</td>
                        <td width="10%">
                           Adresregel
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Omschrijving
                           </td>
                        <td width="50%">Omschrijving van het digitaal adres.</td>
                        <td width="10%">
                           Omschrijving-kort
                           </td>
                        <td width="10%">1</td>
                     </tr>
                  </tbody>
               </table>
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht relaties</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Relatienaam met kardinaliteiten</i></td>
                        <td><i>Definitie</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           
                           Betrokkene bij klantcontact
                           
                           [ 0 .. 1 ]
                           
                           verstrekte voor opvolging van klantcontact
                           
                           Digitaal adres
                           [ 0 .. * ]
                           </td>
                        <td width="50%">Digitaal adres dat een betrokkene bij klantcontact verstrekte voor gebruik bij opvolging
                           van een klantcontact.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           
                           Partij
                           
                           [ 0 .. 1 ]
                           
                           verstrekte voor toekomstig contact
                           
                           Digitaal adres
                           [ 0 .. * ]
                           </td>
                        <td width="50%">Digitaal adres dat een partij verstrekte voor gebruik bij toekomstig contact met de
                           gemeente.</td>
                     </tr>
                  </tbody>
               </table>
               
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Toelichting</b></td>
                     </tr>
                  </tbody>
               </table>
               <table>
                  <tbody>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="95%">Digitaal adres duidt gegevens aan die beschrijven hoe een persoon of organisatie via
                           een digitaal kanaal bereikt kan worden. Voorbeelden hiervan zijn een telefoonnummer,
                           een e-mailadres of een gebruikersnaam op een sociaal medium. Adressen die gekoppeld
                           kunnen worden aan een vaste plaats in de fysieke wereld, zoals een bezoekadres, postbus
                           of antwoordnummer zijn geen digitaal adres.</td>
                     </tr>
                  </tbody>
               </table>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Medewerker"></a><h2> Medewerker</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Medewerker</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">RGBZ</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Een MEDEWERKER van de organisatie die zaken behandelt uit hoofde van zijn of haar
                           functie binnen een ORGANISATORISCHE EENHEID.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">RGBZ</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Indicatie abstract object</b></td>
                        <td width="70%">Nee</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Functie
                           </td>
                        <td width="50%">De aanduiding van de taken, rechten en plichten die de MEDEWERKER heeft of heeft gehad
                           binnen de zaakbehandelende organisatie.</td>
                        <td width="10%">
                           Omschrijving-kort
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           E-mailadres
                           </td>
                        <td width="50%">Elektronisch postadres waaronder de MEDEWERKER in de regel bereikbaar is.</td>
                        <td width="10%">
                           E-mailadres
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Telefoonnummer
                           </td>
                        <td width="50%">Telefoonnummer waaronder de MEDEWERKER in de regel bereikbaar is.</td>
                        <td width="10%">
                           Telefoonnummer
                           </td>
                        <td width="10%">1</td>
                     </tr>
                  </tbody>
               </table>
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht relaties</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Relatienaam met kardinaliteiten</i></td>
                        <td><i>Definitie</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Medewerker
                           is specialisatie van
                           
                           Actor
                           
                           </td>
                        <td width="50%">Iets dat of iemand die voor de gemeente werkzaamheden uitvoert.</td>
                     </tr>
                  </tbody>
               </table>
               
               
               </div>
            
            <div><a class="anchor" name="global_class_Model_Geautomatiseerdeactor"></a><h2> Geautomatiseerde actor</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Geautomatiseerde actor</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Systeemcomponent dat voor de gemeente werkzaamheden uitvoert. </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Indicatie abstract object</b></td>
                        <td width="70%">Nee</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Functie
                           </td>
                        <td width="50%">Functie van de geautomatiseerde actor of beschrijving van de werkzaamheden die deze
                           uitvoert.</td>
                        <td width="10%">
                           Omschrijving-kort
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Omschrijving
                           </td>
                        <td width="50%">Omschrijving van de geautomatiseerde actor.</td>
                        <td width="10%">
                           Omschrijving-lang
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                  </tbody>
               </table>
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht relaties</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Relatienaam met kardinaliteiten</i></td>
                        <td><i>Definitie</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Geautomatiseerde actor
                           is specialisatie van
                           
                           Actor
                           
                           </td>
                        <td width="50%">Iets dat of iemand die voor de gemeente werkzaamheden uitvoert.</td>
                     </tr>
                  </tbody>
               </table>
               
               
               </div>
            
            <div><a class="anchor" name="global_class_Model_Informatieobject"></a><h2> Informatieobject</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Informatieobject</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">RGBZ</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Geheel van gegevens met een eigen identiteit ongeacht zijn vorm, met de bijbehorende
                           metadata ontvangen of opgemaakt door een natuurlijke en/of rechtspersoon bij de uitvoering
                           van taken, zijnde een ENKELVOUDIG INFORMATIEOBJECT of een SAMENGESTELD INFORMATIEOBJECT.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">RGBZ</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%">Informatieobjectidentificatie</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Indicatie abstract object</b></td>
                        <td width="70%">Nee</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Informatieobjectidentificatie
                           </td>
                        <td width="50%">Een binnen een gegeven context ondubbelzinnige referentie naar het INFORMATIEOBJECT.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                  </tbody>
               </table>
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht relaties</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Relatienaam met kardinaliteiten</i></td>
                        <td><i>Definitie</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           
                           Inhoudsobject
                           
                           [ 0 .. 1 ]
                           
                           was
                           
                           Informatieobject
                           [ 0 .. 1 ]
                           </td>
                        <td width="50%">Informatieobject dat een inhoudsobject was.</td>
                     </tr>
                  </tbody>
               </table>
               
               
               </div>
            
            <div><a class="anchor" name="global_class_Model_Actor"></a><h2> Actor</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Actor</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Iets dat of iemand die voor de gemeente werkzaamheden uitvoert.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%">ID</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Indicatie abstract object</b></td>
                        <td width="70%">Ja</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           ID
                           </td>
                        <td width="50%">Unieke (technische) identificatiecode van de actor.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Naam
                           </td>
                        <td width="50%">Naam van de actor.</td>
                        <td width="10%">
                           Naam-lang
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Soort actor
                           </td>
                        <td width="50%">Geeft aan van welke specifieke soort actor sprake is.</td>
                        <td width="10%">
                           Soort actor
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Indicatie actief
                           </td>
                        <td width="50%">Geeft aan of aan de actor nog betrokken mag worden bij nieuwe klantcontacten. Voor
                           niet-actieve is dit niet toegestaan.</td>
                        <td width="10%">
                           Indicatie Ja Nee
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Actoridentifcator
                           :</td>
                        <td width="50%">Gegevens die een actor in een extern register uniek identificeren.</td>
                        <td width="10%">
                           Identificator
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Objecttype
                           </td>
                        <td width="50%">Type van het object.</td>
                        <td width="10%">
                           Soort object
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Soort Object ID
                           </td>
                        <td width="50%">Naam van de eigenschap die het object identificeert.</td>
                        <td width="10%">
                           Soort object
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Object ID
                           </td>
                        <td width="50%">Waarde van de eigenschap die het object identificeert.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Register
                           </td>
                        <td width="50%">Binnen het landschap van registers unieke omschrijving van het register waarin het
                           object is geregistreerd.</td>
                        <td width="10%">
                           Extern register
                           </td>
                        <td width="10%">1</td>
                     </tr>
                  </tbody>
               </table>
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht relaties</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Relatienaam met kardinaliteiten</i></td>
                        <td><i>Definitie</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           
                           Klantcontact
                           
                           [ 0 .. * ]
                           
                           had betrokken
                           
                           Actor
                           [ 1 .. * ]
                           </td>
                        <td width="50%">Actor die bij een klantcontact betrokken was.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           
                           Interne taak
                           
                           [ 0 .. * ]
                           
                           werd toegewezen aan
                           
                           Actor
                           [ 1 ]
                           </td>
                        <td width="50%">Actor die een interne taak toegewezen kreeg.</td>
                     </tr>
                  </tbody>
               </table>
               
               
               </div>
            
            <div><a class="anchor" name="global_class_Model_Organisatorischeeenheid"></a><h2> Organisatorische eenheid</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Organisatorische eenheid</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">RGBZ</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Het deel van een functioneel afgebakend onderdeel binnen de organisatie dat haar activiteiten
                           uitvoert binnen een VESTIGING VAN ZAAKBEHANDELENDE ORGANISATIE en die verantwoordelijk
                           is voor de behandeling van zaken.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">RGBZ</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Indicatie abstract object</b></td>
                        <td width="70%">Nee</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Omschrijving
                           </td>
                        <td width="50%">Een omschrijving van de organisatorische eenheid.</td>
                        <td width="10%">
                           Omschrijving-lang
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           E-mailadres
                           </td>
                        <td width="50%">Elektronisch postadres waaronder de organisatorische eenheid in de regel bereikbaar
                           is. </td>
                        <td width="10%">
                           E-mailadres
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Faxnummer
                           </td>
                        <td width="50%">Faxnummer waaronder de organisatorische eenheid in de regel bereikbaar is.</td>
                        <td width="10%">
                           Telefoonnummer
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Telefoonnummer
                           </td>
                        <td width="50%">Telefoonnummer waaronder de organisatorische eenheid in de regel bereikbaar is.</td>
                        <td width="10%">
                           Telefoonnummer
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                  </tbody>
               </table>
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht relaties</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Relatienaam met kardinaliteiten</i></td>
                        <td><i>Definitie</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Organisatorische eenheid
                           is specialisatie van
                           
                           Actor
                           
                           </td>
                        <td width="50%">Iets dat of iemand die voor de gemeente werkzaamheden uitvoert.</td>
                     </tr>
                  </tbody>
               </table>
               
               
               </div>
            
            <div><a class="anchor" name="global_class_Model_Internetaak"></a><h2> Interne taak</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Interne taak</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Iets dat door een actor moet worden gedaan om opvolging te geven aan een klantcontact.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%">ID</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Indicatie abstract object</b></td>
                        <td width="70%">Nee</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           ID
                           </td>
                        <td width="50%">Unieke (technische) identificatiecode van de interne taak.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Nummer
                           </td>
                        <td width="50%">Uniek identificerend nummer dat tijdens communicatie tussen mensen kan worden gebruikt
                           om de specifieke interne taak aan te duiden.</td>
                        <td width="10%">
                           Identificerend nummer
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Gevraagde handeling
                           </td>
                        <td width="50%">Handeling die moet worden uitgevoerd om de taak af te ronden.</td>
                        <td width="10%">
                           Omschrijving-lang
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Toelichting
                           </td>
                        <td width="50%">Toelichting die, aanvullend bij de inhoud van het klantcontact dat aanleiding gaf
                           tot de taak en de gevraagde handeling, bijdraagt aan het kunnen afhandelen van de
                           taak.</td>
                        <td width="10%">
                           Toelichting
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Status
                           </td>
                        <td width="50%">Aanduiding van de vordering bij afhandeling van de interne taak.</td>
                        <td width="10%">
                           Taakstatus
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Toegewezen op
                           </td>
                        <td width="50%">Datum en tijdstip waarop de interne taak aan een actor werd toegewezen.</td>
                        <td width="10%">
                           Datumtijd
                           </td>
                        <td width="10%">1</td>
                     </tr>
                  </tbody>
               </table>
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht relaties</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Relatienaam met kardinaliteiten</i></td>
                        <td><i>Definitie</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Interne taak
                           [ 0 .. * ]
                           
                           werd toegewezen aan
                           
                           
                           Actor
                           
                           [ 1 ]
                           </td>
                        <td width="50%">Actor die een interne taak toegewezen kreeg.</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           Interne taak
                           [ 0 .. * ]
                           
                           ontstond naar aanleiding van
                           
                           
                           Klantcontact
                           
                           [ 1 ]
                           </td>
                        <td width="50%">Klantcontact dat leidde tot een interne taak.</td>
                     </tr>
                  </tbody>
               </table>
               
               
               </div>
            
            <div><a class="anchor" name="global_class_Model_Klanttaak"></a><h2> Klanttaak</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Klanttaak</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">VNG</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Iets dat door een bij een zaak betrokken partij moet worden gedaan.<br><br>De noodzaak om een klanttaak te kunnen registreren is tijdens ontwikkeling van klantinteracties
                           onderkend. Qua karakter en eigenschappen hoort de klanttaak binnen het domein van
                           zaakgericht werken en is Klantinteracties dus niet het 'thuisdomein' van dit object.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">VNG</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%">ID</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Indicatie abstract object</b></td>
                        <td width="70%">Nee</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           ID
                           </td>
                        <td width="50%">Unieke identificatiecode van de klanttaak.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Nummer
                           </td>
                        <td width="50%">Uniek identificerend nummer waarmee tijdens communicatie tussen mensen verwezen kan
                           worden naar de klanttaak.</td>
                        <td width="10%">
                           Identificerend nummer
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Gevraagde handeling
                           </td>
                        <td width="50%">Op de klant gerichte uitleg van de activiteit die de gemeente vraag aan de klant om
                           uit te voeren. </td>
                        <td width="10%">
                           Omschrijving-lang
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Toelichting
                           </td>
                        <td width="50%">Toelichtende tekst op de aan de klant gevraagde uit te voeren handeling. </td>
                        <td width="10%">
                           Toelichting
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Status
                           </td>
                        <td width="50%">De indicatie of de klantaak is uitgevoerd.</td>
                        <td width="10%">
                           Taakstatus
                           </td>
                        <td width="10%">1</td>
                     </tr>
                  </tbody>
               </table>
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht relaties</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Relatienaam met kardinaliteiten</i></td>
                        <td><i>Definitie</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           
                           Onderwerpobject
                           
                           [ 0 .. * ]
                           
                           was
                           
                           Klanttaak
                           [ 0 .. 1 ]
                           </td>
                        <td width="50%">Klanttaak die een onderwerpobject was.</td>
                     </tr>
                  </tbody>
               </table>
               
               
               </div>
            
            <div><a class="anchor" name="global_class_Model_Zaak"></a><h2> Zaak</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Zaak</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">RGBZ</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Een samenhangende hoeveelheid werk met een welgedefinieerde aanleiding en een welgedefinieerd
                           eindresultaat, waarvan kwaliteit en doorlooptijd bewaakt moeten worden. </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">RGBZ</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%">Zaakidentificatie</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Indicatie abstract object</b></td>
                        <td width="70%">Nee</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Zaakidentificatie
                           </td>
                        <td width="50%">De unieke identificatie van de ZAAK binnen de organisatie die verantwoordelijk is
                           voor de behandeling van de ZAAK.</td>
                        <td width="10%">
                           CharacterString
                           </td>
                        <td width="10%">1</td>
                     </tr>
                  </tbody>
               </table>
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht relaties</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Relatienaam met kardinaliteiten</i></td>
                        <td><i>Definitie</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           
                           Onderwerpobject
                           
                           [ 0 .. * ]
                           
                           was
                           
                           Zaak
                           [ 0 .. 1 ]
                           </td>
                        <td width="50%">Zaak die een onderwerpobject was.</td>
                     </tr>
                  </tbody>
               </table>
               
               
               </div>
            
            <div><a class="anchor" name="global_class_Model_Partijidentificator"></a><h2> Partij-identificator</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Partij-identificator</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Gegevens die een partij in een basisregistratie of ander extern register uniek identificeren.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%">ID</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Indicatie abstract object</b></td>
                        <td width="70%">Nee</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           ID
                           </td>
                        <td width="50%">Unieke (technische) identificatiecode van de externe identificatie</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Andere partij-identificator
                           </td>
                        <td width="50%">Vrij tekstveld om de verwijzing naar een niet-voorgedefinieerd objecttype, soort objectID
                           of Register vast te leggen. </td>
                        <td width="10%">
                           Omschrijving-lang
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">
                           Partij-identificator
                           :</td>
                        <td width="50%">Gegevens die een partij in een basisregistratie of ander extern register uniek identificeren.</td>
                        <td width="10%">
                           Identificator
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Objecttype
                           </td>
                        <td width="50%">Type van het object.</td>
                        <td width="10%">
                           Soort object
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Soort Object ID
                           </td>
                        <td width="50%">Naam van de eigenschap die het object identificeert.</td>
                        <td width="10%">
                           Soort object
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Object ID
                           </td>
                        <td width="50%">Waarde van de eigenschap die het object identificeert.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Register
                           </td>
                        <td width="50%">Binnen het landschap van registers unieke omschrijving van het register waarin het
                           object is geregistreerd.</td>
                        <td width="10%">
                           Extern register
                           </td>
                        <td width="10%">1</td>
                     </tr>
                  </tbody>
               </table>
               
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht relaties</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Relatienaam met kardinaliteiten</i></td>
                        <td><i>Definitie</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="45%">
                           
                           Partij
                           
                           [ 0 .. 1 ]
                           
                           had
                           
                           Partij-identificator
                           [ 1 .. * ]
                           </td>
                        <td width="50%">Partij-identificator die een partij had.</td>
                     </tr>
                  </tbody>
               </table>
               
               
               </div>
            </div>
         <div>
            <h1>Referentielijsten </h1>
            
            <div><a class="anchor" name="global_class_Model_Taal"></a><h2>Referentielijst Taal</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Taal</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">GBA</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Een lijst van talen die personen en organisaties kunnen gebruiken bij contact met
                           de gemeente en vice versa.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Data locatie</b></td>
                        <td width="70%"><br>                        http://publicaties.rvig.nl/Landelijke_tabellen<br>                     </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%">Code</td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht referentie elementen </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Referentie element</i></td>
                           <td><i>Definitie</i></td>
                           <td><i>Formaat</i></td>
                           <td><i>Card</i></td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Code
                              </td>
                           <td width="50%">De code, behorende bij de voorkeurstaal.</td>
                           <td width="10%">
                              CharacterString
                              </td>
                           <td width="10%">1</td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Naam
                              </td>
                           <td width="50%">De naam van de voorkeurstaal.</td>
                           <td width="10%">
                              CharacterString
                              </td>
                           <td width="10%">1</td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Indicatie actief
                              </td>
                           <td width="50%">Indicatie of de betreffende voorkeurstaal nog gebruikt mag worden. </td>
                           <td width="10%">
                              Indicatie Ja Nee
                              </td>
                           <td width="10%">1</td>
                        </tr>
                     </tbody>
                  </table>
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Land"></a><h2>Referentielijst Land</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Land</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">GBA</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Een lijst van alle huidige en voormalige landen met hun codes, namen en geldigheidstermijnen.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">1 november 2008</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Data locatie</b></td>
                        <td width="70%"><br>                        http://publicaties.rvig.nl/Landelijke_tabellen<br>                     </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%">Landcode</td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht referentie elementen </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Referentie element</i></td>
                           <td><i>Definitie</i></td>
                           <td><i>Formaat</i></td>
                           <td><i>Card</i></td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Landcode
                              </td>
                           <td width="50%">De code, behorende bij de landnaam, opgenomen in de Landentabel van de GBA.</td>
                           <td width="10%">
                              CharacterString
                              </td>
                           <td width="10%">1</td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Landnaam
                              </td>
                           <td width="50%">De naam van het land, zoals opgenomen in de Landentabel van de GBA.</td>
                           <td width="10%">
                              CharacterString
                              </td>
                           <td width="10%">1</td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Ingangsdatum land
                              </td>
                           <td width="50%">De datum waarop het land/gebied is ontstaan.</td>
                           <td width="10%">
                              Datum
                              </td>
                           <td width="10%">1</td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Einddatum land
                              </td>
                           <td width="50%">De datum waarop het land/gebied is opgeheven.</td>
                           <td width="10%">
                              Datum
                              </td>
                           <td width="10%">1</td>
                        </tr>
                     </tbody>
                  </table>
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Kanaal"></a><h2>Referentielijst Kanaal</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Kanaal</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Een lijst van kanalen die personen en organisaties kunnen gebruiken voor contact met
                           de gemeente en vice versa.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Data locatie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%">Code</td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht referentie elementen </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Referentie element</i></td>
                           <td><i>Definitie</i></td>
                           <td><i>Formaat</i></td>
                           <td><i>Card</i></td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Code
                              </td>
                           <td width="50%">De code, behorende bij het kanaal.</td>
                           <td width="10%">
                              CharacterString
                              </td>
                           <td width="10%">1</td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Naam
                              </td>
                           <td width="50%">De naam van het kanaal.</td>
                           <td width="10%">
                              CharacterString
                              </td>
                           <td width="10%">1</td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Indicatie actief
                              </td>
                           <td width="50%">Indicatie of het betreffende kanaal nog gebruikt mag worden. </td>
                           <td width="10%">
                              Indicatie Ja Nee
                              </td>
                           <td width="10%">1</td>
                        </tr>
                     </tbody>
                  </table>
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Soortobject"></a><h2>Referentielijst Soort object</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Soort object</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Een lijst van typen objecten waarnaar vanuit het klantinteractiesregister relaties
                           kunnen worden gelegd.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">08-07-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Data locatie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%">Code</td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht referentie elementen </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Referentie element</i></td>
                           <td><i>Definitie</i></td>
                           <td><i>Formaat</i></td>
                           <td><i>Card</i></td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Code
                              </td>
                           <td width="50%">De code, behorende bij het soort object.</td>
                           <td width="10%">
                              CharacterString
                              </td>
                           <td width="10%">1</td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Naam
                              </td>
                           <td width="50%">De naam van het soort object.</td>
                           <td width="10%">
                              CharacterString
                              </td>
                           <td width="10%">1</td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Indicatie actief
                              </td>
                           <td width="50%">Indicatie of het betreffende soort object nog gebruikt mag worden. </td>
                           <td width="10%">
                              Indicatie Ja Nee
                              </td>
                           <td width="10%">1</td>
                        </tr>
                     </tbody>
                  </table>
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Externregister"></a><h2>Referentielijst Extern register</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Extern register</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Een lijst van registers buiten het domein van klantinteracties waarin objecten zijn
                           geregistreerd die gerelateerd zijn met objecen in het klantinteractiesdomein.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">08-07-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Data locatie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%">Code</td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht referentie elementen </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Referentie element</i></td>
                           <td><i>Definitie</i></td>
                           <td><i>Formaat</i></td>
                           <td><i>Card</i></td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Code
                              </td>
                           <td width="50%">De code, behorende bij het soort extern id.</td>
                           <td width="10%">
                              Identificatiecode
                              </td>
                           <td width="10%">1</td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Naam
                              </td>
                           <td width="50%">De naam van het soort extern id.</td>
                           <td width="10%">
                              Naam-kort
                              </td>
                           <td width="10%">1</td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Locatie
                              </td>
                           <td width="50%">Indicatie die aangeeft of het soort extern ID nog actief is en toegekend mag worden
                              aan een etern ID van een Partij. </td>
                           <td width="10%">
                              Omschrijving-kort
                              </td>
                           <td width="10%">1</td>
                        </tr>
                     </tbody>
                  </table>
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Soortdigitaaladres"></a><h2>Referentielijst Soort digitaal adres</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Soort digitaal adres</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Een lijst van soorten digitale adressen die personen en organisaties kunnen gebruiken
                           voor contact met de gemeente en vice versa.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Data locatie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%">Code</td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht referentie elementen </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Referentie element</i></td>
                           <td><i>Definitie</i></td>
                           <td><i>Formaat</i></td>
                           <td><i>Card</i></td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Code
                              </td>
                           <td width="50%">De code, behorende bij het soort digitaal adres.</td>
                           <td width="10%">
                              CharacterString
                              </td>
                           <td width="10%">1</td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Naam
                              </td>
                           <td width="50%">De naam van het soort digitaal adres.</td>
                           <td width="10%">
                              CharacterString
                              </td>
                           <td width="10%">1</td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Indicatie actief
                              </td>
                           <td width="50%">Indicatie of het betreffende digitale adres nog gebruikt mag worden. </td>
                           <td width="10%">
                              Indicatie Ja Nee
                              </td>
                           <td width="10%">1</td>
                        </tr>
                     </tbody>
                  </table>
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_SoortobjectID"></a><h2>Referentielijst Soort object ID</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Soort object ID</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Een lijst van identificatiesystemen en de (bron)registers die de authentieke vindplaats
                           vormen van volgens deze systemen geregistreerde gegevens.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">08-07-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Data locatie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Unieke aanduiding</b></td>
                        <td width="70%">Code</td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht referentie elementen </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Referentie element</i></td>
                           <td><i>Definitie</i></td>
                           <td><i>Formaat</i></td>
                           <td><i>Card</i></td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Code
                              </td>
                           <td width="50%">De code, behorende bij het soort extern id.</td>
                           <td width="10%">
                              CharacterString
                              </td>
                           <td width="10%">1</td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Extern register
                              </td>
                           <td width="50%">Het register dat geraadpleegd kan worden m.b.v. de externe identificatiecode. </td>
                           <td width="10%">
                              Extern register
                              </td>
                           <td width="10%">1</td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Naam
                              </td>
                           <td width="50%">De naam van het soort extern id.</td>
                           <td width="10%">
                              CharacterString
                              </td>
                           <td width="10%">1</td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Indicatie actief
                              </td>
                           <td width="50%">Indicatie die aangeeft of het soort extern ID nog actief is en toegekend mag worden
                              aan een etern ID van een Partij. </td>
                           <td width="10%">
                              Indicatie Ja Nee
                              </td>
                           <td width="10%">1</td>
                        </tr>
                        <tr>
                           <td width="5%">&nbsp;</td>
                           <td width="25%">
                              Soort partij
                              </td>
                           <td width="50%">Indicatie voor welk soort partij dit soort extern ID toepasbaar is. </td>
                           <td width="10%">
                              Soort partij
                              </td>
                           <td width="10%">1</td>
                        </tr>
                     </tbody>
                  </table>
                  </div>
               </div>
            </div>
         <div>
            <h1>Gegevensgroeptypen </h1>
            
            <div><a class="anchor" name="global_class_Model_Identificator"></a><h2>Gegevensgroep Identificator</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Identificator</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Gegevens die een object in een extern register uniek identificeren.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">10-10-2023</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Objecttype
                           </td>
                        <td width="50%">Type van het object.</td>
                        <td width="10%">
                           Soort object
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Soort Object ID
                           </td>
                        <td width="50%">Naam van de eigenschap die het object identificeert.</td>
                        <td width="10%">
                           Soort object
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Object ID
                           </td>
                        <td width="50%">Waarde van de eigenschap die het object identificeert.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Register
                           </td>
                        <td width="50%">Binnen het landschap van registers unieke omschrijving van het register waarin het
                           object is geregistreerd.</td>
                        <td width="10%">
                           Extern register
                           </td>
                        <td width="10%">1</td>
                     </tr>
                  </tbody>
               </table>
               
               </div>
            
            <div><a class="anchor" name="global_class_Model_Bezoekadres"></a><h2>Gegevensgroep Bezoekadres</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Bezoekadres</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Het adres waar een persoon of een organisatie bezoekers ontvangt.<br><br>Het bezoekadres is weliswaar geen BRP-object, maar voor de definitie van adres-componenten
                           </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           NummeraanduidingID
                           </td>
                        <td width="50%">Identificatie van het adres bij de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Adresregel 1
                           </td>
                        <td width="50%">Eerste deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Adresregel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Adresregel 2
                           </td>
                        <td width="50%">Tweede deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Adresregel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Adresregel 3
                           </td>
                        <td width="50%">Derde deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Adresregel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Land
                           </td>
                        <td width="50%">Een code, opgenomen in Tabel 34, Landentabel, die het land (buiten Nederland) aangeeft
                           alwaar de ingeschrevene verblijft. </td>
                        <td width="10%">
                           Land
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                  </tbody>
               </table>
               
               </div>
            
            <div><a class="anchor" name="global_class_Model_Contactnaam"></a><h2>Gegevensgroep Contactnaam</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Contactnaam</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">De naam die de persoon opgaf voor gebruik bij contact met de gemeente.  </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Voorletters
                           </td>
                        <td width="50%">Een afkorting van de voornamen. Meestal de beginletter, maar in sommige gevallen de
                           beginletter gecombineerd met de tweede letter van een voornaam.</td>
                        <td width="10%">
                           Voorletters
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Voornaam
                           </td>
                        <td width="50%">De voornaam die de persoon wil gebruiken tijdens communicatie met de gemeente.</td>
                        <td width="10%">
                           Naam-kort
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Voorvoegsel achternaam
                           </td>
                        <td width="50%">Een eventueel voorvoegsel dat hoort bij de achternaam die de persoon wil gebruiken
                           tijdens communicatie met de gemeente.</td>
                        <td width="10%">
                           Voorvoegsel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Achternaam
                           </td>
                        <td width="50%">Een achternaam die de persoon wil gebruiken tijdens communicatie met de gemeente.</td>
                        <td width="10%">
                           Omschrijving-lang
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                  </tbody>
               </table>
               
               </div>
            
            <div><a class="anchor" name="global_class_Model_Correspondentieadres"></a><h2>Gegevensgroep Correspondentieadres</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Correspondentieadres</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Het adres waarnaar de persoon of de organisatie de voor hen bestemde correspondentie
                           laat verzenden. </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Overzicht attributen</b></td>
                     </tr>
                  </tbody>
               </table>
               
               <table>
                  <tbody>
                     <tr>
                        <td><i></i></td>
                        <td><i>Attribuutnaam</i></td>
                        <td><i>Definitie</i></td>
                        <td><i>Formaat</i></td>
                        <td><i>Card</i></td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           NummeraanduidingID
                           </td>
                        <td width="50%">Identificatie van het adres bij de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Identificatiecode
                           </td>
                        <td width="10%">1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Adresregel 1
                           </td>
                        <td width="50%">Eerste deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Adresregel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Adresregel 2
                           </td>
                        <td width="50%">Tweede deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Adresregel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Adresregel 3
                           </td>
                        <td width="50%">Derde van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                        <td width="10%">
                           Adresregel
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                     <tr>
                        <td width="5%">&nbsp;</td>
                        <td width="25%">- 
                           Land
                           </td>
                        <td width="50%">Een code, opgenomen in Tabel 34, Landentabel, die het land (buiten Nederland) aangeeft
                           alwaar de ingeschrevene verblijft. </td>
                        <td width="10%">
                           Land
                           </td>
                        <td width="10%">0 .. 1</td>
                     </tr>
                  </tbody>
               </table>
               
               </div>
            </div>
         <div>
            <h1>Primitieve datatypen </h1>
            
            <div><a class="anchor" name="global_class_Model_Omschrijvinglang"></a><h2>Primitief datatype Omschrijving-lang</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Omschrijving-lang</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">VNG</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">200</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Omschrijving-lang
                                 is specialisatie van
                                 
                                 CharacterString
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Huisletter"></a><h2>Primitief datatype Huisletter</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Huisletter</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">GBA</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">1</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Huisletter
                                 is specialisatie van
                                 
                                 CharacterString
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Antwoordnummer"></a><h2>Primitief datatype Antwoordnummer</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Antwoordnummer</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">VNG</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">5</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Antwoordnummer
                                 is specialisatie van
                                 
                                 Integer
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Postcode"></a><h2>Primitief datatype Postcode</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Postcode</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">GBA</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">7</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Postcode
                                 is specialisatie van
                                 
                                 CharacterString
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Tekst"></a><h2>Primitief datatype Tekst</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Tekst</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">04-10-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">1000</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Tekst
                                 is specialisatie van
                                 
                                 CharacterString
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Omschrijvingkort"></a><h2>Primitief datatype Omschrijving-kort</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Omschrijving-kort</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">VNG</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">40</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Omschrijving-kort
                                 is specialisatie van
                                 
                                 CharacterString
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Datumtijd"></a><h2>Primitief datatype Datumtijd</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Datumtijd</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">VNG</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">20230216</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Datumtijd
                                 is specialisatie van
                                 
                                 DateTime
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Postbusnummer"></a><h2>Primitief datatype Postbusnummer</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Postbusnummer</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">VNG</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">5</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Postbusnummer
                                 is specialisatie van
                                 
                                 Integer
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Voorvoegsel"></a><h2>Primitief datatype Voorvoegsel</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Voorvoegsel</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">GBA</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">10</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Voorvoegsel
                                 is specialisatie van
                                 
                                 CharacterString
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Adresregel"></a><h2>Primitief datatype Adresregel</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Adresregel</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">VNG</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Een generieke regel om adresgegevens in op te nemen.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">80</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Adresregel
                                 is specialisatie van
                                 
                                 CharacterString
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Straat"></a><h2>Primitief datatype Straat</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Straat</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">VNG</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">80</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Straat
                                 is specialisatie van
                                 
                                 CharacterString
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Telefoonnummer"></a><h2>Primitief datatype Telefoonnummer</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Telefoonnummer</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">GBA</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">20</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Telefoonnummer
                                 is specialisatie van
                                 
                                 CharacterString
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Huisnummer"></a><h2>Primitief datatype Huisnummer</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Huisnummer</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">GBA</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">5</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Huisnummer
                                 is specialisatie van
                                 
                                 Integer
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Emailadres"></a><h2>Primitief datatype E-mailadres</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">E-mailadres</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">VNG</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Een geldig email-adres, maximaal 20 karakters lang en minimaal een @ en een . opgenomen.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">200</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 E-mailadres
                                 is specialisatie van
                                 
                                 CharacterString
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Partijnummer"></a><h2>Primitief datatype Partijnummer</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Partijnummer</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">VNG</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">10</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Partijnummer
                                 is specialisatie van
                                 
                                 Integer
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_AantalJaar"></a><h2>Primitief datatype Aantal Jaar</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Aantal Jaar</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">VNG</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">Groter of gelijk aan nul.</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Aantal Jaar
                                 is specialisatie van
                                 
                                 Integer
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Voorletters"></a><h2>Primitief datatype Voorletters</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Voorletters</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">Klantinteracties</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">10-10-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">10</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Identificerendnummer"></a><h2>Primitief datatype Identificerend nummer</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Identificerend nummer</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">VNG</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">10</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Identificerend nummer
                                 is specialisatie van
                                 
                                 Integer
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Toelichting"></a><h2>Primitief datatype Toelichting</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Toelichting</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">VNG</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Toelichtende tekst</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">400</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Toelichting
                                 is specialisatie van
                                 
                                 CharacterString
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Huisnummertoevoeging"></a><h2>Primitief datatype Huisnummertoevoeging</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Huisnummertoevoeging</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">GBA</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">4</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Huisnummertoevoeging
                                 is specialisatie van
                                 
                                 CharacterString
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Woonplaats"></a><h2>Primitief datatype Woonplaats</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Woonplaats</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">GBA</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">80</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Woonplaats
                                 is specialisatie van
                                 
                                 CharacterString
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Naamkort"></a><h2>Primitief datatype Naam-kort</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Naam-kort</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">VNG</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">80</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Naam-kort
                                 is specialisatie van
                                 
                                 CharacterString
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Naamlang"></a><h2>Primitief datatype Naam-lang</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Naam-lang</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">VNG</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">200</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Naam-lang
                                 is specialisatie van
                                 
                                 CharacterString
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Identificatiecode"></a><h2>Primitief datatype Identificatiecode</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Identificatiecode</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">VNG</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-02-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%">40</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Identificatiecode
                                 is specialisatie van
                                 
                                 CharacterString
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_Datum"></a><h2>Primitief datatype Datum</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Datum</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">VNG</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%">Datum</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">16-03-2023</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Datum
                                 is specialisatie van
                                 
                                 Date
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            
            <div><a class="anchor" name="global_class_Model_IndicatieJaNee"></a><h2>Primitief datatype Indicatie Ja Nee</h2>
               
               <table>
                  <tbody>
                     <tr>
                        <td width="30%"><b>Naam</b></td>
                        <td width="70%">Indicatie Ja Nee</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst</b></td>
                        <td width="70%">VNG</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Herkomst definitie</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Datum opname</b></td>
                        <td width="70%">20230216</td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Lengte</b></td>
                        <td width="70%"> </td>
                     </tr>
                     <tr>
                        <td width="30%"><b>Patroon</b></td>
                        <td width="70%"> </td>
                     </tr>
                  </tbody>
               </table>
               
               <div>
                  <h3>Overzicht relaties </h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i></i></td>
                           <td><i>Supertype relaties</i></td>
                           <td><i>Supertype definitie</i></td>
                        </tr>
                        <tr>
                           <td width="30%"><b>
                                 Indicatie Ja Nee
                                 is specialisatie van
                                 
                                 Boolean
                                 
                                 </b></td>
                           <td width="70%"></td>
                        </tr>
                     </tbody>
                  </table>
                  
                  </div>
               </div>
            </div>
         <div>
            <h1>Enumeraties </h1>
            
            <table>
               <tbody>
                  <tr>
                     <td width="30%"><b><a class="anchor" name="global_class_Model_Initiator"></a>Initiator</b></td>
                     <td width="70%">De waarden van de partij die het contact heeft geinitieerd.</td>
                  </tr>
                  <tr>
                     <td width="30%"><b><a class="anchor" name="global_class_Model_Indicatiejaneeonbekend"></a>Indicatie ja nee onbekend</b></td>
                     <td width="70%">Deze enumeratie is toegevoegd omdat de ingevulde waarde geen boolean kan zijn (waar
                        of niet waar). De gewenste waarden zijn ja,nee of onbekend.  </td>
                  </tr>
                  <tr>
                     <td width="30%"><b><a class="anchor" name="global_class_Model_Taakstatus"></a>Taakstatus</b></td>
                     <td width="70%">De waarden van de typering van de voortgang van afhandeling van een VERZOEK.</td>
                  </tr>
                  <tr>
                     <td width="30%"><b><a class="anchor" name="global_class_Model_Soortbezoekadres"></a>Soort bezoekadres</b></td>
                     <td width="70%">Typering waarmee aangegeven of het bezoekadres een binnenlands - of een buitenlands
                        adres is. </td>
                  </tr>
                  <tr>
                     <td width="30%"><b><a class="anchor" name="global_class_Model_Aanduidingbijhuisnummer"></a>Aanduiding bij huisnummer</b></td>
                     <td width="70%">De aanduiding die gebruikt wordt voor bijvoorbeeld een ligplaats of een standplaats
                        die geen eigen nummeraanduiding heeft. </td>
                  </tr>
                  <tr>
                     <td width="30%"><b><a class="anchor" name="global_class_Model_Soortcorrespondentieadres"></a>Soort correspondentieadres</b></td>
                     <td width="70%">Typering waarmee aangegeven wordt of het correspondentieadres een binnenlands - of
                        een buitenlands adres is danwel een postbusnummer of een antwoordnummer. </td>
                  </tr>
                  <tr>
                     <td width="30%"><b><a class="anchor" name="global_class_Model_Soortactor"></a>Soort actor</b></td>
                     <td width="70%">De typering van de actor.   </td>
                  </tr>
                  <tr>
                     <td width="30%"><b><a class="anchor" name="global_class_Model_Soortinhoudsdeel"></a>Soort inhoudsdeel</b></td>
                     <td width="70%">De typering van het inhoudsdeel.   </td>
                  </tr>
                  <tr>
                     <td width="30%"><b><a class="anchor" name="global_class_Model_Soortpartij"></a>Soort partij</b></td>
                     <td width="70%">De typering van de partij.</td>
                  </tr>
                  <tr>
                     <td width="30%"><b><a class="anchor" name="global_class_Model_Klantcontactrol"></a>Klantcontactrol</b></td>
                     <td width="70%">De typering van de rol van de persoon of organisatie in het klantcontact.   </td>
                  </tr>
               </tbody>
            </table>
            </div>
         <div>
            <h1>Attribuut- en relatiesoort details </h1>
            
            <div>
               <h2>Objecttype details </h2>
               
               <div><a class="anchor" name="detail_class_Model_Klantcontact"></a><h3> Klantcontact</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Klantcontact_ID"></a><h4>Attribuutsoort details ID</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">ID</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Unieke (technische) identificatiecode van het klantcontact.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klentinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificatiecode
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Klantcontact_Nummer"></a><h4>Attribuutsoort details Nummer</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Nummer</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Uniek identificerend nummer dat tijdens communicatie tussen mensen kan worden gebruikt
                                 om het specifieke klantcontact aan te duiden.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificerend nummer
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Klantcontact_Kanaal"></a><h4>Attribuutsoort details Kanaal</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Kanaal</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Communicatiekanaal dat bij het klantcontact werd gebruikt.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Kanaal
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Klantcontact_Onderwerp"></a><h4>Attribuutsoort details Onderwerp</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Onderwerp</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Datgene waarover het klantcontact ging.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-06-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Omschrijving-lang
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Klantcontact_Inhoud"></a><h4>Attribuutsoort details Inhoud</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Inhoud</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Informatie die tijdens het klantcontact werd overgebracht of uitgewisseld, voor zover
                                 die voor betrokkenen of actoren relevant is.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Tekst
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Toelichting</b></td>
                           </tr>
                        </tbody>
                     </table>
                     <table>
                        <tbody>
                           <tr>
                              <td width="5%">&nbsp;</td>
                              <td width="95%"><br>                                 De inhoud van een klantcontact vormt zoveel mogelijk
                                 een feitelijke, 'onbehandelde' weergave van de informatie die tijdens een contact
                                 tussen inwoners of ondernemers en de gemeente kenbaar is gemaakt of uitgewisseld.
                                 Dit betekent niet dat altijd sprake is van een letterlijk verslag: het gaat erom die
                                 informatie vast te leggen die voor betrokken inwoners op een later moment relevant
                                 kan zijn.<br>                                 <br>                                 Als de inhoud van het klantcontact al duidelijk wordt
                                 uit de inhoud van een bijlage waarin bijvoorbeeld een gescande brief of in een elektronisch
                                 formulier ontvangen gegevens zijn opgenomen, blijft het attribuut 'inhoud' bij registratie
                                 van een klantcontact leeg.<br>                              </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Klantcontact_Initiator"></a><h4>Attribuutsoort details Initiator</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Initiator</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Degene die het klantcontact initieerde.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Initiator
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Klantcontact_Indicatiecontactgelukt"></a><h4>Attribuutsoort details Indicatie contact gelukt</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Indicatie contact gelukt</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Geeft, indien bekend, aan of de poging contact tussen de gemeente en inwoner(s) of
                                 organisatie(s) tot stand te brengen succesvol was.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Indicatie ja nee onbekend
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Klantcontact_Taal"></a><h4>Attribuutsoort details Taal</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Taal</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Taal die bij het klantcontact werd gesproken of geschreven.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Taal
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Klantcontact_Vertrouwelijk"></a><h4>Attribuutsoort details Vertrouwelijk</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Vertrouwelijk</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Geeft aan of onderwerp, inhoud en kenmerken van het klantcontact vertrouwelijk moeten
                                 worden behandeld.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Indicatie Ja Nee
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Klantcontact_Plaatsgevondenop"></a><h4>Attribuutsoort details Plaatsgevonden op</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Plaatsgevonden op</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Datum en tijdstip waarop het klantontact plaatsvond. Als het klantcontact een gesprek
                                 betrof, is dit het moment waarop het gesprek begon. Als het klantcontact verzending
                                 of ontvangst van informatie betrof, is dit bij benadering het moment waarop informatie
                                 door gemeente verzonden of ontvangen werd.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Datumtijd
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_association_Model_Klantcontact_hadbetrokken"></a><h4>Relatiesoort details had betrokken</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">had betrokken</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Gerelateerd objecttype</b></td>
                              <td width="70%">
                                 Actor
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Actor die bij een klantcontact betrokken was.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1 .. *</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     
                     </div>
                  
                  <div><a class="anchor" name="detail_association_Model_Klantcontact_had"></a><h4>Relatiesoort details had</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">had</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Gerelateerd objecttype</b></td>
                              <td width="70%">
                                 Betrokkene bij klantcontact
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Persoon of organisatie die betrokken was bij een klantcontact.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. *</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     
                     </div>
                  
                  <div><a class="anchor" name="detail_association_Model_Klantcontact_gingover"></a><h4>Relatiesoort details ging over</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">ging over</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Gerelateerd objecttype</b></td>
                              <td width="70%">
                                 Onderwerpobject
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Onderwerpobject dat tijdens een klantcontact aan de orde kwam.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-07-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. *</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     
                     </div>
                  
                  <div><a class="anchor" name="detail_association_Model_Klantcontact_omvatte"></a><h4>Relatiesoort details omvatte</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">omvatte</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Gerelateerd objecttype</b></td>
                              <td width="70%">
                                 Inhoudsobject
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Inhoudsobject dat onderdeel was van de inhoud van het klantcontact.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-07-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. *</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Betrokkenebijklantcontact"></a><h3> Betrokkene bij klantcontact</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Betrokkenebijklantcontact_ID"></a><h4>Attribuutsoort details ID</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">ID</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Unieke (technische) identificatiecode van de betrokkene bij klantcontact.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificatiecode
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Betrokkenebijklantcontact_Rol"></a><h4>Attribuutsoort details Rol</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Rol</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Rol die de betrokkene bij klantcontact tijdens dat contact vervulde.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Klantcontactrol
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Betrokkenebijklantcontact_Organisatienaam"></a><h4>Attribuutsoort details Organisatienaam</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Organisatienaam</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Naam van de organisatie waarmee de betrokkene bij klantcontact een relatie had.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Naam-lang
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Betrokkenebijklantcontact_Contactnaam"></a><h4>Attribuutsoort Contactnaam van gegevensgroeptype Betrokkene bij klantcontact</h4>
                     
                     <table>
                        <tbody>
                           <tr></tr>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Contactnaam</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Naam die de betrokkene bij klantcontact bij opvolging van dat contact wil gebruiken.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Contactnaam
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_class_Model_Contactnaam"></a><h4>Gegevensgroeptype Contactnaam</h4>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Contactnaam_Voorletters"></a><h5>Attribuutsoort details Voorletters</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Voorletters</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Een afkorting van de voornamen. Meestal de beginletter, maar in sommige gevallen de
                                    beginletter gecombineerd met de tweede letter van een voornaam.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">02-10-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Voorletters
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Contactnaam_Voornaam"></a><h5>Attribuutsoort details Voornaam</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Voornaam</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">De voornaam die de persoon wil gebruiken tijdens communicatie met de gemeente.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%">200</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Naam-kort
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Contactnaam_Voorvoegselachternaam"></a><h5>Attribuutsoort details Voorvoegsel achternaam</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Voorvoegsel achternaam</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Een eventueel voorvoegsel dat hoort bij de achternaam die de persoon wil gebruiken
                                    tijdens communicatie met de gemeente.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%">10</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Voorvoegsel
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Contactnaam_Achternaam"></a><h5>Attribuutsoort details Achternaam</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Achternaam</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Een achternaam die de persoon wil gebruiken tijdens communicatie met de gemeente.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%">200</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Omschrijving-lang
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Betrokkenebijklantcontact_Correspondentieadres"></a><h4>Attribuutsoort Correspondentieadres van gegevensgroeptype Betrokkene bij klantcontact</h4>
                     
                     <table>
                        <tbody>
                           <tr></tr>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Correspondentieadres</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Adres waarop de betrokkene bij klantcontact naar aanleiding van dat contact te versturen
                                 post wil ontvangen.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Correspondentieadres
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_class_Model_Correspondentieadres"></a><h4>Gegevensgroeptype Correspondentieadres</h4>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Correspondentieadres_NummeraanduidingID"></a><h5>Attribuutsoort details NummeraanduidingID</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">NummeraanduidingID</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Identificatie van het adres bij de Basisregistratie Adressen en Gebouwen.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">22-09-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Identificatiecode
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Correspondentieadres_Adresregel1"></a><h5>Attribuutsoort details Adresregel 1</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Adresregel 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Eerste deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Adresregel
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Correspondentieadres_Adresregel2"></a><h5>Attribuutsoort details Adresregel 2</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Adresregel 2</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Tweede deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Adresregel
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Correspondentieadres_Adresregel3"></a><h5>Attribuutsoort details Adresregel 3</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Adresregel 3</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Derde van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Adresregel
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Correspondentieadres_Land"></a><h5>Attribuutsoort details Land</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Land</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BAG</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Een code, opgenomen in Tabel 34, Landentabel, die het land (buiten Nederland) aangeeft
                                    alwaar de ingeschrevene verblijft. </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BAG</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Land
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Betrokkenebijklantcontact_Bezoekadres"></a><h4>Attribuutsoort Bezoekadres van gegevensgroeptype Betrokkene bij klantcontact</h4>
                     
                     <table>
                        <tbody>
                           <tr></tr>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Bezoekadres</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Adres waarop de betrokkene bij klantcontact in naar aanleiding van dat contact af
                                 te leggen bezoeken wil ontvangen.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Bezoekadres
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_class_Model_Bezoekadres"></a><h4>Gegevensgroeptype Bezoekadres</h4>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Bezoekadres_NummeraanduidingID"></a><h5>Attribuutsoort details NummeraanduidingID</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">NummeraanduidingID</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Identificatie van het adres bij de Basisregistratie Adressen en Gebouwen.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">22-09-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Identificatiecode
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Bezoekadres_Adresregel1"></a><h5>Attribuutsoort details Adresregel 1</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Adresregel 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Eerste deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Adresregel
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Bezoekadres_Adresregel2"></a><h5>Attribuutsoort details Adresregel 2</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Adresregel 2</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Tweede deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Adresregel
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Bezoekadres_Adresregel3"></a><h5>Attribuutsoort details Adresregel 3</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Adresregel 3</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Derde deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Adresregel
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Bezoekadres_Land"></a><h5>Attribuutsoort details Land</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Land</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BAG</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Een code, opgenomen in Tabel 34, Landentabel, die het land (buiten Nederland) aangeeft
                                    alwaar de ingeschrevene verblijft. </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BAG</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Land
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     </div>
                  
                  <div><a class="anchor" name="detail_association_Model_Betrokkenebijklantcontact_was"></a><h4>Relatiesoort details was</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">was</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Gerelateerd objecttype</b></td>
                              <td width="70%">
                                 Partij
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Betrokkene bij klantcontact die een partij was.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     
                     </div>
                  
                  <div><a class="anchor" name="detail_association_Model_Betrokkenebijklantcontact_verstrektevooropvolgingvanklantcontact"></a><h4>Relatiesoort details verstrekte voor opvolging van klantcontact</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">verstrekte voor opvolging van klantcontact</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Gerelateerd objecttype</b></td>
                              <td width="70%">
                                 Digitaal adres
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Digitaal adres dat een betrokkene bij klantcontact verstrekte voor gebruik bij opvolging
                                 van een klantcontact.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. *</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_OverigObject"></a><h3> Overig Object</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_OverigObject_ID"></a><h4>Attribuutsoort details ID</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">ID</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">RGBZ</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Unieke identificatie van het Overig Object.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">RGBZ</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificatiecode
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Organisatie"></a><h3> Organisatie</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Organisatie_Naam"></a><h4>Attribuutsoort details Naam</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Naam</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Naam van de organisatie.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Naam-lang
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Onderwerpobject"></a><h3> Onderwerpobject</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Onderwerpobject_ID"></a><h4>Attribuutsoort details ID</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">ID</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Unieke (technische) identificatiecode van het onderwerpdeel.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-06-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificatiecode
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Onderwerpobject_Objectidentificator"></a><h4>Attribuutsoort Objectidentificator van gegevensgroeptype Onderwerpobject</h4>
                     
                     <table>
                        <tbody>
                           <tr></tr>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Objectidentificator</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Gegevens die een onderwerpobject in een extern register uniek identificeren.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">10-10-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificator
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_class_Model_Identificator"></a><h4>Gegevensgroeptype Identificator</h4>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Identificator_Objecttype"></a><h5>Attribuutsoort details Objecttype</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Objecttype</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Type van het object.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">10-10-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Soort object
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Identificator_SoortObjectID"></a><h5>Attribuutsoort details Soort Object ID</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Soort Object ID</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Naam van de eigenschap die het object identificeert.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">10-10-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Soort object ID
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Identificator_ObjectID"></a><h5>Attribuutsoort details Object ID</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Object ID</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Waarde van de eigenschap die het object identificeert.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">10-10-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Identificatiecode
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Identificator_Register"></a><h5>Attribuutsoort details Register</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Register</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Binnen het landschap van registers unieke omschrijving van het register waarin het
                                    object is geregistreerd.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">10-10-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Extern register
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     </div>
                  
                  <div><a class="anchor" name="detail_association_Model_Onderwerpobject_was"></a><h4>Relatiesoort details was</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">was</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Gerelateerd objecttype</b></td>
                              <td width="70%">
                                 Klantcontact
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Klantcontact dat een onderwerpobject was.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-07-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     
                     </div>
                  
                  <div><a class="anchor" name="detail_association_Model_Onderwerpobject_was"></a><h4>Relatiesoort details was</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">was</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Gerelateerd objecttype</b></td>
                              <td width="70%">
                                 Ander Object
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Ander object dat een onderwerpobject was.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-07-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     
                     </div>
                  
                  <div><a class="anchor" name="detail_association_Model_Onderwerpobject_was"></a><h4>Relatiesoort details was</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">was</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Gerelateerd objecttype</b></td>
                              <td width="70%">
                                 Klanttaak
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Klanttaak die een onderwerpobject was.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-07-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     
                     </div>
                  
                  <div><a class="anchor" name="detail_association_Model_Onderwerpobject_was"></a><h4>Relatiesoort details was</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">was</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Gerelateerd objecttype</b></td>
                              <td width="70%">
                                 Zaak
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Zaak die een onderwerpobject was.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-07-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Partij"></a><h3> Partij</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Partij_ID"></a><h4>Attribuutsoort details ID</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">ID</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Unieke (technische) identificatiecode van de partij.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificatiecode
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Partij_Nummer"></a><h4>Attribuutsoort details Nummer</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Nummer</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Uniek identificerend nummer dat tijdens communicatie tussen mensen kan worden gebruikt
                                 om de specifieke partij aan te duiden.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Partijnummer
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Partij_Bezoekadres"></a><h4>Attribuutsoort Bezoekadres van gegevensgroeptype Partij</h4>
                     
                     <table>
                        <tbody>
                           <tr></tr>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Bezoekadres</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Adres waarop de partij door gemeente bezocht wil worden.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Bezoekadres
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_class_Model_Bezoekadres"></a><h4>Gegevensgroeptype Bezoekadres</h4>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Bezoekadres_NummeraanduidingID"></a><h5>Attribuutsoort details NummeraanduidingID</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">NummeraanduidingID</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Identificatie van het adres bij de Basisregistratie Adressen en Gebouwen.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">22-09-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Identificatiecode
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Bezoekadres_Adresregel1"></a><h5>Attribuutsoort details Adresregel 1</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Adresregel 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Eerste deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Adresregel
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Bezoekadres_Adresregel2"></a><h5>Attribuutsoort details Adresregel 2</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Adresregel 2</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Tweede deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Adresregel
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Bezoekadres_Adresregel3"></a><h5>Attribuutsoort details Adresregel 3</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Adresregel 3</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Derde deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Adresregel
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Bezoekadres_Land"></a><h5>Attribuutsoort details Land</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Land</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BAG</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Een code, opgenomen in Tabel 34, Landentabel, die het land (buiten Nederland) aangeeft
                                    alwaar de ingeschrevene verblijft. </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BAG</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Land
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Partij_Correspondentieadres"></a><h4>Attribuutsoort Correspondentieadres van gegevensgroeptype Partij</h4>
                     
                     <table>
                        <tbody>
                           <tr></tr>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Correspondentieadres</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">VNG</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Adres waarop de partij post van de gemeente wil ontvangen.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">VNG</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Correspondentieadres
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_class_Model_Correspondentieadres"></a><h4>Gegevensgroeptype Correspondentieadres</h4>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Correspondentieadres_NummeraanduidingID"></a><h5>Attribuutsoort details NummeraanduidingID</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">NummeraanduidingID</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Identificatie van het adres bij de Basisregistratie Adressen en Gebouwen.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">22-09-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Identificatiecode
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Correspondentieadres_Adresregel1"></a><h5>Attribuutsoort details Adresregel 1</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Adresregel 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Eerste deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Adresregel
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Correspondentieadres_Adresregel2"></a><h5>Attribuutsoort details Adresregel 2</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Adresregel 2</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Tweede deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Adresregel
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Correspondentieadres_Adresregel3"></a><h5>Attribuutsoort details Adresregel 3</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Adresregel 3</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Derde van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Adresregel
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Correspondentieadres_Land"></a><h5>Attribuutsoort details Land</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Land</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BAG</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Een code, opgenomen in Tabel 34, Landentabel, die het land (buiten Nederland) aangeeft
                                    alwaar de ingeschrevene verblijft. </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BAG</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Land
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Partij_Internenotitie"></a><h4>Attribuutsoort details Interne notitie</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Interne notitie</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Mededelingen, aantekeningen of bijzonderheden over de partij, bedoeld voor intern
                                 gebruik.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Tekst
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Partij_Soortpartij"></a><h4>Attribuutsoort details Soort partij</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Soort partij</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Geeft aan van welke specifieke soort partij sprake is.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-06-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Soort partij
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Partij_Indicatiegeheimhouding"></a><h4>Attribuutsoort details Indicatie geheimhouding</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Indicatie geheimhouding</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Geeft aan of de verstrekker van partijgegevens heeft aangegeven dat deze gegevens
                                 als geheim beschouwd moeten worden.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Indicatie Ja Nee
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Partij_Voorkeurskanaal"></a><h4>Attribuutsoort details Voorkeurskanaal</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Voorkeurskanaal</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Kanaal dat de partij bij voorkeur gebruikt voor contact met de gemeente.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Kanaal
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Partij_Voorkeurstaal"></a><h4>Attribuutsoort details Voorkeurstaal</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Voorkeurstaal</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Taal waarin de partij bij voorkeur contact heeft met de gemeente.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Taal
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Partij_Indicatieactief"></a><h4>Attribuutsoort details Indicatie actief</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Indicatie actief</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Geeft aan of de contactgegevens van de partij nog gebruikt morgen worden om contact
                                 op te nemen. Gegevens van niet-actieve partijen mogen hiervoor niet worden gebruikt.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-06-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Indicatie Ja Nee
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_association_Model_Partij_had"></a><h4>Relatiesoort details had</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">had</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Gerelateerd objecttype</b></td>
                              <td width="70%">
                                 Partij-identificator
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klaninteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Partij-identificator die een partij had.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klaninteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-07-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1 .. *</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     
                     </div>
                  
                  <div><a class="anchor" name="detail_association_Model_Partij_vertegenwoordigde"></a><h4>Relatiesoort details vertegenwoordigde</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">vertegenwoordigde</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Gerelateerd objecttype</b></td>
                              <td width="70%">
                                 Partij
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Partij die een andere partij vertegenwoordigde.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-07-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. *</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     
                     </div>
                  
                  <div><a class="anchor" name="detail_association_Model_Partij_verstrektevoortoekomstigcontact"></a><h4>Relatiesoort details verstrekte voor toekomstig contact</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">verstrekte voor toekomstig contact</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Gerelateerd objecttype</b></td>
                              <td width="70%">
                                 Digitaal adres
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Digitaal adres dat een partij verstrekte voor gebruik bij toekomstig contact met de
                                 gemeente.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-07-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. *</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Inhoudsobject"></a><h3> Inhoudsobject</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Inhoudsobject_ID"></a><h4>Attribuutsoort details ID</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">ID</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Unieke (technische) identificatiecode van het inhoudsdeel.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificatiecode
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Inhoudsobject_Objectidentificator"></a><h4>Attribuutsoort Objectidentificator van gegevensgroeptype Inhoudsobject</h4>
                     
                     <table>
                        <tbody>
                           <tr></tr>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Objectidentificator</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Gegevens die een inhoudsobject in een extern register uniek identificeren.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">10-10-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificator
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_class_Model_Identificator"></a><h4>Gegevensgroeptype Identificator</h4>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Identificator_Objecttype"></a><h5>Attribuutsoort details Objecttype</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Objecttype</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Type van het object.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">10-10-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Soort object
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Identificator_SoortObjectID"></a><h5>Attribuutsoort details Soort Object ID</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Soort Object ID</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Naam van de eigenschap die het object identificeert.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">10-10-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Soort object ID
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Identificator_ObjectID"></a><h5>Attribuutsoort details Object ID</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Object ID</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Waarde van de eigenschap die het object identificeert.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">10-10-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Identificatiecode
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Identificator_Register"></a><h5>Attribuutsoort details Register</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Register</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Binnen het landschap van registers unieke omschrijving van het register waarin het
                                    object is geregistreerd.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">10-10-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Extern register
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     </div>
                  
                  <div><a class="anchor" name="detail_association_Model_Inhoudsobject_was"></a><h4>Relatiesoort details was</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">was</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Gerelateerd objecttype</b></td>
                              <td width="70%">
                                 Informatieobject
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Informatieobject dat een inhoudsobject was.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-07-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     
                     </div>
                  
                  <div><a class="anchor" name="detail_association_Model_Inhoudsobject_was"></a><h4>Relatiesoort details was</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">was</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Gerelateerd objecttype</b></td>
                              <td width="70%">
                                 Overig Object
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Overig object dat een inhoudsobject was.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-07-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     
                     </div>
                  
                  <div><a class="anchor" name="detail_association_Model_Inhoudsobject_was"></a><h4>Relatiesoort details was</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">was</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Gerelateerd objecttype</b></td>
                              <td width="70%">
                                 Ander Object
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Ander object dat een inhoudsobject was.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-07-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Contactpersoon"></a><h3> Contactpersoon</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Contactpersoon_Contactnaam"></a><h4>Attribuutsoort Contactnaam van gegevensgroeptype Contactpersoon</h4>
                     
                     <table>
                        <tbody>
                           <tr></tr>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Contactnaam</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">VNG</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De naam die de contactpersoon wil gebruiken tijdens contact met de gemeente.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">VNG</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-06-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Contactnaam
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_class_Model_Contactnaam"></a><h4>Gegevensgroeptype Contactnaam</h4>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Contactnaam_Voorletters"></a><h5>Attribuutsoort details Voorletters</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Voorletters</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Een afkorting van de voornamen. Meestal de beginletter, maar in sommige gevallen de
                                    beginletter gecombineerd met de tweede letter van een voornaam.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">02-10-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Voorletters
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Contactnaam_Voornaam"></a><h5>Attribuutsoort details Voornaam</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Voornaam</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">De voornaam die de persoon wil gebruiken tijdens communicatie met de gemeente.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%">200</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Naam-kort
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Contactnaam_Voorvoegselachternaam"></a><h5>Attribuutsoort details Voorvoegsel achternaam</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Voorvoegsel achternaam</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Een eventueel voorvoegsel dat hoort bij de achternaam die de persoon wil gebruiken
                                    tijdens communicatie met de gemeente.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%">10</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Voorvoegsel
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Contactnaam_Achternaam"></a><h5>Attribuutsoort details Achternaam</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Achternaam</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Een achternaam die de persoon wil gebruiken tijdens communicatie met de gemeente.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%">200</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Omschrijving-lang
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     </div>
                  
                  <div><a class="anchor" name="detail_association_Model_Contactpersoon_werktevoor"></a><h4>Relatiesoort details werkte voor</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">werkte voor</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Gerelateerd objecttype</b></td>
                              <td width="70%">
                                 Organisatie
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Organisatie waarvoor een contactpersoon werkte.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-07-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Persoon"></a><h3> Persoon</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Persoon_Contactnaam"></a><h4>Attribuutsoort Contactnaam van gegevensgroeptype Persoon</h4>
                     
                     <table>
                        <tbody>
                           <tr></tr>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Contactnaam</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De naam die de persoon wil gebruiken tijdens contact met de gemeente.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-07-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">n.v.t.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Overig</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Contactnaam
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_class_Model_Contactnaam"></a><h4>Gegevensgroeptype Contactnaam</h4>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Contactnaam_Voorletters"></a><h5>Attribuutsoort details Voorletters</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Voorletters</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Een afkorting van de voornamen. Meestal de beginletter, maar in sommige gevallen de
                                    beginletter gecombineerd met de tweede letter van een voornaam.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">02-10-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Voorletters
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Contactnaam_Voornaam"></a><h5>Attribuutsoort details Voornaam</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Voornaam</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">De voornaam die de persoon wil gebruiken tijdens communicatie met de gemeente.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%">200</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Naam-kort
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Contactnaam_Voorvoegselachternaam"></a><h5>Attribuutsoort details Voorvoegsel achternaam</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Voorvoegsel achternaam</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Een eventueel voorvoegsel dat hoort bij de achternaam die de persoon wil gebruiken
                                    tijdens communicatie met de gemeente.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%">10</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Voorvoegsel
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Contactnaam_Achternaam"></a><h5>Attribuutsoort details Achternaam</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Achternaam</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Een achternaam die de persoon wil gebruiken tijdens communicatie met de gemeente.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">16-02-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">0 .. 1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%">200</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Omschrijving-lang
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_AnderObject"></a><h3> Ander Object</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_AnderObject_ID"></a><h4>Attribuutsoort details ID</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">ID</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">VNG</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Unieke identificatie van het Ander Object</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">VNG</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">20230216</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificatiecode
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Digitaaladres"></a><h3> Digitaal adres</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Digitaaladres_ID"></a><h4>Attribuutsoort details ID</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">ID</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Unieke (technische) identificatiecode van het digitaal adres.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificatiecode
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Digitaaladres_Soortdigitaaladres"></a><h4>Attribuutsoort details Soort digitaal adres</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Soort digitaal adres</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Typering van het digitale adres die aangeeft via welk(e) kanaal of kanalen met dit
                                 adres contact kan worden opgenomen.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Soort digitaal adres
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Digitaaladres_Adres"></a><h4>Attribuutsoort details Adres</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Adres</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Digitaal adres waarmee een persoon of organisatie bereikt kan worden.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Adresregel
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Digitaaladres_Omschrijving"></a><h4>Attribuutsoort details Omschrijving</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Omschrijving</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Omschrijving van het digitaal adres.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Omschrijving-kort
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Medewerker"></a><h3> Medewerker</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Medewerker_Functie"></a><h4>Attribuutsoort details Functie</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Functie</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">RGBZ</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De aanduiding van de taken, rechten en plichten die de MEDEWERKER heeft of heeft gehad
                                 binnen de zaakbehandelende organisatie.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">RGBZ</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Omschrijving-kort
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Medewerker_Emailadres"></a><h4>Attribuutsoort details E-mailadres</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">E-mailadres</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">RGBZ</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Elektronisch postadres waaronder de MEDEWERKER in de regel bereikbaar is.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">RGBZ</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 E-mailadres
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Medewerker_Telefoonnummer"></a><h4>Attribuutsoort details Telefoonnummer</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Telefoonnummer</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">RGBZ</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Telefoonnummer waaronder de MEDEWERKER in de regel bereikbaar is.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">RGBZ</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Telefoonnummer
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Geautomatiseerdeactor"></a><h3> Geautomatiseerde actor</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Geautomatiseerdeactor_Functie"></a><h4>Attribuutsoort details Functie</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Functie</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Functie van de geautomatiseerde actor of beschrijving van de werkzaamheden die deze
                                 uitvoert.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Omschrijving-kort
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Geautomatiseerdeactor_Omschrijving"></a><h4>Attribuutsoort details Omschrijving</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Omschrijving</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Omschrijving van de geautomatiseerde actor.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Omschrijving-lang
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Informatieobject"></a><h3> Informatieobject</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Informatieobject_Informatieobjectidentificatie"></a><h4>Attribuutsoort details Informatieobjectidentificatie</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Informatieobjectidentificatie</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">RGBZ</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Een binnen een gegeven context ondubbelzinnige referentie naar het INFORMATIEOBJECT.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">RGBZ</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificatiecode
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Actor"></a><h3> Actor</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Actor_ID"></a><h4>Attribuutsoort details ID</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">ID</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Unieke (technische) identificatiecode van de actor.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificatiecode
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Actor_Naam"></a><h4>Attribuutsoort details Naam</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Naam</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Naam van de actor.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Naam-lang
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Actor_Soortactor"></a><h4>Attribuutsoort details Soort actor</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Soort actor</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Geeft aan van welke specifieke soort actor sprake is.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-06-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Soort actor
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Actor_Indicatieactief"></a><h4>Attribuutsoort details Indicatie actief</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Indicatie actief</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Geeft aan of aan de actor nog betrokken mag worden bij nieuwe klantcontacten. Voor
                                 niet-actieve is dit niet toegestaan.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-06-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Indicatie Ja Nee
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Actor_Actoridentifcator"></a><h4>Attribuutsoort Actoridentifcator van gegevensgroeptype Actor</h4>
                     
                     <table>
                        <tbody>
                           <tr></tr>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Actoridentifcator</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Gegevens die een actor in een extern register uniek identificeren.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">10-10-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificator
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_class_Model_Identificator"></a><h4>Gegevensgroeptype Identificator</h4>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Identificator_Objecttype"></a><h5>Attribuutsoort details Objecttype</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Objecttype</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Type van het object.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">10-10-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Soort object
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Identificator_SoortObjectID"></a><h5>Attribuutsoort details Soort Object ID</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Soort Object ID</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Naam van de eigenschap die het object identificeert.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">10-10-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Soort object ID
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Identificator_ObjectID"></a><h5>Attribuutsoort details Object ID</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Object ID</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Waarde van de eigenschap die het object identificeert.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">10-10-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Identificatiecode
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Identificator_Register"></a><h5>Attribuutsoort details Register</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Register</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Binnen het landschap van registers unieke omschrijving van het register waarin het
                                    object is geregistreerd.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">10-10-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Extern register
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Organisatorischeeenheid"></a><h3> Organisatorische eenheid</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Organisatorischeeenheid_Omschrijving"></a><h4>Attribuutsoort details Omschrijving</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Omschrijving</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">RGBZ</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Een omschrijving van de organisatorische eenheid.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">RGBZ</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%">80</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Omschrijving-lang
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%">alle alfanumerieke tekens</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Organisatorischeeenheid_Emailadres"></a><h4>Attribuutsoort details E-mailadres</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">E-mailadres</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">RGBZ</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Elektronisch postadres waaronder de organisatorische eenheid in de regel bereikbaar
                                 is. </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">RGBZ</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%">254</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 E-mailadres
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%">alle bestaande alfanumerieke tekens waarin zich, evenwel niet aan het begin en aan
                                 het eind, een ‘@’ moet bevinden.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Toelichting</b></td>
                           </tr>
                        </tbody>
                     </table>
                     <table>
                        <tbody>
                           <tr>
                              <td width="5%">&nbsp;</td>
                              <td width="95%">Het attribuutsoort is overeenkomstig het attribuutsoort Subject.Emailadres.</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Organisatorischeeenheid_Faxnummer"></a><h4>Attribuutsoort details Faxnummer</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Faxnummer</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">RGBZ</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Faxnummer waaronder de organisatorische eenheid in de regel bereikbaar is.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">RGBZ</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%">20</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Telefoonnummer
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%">alle bestaande alfanumerieke tekens.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Toelichting</b></td>
                           </tr>
                        </tbody>
                     </table>
                     <table>
                        <tbody>
                           <tr>
                              <td width="5%">&nbsp;</td>
                              <td width="95%"><br>                                 Het attribuutsoort is overeenkomstig het attribuutsoort
                                 Subject.FAX-nummer.<br>                                 Het type is alfanumeriek zodat eventuele toevoegingen
                                 als 'bgg', 'zak' of 'mobiel' kunnen worden verwerkt.<br>                              </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Organisatorischeeenheid_Telefoonnummer"></a><h4>Attribuutsoort details Telefoonnummer</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Telefoonnummer</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">RGBZ</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Telefoonnummer waaronder de organisatorische eenheid in de regel bereikbaar is.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">RGBZ</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%">20</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Telefoonnummer
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%">alle bestaande alfanumerieke tekens</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Toelichting</b></td>
                           </tr>
                        </tbody>
                     </table>
                     <table>
                        <tbody>
                           <tr>
                              <td width="5%">&nbsp;</td>
                              <td width="95%"><br>                                 Het attribuutsoort is overeenkomstig het attribuutsoort
                                 Subject.Telefoonnummer.<br>                                 Het type is alfanumeriek zodat eventuele toevoegingen
                                 als 'bgg', 'zak' of 'mobiel' kunnen worden verwerkt.<br>                              </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Internetaak"></a><h3> Interne taak</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Internetaak_ID"></a><h4>Attribuutsoort details ID</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">ID</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Unieke (technische) identificatiecode van de interne taak.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificatiecode
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Internetaak_Nummer"></a><h4>Attribuutsoort details Nummer</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Nummer</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Uniek identificerend nummer dat tijdens communicatie tussen mensen kan worden gebruikt
                                 om de specifieke interne taak aan te duiden.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificerend nummer
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Internetaak_Gevraagdehandeling"></a><h4>Attribuutsoort details Gevraagde handeling</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Gevraagde handeling</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Handeling die moet worden uitgevoerd om de taak af te ronden.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Omschrijving-lang
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Internetaak_Toelichting"></a><h4>Attribuutsoort details Toelichting</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Toelichting</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Toelichting die, aanvullend bij de inhoud van het klantcontact dat aanleiding gaf
                                 tot de taak en de gevraagde handeling, bijdraagt aan het kunnen afhandelen van de
                                 taak.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Toelichting
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Internetaak_Status"></a><h4>Attribuutsoort details Status</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Status</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Aanduiding van de vordering bij afhandeling van de interne taak.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Taakstatus
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Internetaak_Toegewezenop"></a><h4>Attribuutsoort details Toegewezen op</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Toegewezen op</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Datum en tijdstip waarop de interne taak aan een actor werd toegewezen.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">05-10-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Datumtijd
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_association_Model_Internetaak_werdtoegewezenaan"></a><h4>Relatiesoort details werd toegewezen aan</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">werd toegewezen aan</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Gerelateerd objecttype</b></td>
                              <td width="70%">
                                 Actor
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Actor die een interne taak toegewezen kreeg.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-07-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     
                     </div>
                  
                  <div><a class="anchor" name="detail_association_Model_Internetaak_ontstondnaaraanleidingvan"></a><h4>Relatiesoort details ontstond naar aanleiding van</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">ontstond naar aanleiding van</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Gerelateerd objecttype</b></td>
                              <td width="70%">
                                 Klantcontact
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Klantcontact dat leidde tot een interne taak.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-07-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Klanttaak"></a><h3> Klanttaak</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Klanttaak_ID"></a><h4>Attribuutsoort details ID</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">ID</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">VNG</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Unieke identificatiecode van de klanttaak.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">VNG</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificatiecode
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Klanttaak_Nummer"></a><h4>Attribuutsoort details Nummer</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Nummer</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">VNG</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Uniek identificerend nummer waarmee tijdens communicatie tussen mensen verwezen kan
                                 worden naar de klanttaak.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">VNG</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificerend nummer
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Klanttaak_Gevraagdehandeling"></a><h4>Attribuutsoort details Gevraagde handeling</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Gevraagde handeling</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">VNG</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Op de klant gerichte uitleg van de activiteit die de gemeente vraag aan de klant om
                                 uit te voeren. </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">VNG</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Omschrijving-lang
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Klanttaak_Toelichting"></a><h4>Attribuutsoort details Toelichting</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Toelichting</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">VNG</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Toelichtende tekst op de aan de klant gevraagde uit te voeren handeling. </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">VNG</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Toelichting
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Klanttaak_Status"></a><h4>Attribuutsoort details Status</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Status</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">VNG</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De indicatie of de klantaak is uitgevoerd.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">VNG</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Taakstatus
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Zaak"></a><h3> Zaak</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Zaak_Zaakidentificatie"></a><h4>Attribuutsoort details Zaakidentificatie</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Zaakidentificatie</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">RGBZ</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De unieke identificatie van de ZAAK binnen de organisatie die verantwoordelijk is
                                 voor de behandeling van de ZAAK.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">RGBZ</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 CharacterString
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Partijidentificator"></a><h3> Partij-identificator</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Partijidentificator_ID"></a><h4>Attribuutsoort details ID</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">ID</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Unieke (technische) identificatiecode van de externe identificatie</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-06-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificatiecode
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Partijidentificator_Partijidentificator"></a><h4>Attribuutsoort Partij-identificator van gegevensgroeptype Partij-identificator</h4>
                     
                     <table>
                        <tbody>
                           <tr></tr>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Partij-identificator</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Gegevens die een partij in een basisregistratie of ander extern register uniek identificeren.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">10-10-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie formele historie</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie in onderzoek</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Aanduiding strijdigheid/nietigheid</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Regels</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificator
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_class_Model_Identificator"></a><h4>Gegevensgroeptype Identificator</h4>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Identificator_Objecttype"></a><h5>Attribuutsoort details Objecttype</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Objecttype</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Type van het object.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">Klantinteracties</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">10-10-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Soort object
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Identificator_SoortObjectID"></a><h5>Attribuutsoort details Soort Object ID</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Soort Object ID</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Naam van de eigenschap die het object identificeert.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">10-10-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Soort object ID
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Identificator_ObjectID"></a><h5>Attribuutsoort details Object ID</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Object ID</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Waarde van de eigenschap die het object identificeert.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">10-10-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Identificatiecode
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     
                     <div><a class="anchor" name="detail_attribute_Model_Identificator_Register"></a><h5>Attribuutsoort details Register</h5>
                        
                        <table>
                           <tbody>
                              <tr>
                                 <td width="30%"><b>Naam</b></td>
                                 <td width="70%">Register</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Definitie</b></td>
                                 <td width="70%">Binnen het landschap van registers unieke omschrijving van het register waarin het
                                    object is geregistreerd.</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Herkomst definitie</b></td>
                                 <td width="70%">BRP</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Datum opname</b></td>
                                 <td width="70%">10-10-2023</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Mogelijk geen waarde</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie kardinaliteit</b></td>
                                 <td width="70%">1</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie authentiek</b></td>
                                 <td width="70%">Authentiek</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Lengte</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Formaat</b></td>
                                 <td width="70%">
                                    Extern register
                                    </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Patroon</b></td>
                                 <td width="70%"> </td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Indicatie afleidbaar</b></td>
                                 <td width="70%">Zie package</td>
                              </tr>
                              <tr>
                                 <td width="30%"><b>Waarde afleidbaar</b></td>
                                 <td width="70%">Nee</td>
                              </tr>
                           </tbody>
                        </table>
                        </div>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Partijidentificator_Anderepartijidentificator"></a><h4>Attribuutsoort details Andere partij-identificator</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Andere partij-identificator</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Vrij tekstveld om de verwijzing naar een niet-voorgedefinieerd objecttype, soort objectID
                                 of Register vast te leggen. </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">20230216</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Omschrijving-lang
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               </div>
            
            <div>
               <h2>Gegevensgroeptype details </h2>
               
               <div><a class="anchor" name="detail_class_Model_Identificator"></a><h3>Gegevensgroeptype Identificator</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Identificator_Objecttype"></a><h4>Attribuutsoort details Objecttype</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Objecttype</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Type van het object.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">10-10-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Soort object
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Identificator_SoortObjectID"></a><h4>Attribuutsoort details Soort Object ID</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Soort Object ID</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">BRP</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Naam van de eigenschap die het object identificeert.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">BRP</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">10-10-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Soort object ID
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Identificator_ObjectID"></a><h4>Attribuutsoort details Object ID</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Object ID</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">BRP</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Waarde van de eigenschap die het object identificeert.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">BRP</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">10-10-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificatiecode
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Identificator_Register"></a><h4>Attribuutsoort details Register</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Register</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">BRP</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Binnen het landschap van registers unieke omschrijving van het register waarin het
                                 object is geregistreerd.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">BRP</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">10-10-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Extern register
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Bezoekadres"></a><h3>Gegevensgroeptype Bezoekadres</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Bezoekadres_NummeraanduidingID"></a><h4>Attribuutsoort details NummeraanduidingID</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">NummeraanduidingID</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Identificatie van het adres bij de Basisregistratie Adressen en Gebouwen.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">22-09-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificatiecode
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Bezoekadres_Adresregel1"></a><h4>Attribuutsoort details Adresregel 1</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Adresregel 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">BRP</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Eerste deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">BRP</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Adresregel
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Bezoekadres_Adresregel2"></a><h4>Attribuutsoort details Adresregel 2</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Adresregel 2</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">BRP</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Tweede deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">BRP</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Adresregel
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Bezoekadres_Adresregel3"></a><h4>Attribuutsoort details Adresregel 3</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Adresregel 3</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">BRP</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Derde deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">BRP</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Adresregel
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Bezoekadres_Land"></a><h4>Attribuutsoort details Land</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Land</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">BAG</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Een code, opgenomen in Tabel 34, Landentabel, die het land (buiten Nederland) aangeeft
                                 alwaar de ingeschrevene verblijft. </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">BAG</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Land
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Contactnaam"></a><h3>Gegevensgroeptype Contactnaam</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Contactnaam_Voorletters"></a><h4>Attribuutsoort details Voorletters</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Voorletters</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Een afkorting van de voornamen. Meestal de beginletter, maar in sommige gevallen de
                                 beginletter gecombineerd met de tweede letter van een voornaam.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">02-10-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Voorletters
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Contactnaam_Voornaam"></a><h4>Attribuutsoort details Voornaam</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Voornaam</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De voornaam die de persoon wil gebruiken tijdens communicatie met de gemeente.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%">200</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Naam-kort
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Contactnaam_Voorvoegselachternaam"></a><h4>Attribuutsoort details Voorvoegsel achternaam</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Voorvoegsel achternaam</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Een eventueel voorvoegsel dat hoort bij de achternaam die de persoon wil gebruiken
                                 tijdens communicatie met de gemeente.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%">10</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Voorvoegsel
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Contactnaam_Achternaam"></a><h4>Attribuutsoort details Achternaam</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Achternaam</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Een achternaam die de persoon wil gebruiken tijdens communicatie met de gemeente.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%">200</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Omschrijving-lang
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Correspondentieadres"></a><h3>Gegevensgroeptype Correspondentieadres</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Correspondentieadres_NummeraanduidingID"></a><h4>Attribuutsoort details NummeraanduidingID</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">NummeraanduidingID</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Identificatie van het adres bij de Basisregistratie Adressen en Gebouwen.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">Klantinteracties</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">22-09-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificatiecode
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Correspondentieadres_Adresregel1"></a><h4>Attribuutsoort details Adresregel 1</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Adresregel 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">BRP</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Eerste deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">BRP</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Adresregel
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Correspondentieadres_Adresregel2"></a><h4>Attribuutsoort details Adresregel 2</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Adresregel 2</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">BRP</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Tweede deel van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">BRP</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Adresregel
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Correspondentieadres_Adresregel3"></a><h4>Attribuutsoort details Adresregel 3</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Adresregel 3</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">BRP</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Derde van het adres dat niet voorkomt in de Basisregistratie Adressen en Gebouwen.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">BRP</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Adresregel
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Correspondentieadres_Land"></a><h4>Attribuutsoort details Land</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Land</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%">BAG</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Een code, opgenomen in Tabel 34, Landentabel, die het land (buiten Nederland) aangeeft
                                 alwaar de ingeschrevene verblijft. </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%">BAG</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">16-02-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Mogelijk geen waarde</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">0 .. 1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie authentiek</b></td>
                              <td width="70%">Authentiek</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Lengte</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Land
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie afleidbaar</b></td>
                              <td width="70%">Zie package</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Waarde afleidbaar</b></td>
                              <td width="70%">Nee</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               </div>
            
            
            
            
            
            <div>
               <h2>Referentielijst </h2>
               
               <div><a class="anchor" name="detail_class_Model_Taal"></a><h3>Referentielijst Taal</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Taal_Code"></a><h4>Referentie element Code</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Code</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De code, behorende bij de voorkeurstaal.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">1 november 2008</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 CharacterString
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%">0000 en verder alleen natuurlijke getallen zonder voorloopnullen</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Taal_Naam"></a><h4>Referentie element Naam</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Naam</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De naam van de voorkeurstaal.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">1 november 2008</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 CharacterString
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Taal_Indicatieactief"></a><h4>Referentie element Indicatie actief</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Indicatie actief</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Indicatie of de betreffende voorkeurstaal nog gebruikt mag worden. </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-06-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Indicatie Ja Nee
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Land"></a><h3>Referentielijst Land</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Land_Landcode"></a><h4>Referentie element Landcode</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Landcode</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De code, behorende bij de landnaam, opgenomen in de Landentabel van de GBA.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">1 november 2008</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 CharacterString
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%">0000 en verder alleen natuurlijke getallen zonder voorloopnullen</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Land_Landnaam"></a><h4>Referentie element Landnaam</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Landnaam</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De naam van het land, zoals opgenomen in de Landentabel van de GBA.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">1 november 2008</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 CharacterString
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Land_Ingangsdatumland"></a><h4>Referentie element Ingangsdatum land</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Ingangsdatum land</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De datum waarop het land/gebied is ontstaan.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">1 november 2008</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Date
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Land_Einddatumland"></a><h4>Referentie element Einddatum land</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Einddatum land</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De datum waarop het land/gebied is opgeheven.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">1 november 2008</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Date
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Kanaal"></a><h3>Referentielijst Kanaal</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Kanaal_Code"></a><h4>Referentie element Code</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Code</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De code, behorende bij het kanaal.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">1 november 2008</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 CharacterString
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%">0000 en verder alleen natuurlijke getallen zonder voorloopnullen</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Kanaal_Naam"></a><h4>Referentie element Naam</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Naam</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De naam van het kanaal.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">1 november 2008</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 CharacterString
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Kanaal_Indicatieactief"></a><h4>Referentie element Indicatie actief</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Indicatie actief</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Indicatie of het betreffende kanaal nog gebruikt mag worden. </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-06-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Indicatie Ja Nee
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Soortobject"></a><h3>Referentielijst Soort object</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Soortobject_Code"></a><h4>Referentie element Code</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Code</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De code, behorende bij het soort object.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">1 november 2008</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 CharacterString
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%">0000 en verder alleen natuurlijke getallen zonder voorloopnullen</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Soortobject_Naam"></a><h4>Referentie element Naam</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Naam</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De naam van het soort object.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">1 november 2008</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 CharacterString
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Soortobject_Indicatieactief"></a><h4>Referentie element Indicatie actief</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Indicatie actief</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Indicatie of het betreffende soort object nog gebruikt mag worden. </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-06-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Indicatie Ja Nee
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Externregister"></a><h3>Referentielijst Extern register</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Externregister_Code"></a><h4>Referentie element Code</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Code</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De code, behorende bij het soort extern id.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">1 november 2008</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Identificatiecode
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%">0000 en verder alleen natuurlijke getallen zonder voorloopnullen</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Externregister_Naam"></a><h4>Referentie element Naam</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Naam</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De naam van het soort extern id.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">1 november 2008</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Naam-kort
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Externregister_Locatie"></a><h4>Referentie element Locatie</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Locatie</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Indicatie die aangeeft of het soort extern ID nog actief is en toegekend mag worden
                                 aan een etern ID van een Partij. </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-06-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Omschrijving-kort
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Soortdigitaaladres"></a><h3>Referentielijst Soort digitaal adres</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Soortdigitaaladres_Code"></a><h4>Referentie element Code</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Code</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De code, behorende bij het soort digitaal adres.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">1 november 2008</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 CharacterString
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%">0000 en verder alleen natuurlijke getallen zonder voorloopnullen</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Soortdigitaaladres_Naam"></a><h4>Referentie element Naam</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Naam</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De naam van het soort digitaal adres.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">1 november 2008</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 CharacterString
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_Soortdigitaaladres_Indicatieactief"></a><h4>Referentie element Indicatie actief</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Indicatie actief</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Indicatie of het betreffende digitale adres nog gebruikt mag worden. </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-06-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Indicatie Ja Nee
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_SoortobjectID"></a><h3>Referentielijst Soort object ID</h3>
                  
                  <div><a class="anchor" name="detail_attribute_Model_SoortobjectID_Code"></a><h4>Referentie element Code</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Code</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De code, behorende bij het soort extern id.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">1 november 2008</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 CharacterString
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%">0000 en verder alleen natuurlijke getallen zonder voorloopnullen</td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_SoortobjectID_Externregister"></a><h4>Referentie element Extern register</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Extern register</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Het register dat geraadpleegd kan worden m.b.v. de externe identificatiecode. </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">1 november 2008</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Extern register
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_SoortobjectID_Naam"></a><h4>Referentie element Naam</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Naam</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">De naam van het soort extern id.</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">1 november 2008</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 CharacterString
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_SoortobjectID_Indicatieactief"></a><h4>Referentie element Indicatie actief</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Indicatie actief</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Indicatie die aangeeft of het soort extern ID nog actief is en toegekend mag worden
                                 aan een etern ID van een Partij. </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-06-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Indicatie Ja Nee
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  
                  <div><a class="anchor" name="detail_attribute_Model_SoortobjectID_Soortpartij"></a><h4>Referentie element Soort partij</h4>
                     
                     <table>
                        <tbody>
                           <tr>
                              <td width="30%"><b>Naam</b></td>
                              <td width="70%">Soort partij</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Definitie</b></td>
                              <td width="70%">Indicatie voor welk soort partij dit soort extern ID toepasbaar is. </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Herkomst definitie</b></td>
                              <td width="70%"> </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Datum opname</b></td>
                              <td width="70%">08-06-2023</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Indicatie kardinaliteit</b></td>
                              <td width="70%">1</td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Formaat</b></td>
                              <td width="70%">
                                 Soort partij
                                 </td>
                           </tr>
                           <tr>
                              <td width="30%"><b>Patroon</b></td>
                              <td width="70%"> </td>
                           </tr>
                        </tbody>
                     </table>
                     </div>
                  </div>
               </div>
            
            
            <div>
               <h2>Enumeratie </h2>
               
               <div><a class="anchor" name="detail_class_Model_Initiator"></a><h3>Enumeratie details Initiator</h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td width="100%">De waarden van de partij die het contact heeft geinitieerd.</td>
                        </tr>
                     </tbody>
                  </table>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i>Waarde</i></td>
                           <td><i>Omschrijving</i></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>gemeente</b></td>
                           <td width="60%">De gemeente heeft het contact geinitieerd.</td>
                        </tr>
                        <tr>
                           <td width="40%"><b>klant</b></td>
                           <td width="60%">De klant heeft het contact geinitieerd.</td>
                        </tr>
                        <tr>
                           <td width="40%"><b>vertegenwoordiger</b></td>
                           <td width="60%"></td>
                        </tr>
                     </tbody>
                  </table>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Indicatiejaneeonbekend"></a><h3>Enumeratie details Indicatie ja nee onbekend</h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td width="100%">Deze enumeratie is toegevoegd omdat de ingevulde waarde geen boolean kan zijn (waar
                              of niet waar). De gewenste waarden zijn ja,nee of onbekend.  </td>
                        </tr>
                     </tbody>
                  </table>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i>Waarde</i></td>
                           <td><i>Omschrijving</i></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>onbekend</b></td>
                           <td width="60%"></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>ja</b></td>
                           <td width="60%">Het verzoek is afgehandeld.</td>
                        </tr>
                     </tbody>
                  </table>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Taakstatus"></a><h3>Enumeratie details Taakstatus</h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td width="100%">De waarden van de typering van de voortgang van afhandeling van een VERZOEK.</td>
                        </tr>
                     </tbody>
                  </table>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i>Waarde</i></td>
                           <td><i>Omschrijving</i></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>te verwerken</b></td>
                           <td width="60%">Het verzoek is afgehandeld.</td>
                        </tr>
                        <tr>
                           <td width="40%"><b>verwerkt</b></td>
                           <td width="60%">Het verzoek id buiten behandeling gesteld.</td>
                        </tr>
                     </tbody>
                  </table>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Soortbezoekadres"></a><h3>Enumeratie details Soort bezoekadres</h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td width="100%">Typering waarmee aangegeven of het bezoekadres een binnenlands - of een buitenlands
                              adres is. </td>
                        </tr>
                     </tbody>
                  </table>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i>Waarde</i></td>
                           <td><i>Omschrijving</i></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>binnenlands adres</b></td>
                           <td width="60%"></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>buitenlands adres</b></td>
                           <td width="60%"></td>
                        </tr>
                     </tbody>
                  </table>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Aanduidingbijhuisnummer"></a><h3>Enumeratie details Aanduiding bij huisnummer</h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td width="100%">De aanduiding die gebruikt wordt voor bijvoorbeeld een ligplaats of een standplaats
                              die geen eigen nummeraanduiding heeft. </td>
                        </tr>
                     </tbody>
                  </table>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i>Waarde</i></td>
                           <td><i>Omschrijving</i></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>bij</b></td>
                           <td width="60%"></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>tegenover</b></td>
                           <td width="60%"></td>
                        </tr>
                     </tbody>
                  </table>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Soortcorrespondentieadres"></a><h3>Enumeratie details Soort correspondentieadres</h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td width="100%">Typering waarmee aangegeven wordt of het correspondentieadres een binnenlands - of
                              een buitenlands adres is danwel een postbusnummer of een antwoordnummer. </td>
                        </tr>
                     </tbody>
                  </table>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i>Waarde</i></td>
                           <td><i>Omschrijving</i></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>postbusnummer</b></td>
                           <td width="60%"></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>antwoordnummer</b></td>
                           <td width="60%"></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>binnenlands adres</b></td>
                           <td width="60%"></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>buitenlands adres</b></td>
                           <td width="60%"></td>
                        </tr>
                     </tbody>
                  </table>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Soortactor"></a><h3>Enumeratie details Soort actor</h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td width="100%">De typering van de actor.   </td>
                        </tr>
                     </tbody>
                  </table>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i>Waarde</i></td>
                           <td><i>Omschrijving</i></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>medewerker</b></td>
                           <td width="60%"></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>geautomatiseerde actor</b></td>
                           <td width="60%"></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>organisatorische eenheid</b></td>
                           <td width="60%"></td>
                        </tr>
                     </tbody>
                  </table>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Soortinhoudsdeel"></a><h3>Enumeratie details Soort inhoudsdeel</h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td width="100%">De typering van het inhoudsdeel.   </td>
                        </tr>
                     </tbody>
                  </table>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i>Waarde</i></td>
                           <td><i>Omschrijving</i></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>informatieobject</b></td>
                           <td width="60%"></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>overig object</b></td>
                           <td width="60%"></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>tekst</b></td>
                           <td width="60%"></td>
                        </tr>
                     </tbody>
                  </table>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Soortpartij"></a><h3>Enumeratie details Soort partij</h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td width="100%">De typering van de partij.</td>
                        </tr>
                     </tbody>
                  </table>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i>Waarde</i></td>
                           <td><i>Omschrijving</i></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>persoon</b></td>
                           <td width="60%"></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>organisatie</b></td>
                           <td width="60%"></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>contactpersoon</b></td>
                           <td width="60%"></td>
                        </tr>
                     </tbody>
                  </table>
                  </div>
               
               <div><a class="anchor" name="detail_class_Model_Klantcontactrol"></a><h3>Enumeratie details Klantcontactrol</h3>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td width="100%">De typering van de rol van de persoon of organisatie in het klantcontact.   </td>
                        </tr>
                     </tbody>
                  </table>
                  
                  <table>
                     <tbody>
                        <tr>
                           <td><i>Waarde</i></td>
                           <td><i>Omschrijving</i></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>vertegenwoordiger</b></td>
                           <td width="60%"></td>
                        </tr>
                        <tr>
                           <td width="40%"><b>klant</b></td>
                           <td width="60%"></td>
                        </tr>
                     </tbody>
                  </table>
                  </div>
               </div>
            </div>
      </div>
   </body>
</html>
