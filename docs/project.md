---
layout: page-with-side-nav
title: redoc
body_include: redoc-body.html
spec-url: https://raw.githubusercontent.com/VNG-Realisatie/klantinteracties/main/specificatie/contactmomenten/openapi.yaml
---

# Project

Hier worden artefacten gepubliceerd die horen bij het ontwikkelproject van de API-standaarden voor Klantinteracties.

## Online toelichting Klantinteracties 23 juni 2022

Op 23 juni is tijdens de 'Week van de dienstverlening' een korte toelichting gegeven bij de ontwikkelingen rondom de API-standaarden voor Klantinteracties.

### Presentatie

De tijdens de bijeenkomst getoonde [Powerpointpresentatie](./assets/project/20220623-presentatie-klantinteracties.pptx).

### Video-opname

De video-opname is niet publiek toegankelijk gepubliceerd, maar na inloggen beschikbaar via de [Pleio-omgeving bij de 'Week van de dienstverlening'](https://weekvandedienstverlening.pleio.nl/events/view/7bcb43f5-5773-4d9a-b98d-aa1fa413a37c/api-standaarden-voor-klantinteracties-wat-en-waarom-ook-alweer-en-wat-gaat-er-gebeuren).

### Q & A

_Onderstaande vragen zijn tijdens de bijeenkomst in de chat gesteld en achteraf (<span style="color:#000081">in donkerblauw</span>) beantwoord._

Qua definitie van klant: kan het niet ook een vestiging van een organisatie zijn?

<span style="color:#000081">Jazeker, maar een vestiging is wat mij betreft een onderdeel van een organisatie of een kenmerk van een persoon (in geval die namens zijn eenmanszaak handelt).</span>

Zijn meerdere mail-adressen mogelijk ? En zijn ook Social Media (Twitter/Facebook-accounts) mogelijk?

<span style="color:#000081">Zoals toegelicht zijn klantgegevens bedoeld als ‘default’ contactgegevens voor die klant. Voor gebruik tijdens specifieke interacties (een aanvraag bijvoorbeeld) kunnen afwijkende contactgegevens worden opgegeven. Deze gelden als kenmerk van die interactie, en niet als kenmerk van de klant. Als we dit patroon volgen is het vast kunnen leggen van één e-mailadres bij de klant volgens mij voldoende.
Voor het vastleggen van gebruikersnamen op sociale media van klanten zijn nog geen user stories ingediend. Als dat gewenst is, graag zo’n user story via https://github.com/VNG-Realisatie/klantinteracties/issues/new/choose :).</span>

Hoe vrij is de api in het zelf opnemen van elementen? welke vrijheid heeft de gemeente zelf?

<span style="color:#000081">De Klanten API omvat gegevens die (zoveel mogelijk) door de klant zelf (kunnen) worden verstrekt. De standaard is dus niet bedoeld voor het bijhouden van kenmerken of eigenschappen van de klant door de gemeente.</span>

[reactie bij opmerking hierboven] Om een standaard goed te kunnen laten werken is het juist niet de bedoelding om als gemeente eigen elementen toe te voegen. Dat wil niet zeggen dat een gemeente geen goede bijdragen kan hebben maar die zouden we dan graag in de standaard opnemen zodat andere gemeenten hier ook van kunnen profiteren.

<span style="color:#000081">Mee eens :)</span>

[reactie bij twee opmerkingen hierboven over ‘vrije kenmerken’] M.i. nog wel punt van overdenking want binnen verschillende domeinen zijn denk ik verschillende behoeften wat betreft 'klant+ gegevens'.

<span style="color:#000081">Dat denk ik ook. Daarom beperken we ons binnen de Klanten API-standaard tot contactgegevens en -voorkeuren. De behoeften daaromtrent zijn (naar mijn inschatting) domeinonafhankelijk.</span>

Ik denk dat het handig zou zijn om adres als lijsten te kunnen opgeven met een type aanduiding. Idem voor contactgegevens zoals e-mail, telefoonnummer, social media accounts, …

<span style="color:#000081">Voor adressen, social media-accounts en telefoonnummers lijkt me dit ook handig. Ik kan me bijvoorbeeld voorstellen dat het zinvol is om bijvoorbeeld een mobiel en een vast telefoonnummer vast te leggen. Voor e-mailadressen zie ik de noodzaak daarvoor niet meteen – ik kan zo snel ook geen voorbeelden bedenken van andere organisaties waar ik meerdere e-mailadressen kan opgeven om die in verschillende situaties te gebruiken. Een eventueel voorbeeld is welkom als user story :).</span>

[reactie bij opmerking hierboven] Je ziet ook vaak telefoon werk of telefoon privé.

<span style="color:#000081">Mee eens. Belangrijk hierbij op te merken is dat we een persoon die handelt namens zichzelf zien als een andere klant dan dezelfde persoon die handelt namens een organisatie – bijvoorbeeld omdat zij of hij daar werkt. Omdat ‘zakelijke’ nummers vaak ook privé worden gebruikt lijkt me het overigens alsnog nuttig om het mogelijk te maken zakelijke telefoonnummers vast te leggen. Teruggrijpend op de vraag hierboven zie ik dat nut voor e-mailadressen minder.</span>

In een DSO-verzoek kan de indiener ook afwijkende persoonsgegevens en correspondentiegegevens indienen. Hoe verhoudt dat zich tot de klanten-api?

<span style="color:#000081">Deze vraag is tijdens de bijeenkomst beantwoord en wordt in de video beantwoord vanaf minuut 16:00.</span>

De vraag is denk ik of het van belang is om In de klantregistratie vast te kunnen leggen dat een klant gemachtigde is namens iemand anders.

<span style="color:#000081">De Klanten API omvat gegevens die (zoveel mogelijk) door de klant zelf (kunnen) worden verstrekt. Machtigingsgegevens voldoen niet aan dat criterium. Bovendien ‘hangt’ zo’n machtiging aan een basisregistratiesubject, en zou die ook daar in de buurt moeten worden vastgelegd. Ten slotte loopt er een groot project rondom machtigen bij het ministerie van Binnenlandse Zaken en zou ik een oplossing voor dit – landelijke en niet gemeentelijke – probleem het liefst ook op dat niveau zien.</span>

[als vervolg op de vorige opmerking] M.i. is dit context-gerelateerd dwz niet voor een generieke klantenregistratie.

<span style="color:#000081">Mee eens dus :)</span>

"Iedereen die contact heeft/kan-hebben met de gemeente" is m.i. ruimer dan wat meestal met 'klant' wordt aangeduid. Bijv. wikipedia: "Een klant is de afnemer van een goed of dienst van een leverancier." Terminologie nog punt van aandacht dus...  

<span style="color:#000081">De gekozen definitie wijkt inderdaad wat af van hetgeen gebruikelijk is, daarom is die ook zo belangrijk. Eerder hebben we voorgesteld dat ‘klant’ ‘betrokkene’ bij ‘zaak’ vervangt in alle gevallen waar zo’n betrokkene niet voor de gemeente werkt. Dit betekent dat ook een persoon die niet de aanvraag heeft ingediend die heeft geleid tot een zaak, maar daarbij wel betrokken is (bijvoorbeeld omdat de zaak een bezwaar tegen een aan haar of hem verleende vergunning betreft), wordt opgevoerd als ‘klant’. Dit maakt de brede definitie noodzakelijk.</span>

Is in de tweede situatie [waarbij voor een klant geen identificerende gegevens worden vastgelegd] wel sprake van een klant, of alleen van NAW-gegevens bij het formulier van degene die dat formulier heeft ingediend?

<span style="color:#000081">Interessante vraag. Stel iemand doet een melding en wil op de hoogte gehouden worden van de behandeling daarvan. Die melding wordt geregistreerd als productaanvraag. Je kan in dit geval inderdaad twee routes kiezen:
1.	<span style="color:#000081">Contactgegevens worden vastgelegd bij de klant, de contactgegevens bij de bij de productaanvraag waarin die melding is geregistreerd blijft leeg.</span>
2.	<span style="color:#000081">Er ontstaat geen klant, de contactgegevens worden in de contactgegevens bij de bij de productaanvraag waarin die melding is geregistreerd.</span>
<span style="color:#000081">Het tweede is conceptueel zuiverder: het gaat hier immers om contactgegevens die alleen voor de duur van de interactie (kunnen) worden gebruikt: precies waar de contactgegevens bij de aanvraag voor bedoeld zijn. Aan de andere kant kan ik me ook voorstellen dat deze route vraagt om het kunnen vastleggen van meer contactgegevens bij de productaanvraag.</span>

<span style="color:#000081">Een andere consequentie van de tweede optie is dat het niet langer logisch lijkt de relatie tussen een zaak en iemand die bij die zaak betrokken is, maar niet aanleiding heeft gegeven tot het starten daarvan als klant te registreren. Diens contactgegevens zou je dan immers eerder op de relatie persoon – zaak verwachten.</span>

<span style="color:#000081">Het lijkt me noodzakelijk om dit in een aantal casussen verder uit te werken.</span>

Patroon is dus: Klant ophalen (bsn) -> bestaat niet? aanmaken; bestaat wel aanvullen/gegevens ophalen.

<span style="color:#000081">Klopt.</span>

De situatie van meerdere klanten wil je in een CRM systeem helemaal vermijden! Zo niet kan je geen "totaal" klantbeeld maken.

<span style="color:#000081">Helemaal mee eens. Dubbele ‘geïdentificeerde’ klanten zijn inderdaad ongewenst (en komen als het goed is ook niet voor). Maar als je een klant niet identificeert, kan je niet weten of er sprake is van een dubbele klant, of iemand die je nog helemaal niet kent. Vergelijk het met het als ‘gast’ afrekenen bij een webwinkel waar je ook een account hebt. De winkel kan op basis van naam en adres wel aannemen dat de bestelling is gedaan door iemand met dezelfde naam en adres in een account, maar niet met voldoende zekerheid om die bestelling ook daadwerkelijk aan dat account te kunnen koppelen.</span>

[reactie bij opmerking hierboven] Dat lukt je niet als de klant zich niet identificeert (denk aan het inloggen op een site waar je iets wil bestellen).

<span style="color:#000081">Precies.</span>

Het email-adres is ook context-afhankelijk, naast wellicht een defauilt-mailadres.

<span style="color:#000081">Klopt. Dat zou je ook moeten kunnen ‘overrulen’ voor gebruik tijdens een specifieke interactie.</span>

Mag een zaakafhandelcomponent dan een 'niet herbruikbaar' klant record aanmaken om de contact gegevens in de context van een zaak in te kunnen opslaan?

<span style="color:#000081">Ja, dat zou die component volgens het voorstel hierboven mogen doen. Maar wellicht moeten we daar naar aanleiding van de twee hierboven beschreven routes nog eens naar kijken.</span>

Als de klant zich voor één product zeg Vergunning identificeert en bij een melding openbare ruimte NIET. Wat ziet hij dan terug in zijn mijn-omgeving ? Alleen de vergunning, of ook de Melding Openbare ruimte ?

<span style="color:#000081">Deze vraag is tijdens de bijeenkomst beantwoord en wordt in de video beantwoord vanaf minuut 31:45.</span>

[reactie bij opmerking hierboven] lijkt mij alleen die hij met identificatie heeft gedaan. Die andere  kan niet :)

<span style="color:#000081">Klopt!</span>

Waar blijft het e-mailadres in ZGW API als het e-maildres specifiek is voor de zaak?

<span style="color:#000081">Dat zou moeten worden als kenmerk van (en bij) de zaak.</span>

[reactie bij opmerking hierboven]  Rutten, Maarten vermoed dat je dat vastlegt op de relatie tussen Klant en Zaak als zijnde zaakspecifiek voorkeurskanaal

<span style="color:#000081">Voorkeurskanaal zou ik contactgegevens noemen :) – maar klopt!</span>

DigiD is geen must voor identificatie. Er zijn ook andere mogelijkheden van identificatie: denk aan telefoonnummer, social media ids, ...

<span style="color:#000081">Telefoonnummers en social media-id’s zijn veelal bij meerdere mensen bekend, en op zichzelf geen goede middelen om iemands identiteit vast te stellen en tegen te authentiseren. Tegelijkertijd is vragen in te loggen via DigiD of met een identiteitsbewijs fysiek langs te komen niet altijd haalbaar of gewenst. Waar nu precies de grens ligt tussen bescherming tegen mogelijke ongeoorloofd(e) handelen of gegevensverstrekking en het zo laagdrempelig mogelijk aanbieden van producten en diensten is een heel interessant vraagstuk dat ook buiten de toepassing van de Klanten API relevant is en nader onderzoek verdient.</span>

[reactie bij opmerking hierboven] Als je deze kan koppelen aan de klant, kan je altijd een klantbeeld opbouwen. Natuurlijk rekening houdend met AVG en wetgeving

<span style="color:#000081">Koppelen aan een (bestaande, geïdentificeerde) klant moet zeker kunnen, maar die klantgegevens verstrekken van persoonlijke informatie op basis van (alleen) het noemen van een telefoonnummer of social media-id lijkt me niet haalbaar en gewenst.</span>

Ik ben bang dat we niet gaan toekomen aan wat mijn belangrijkste vraag voor deze sessie was:
Komen er ook documentrelaties? Opdat vastgelegd kan worden welke documenten in welke contactmoment zijn ingediend of verzonden

<span style="color:#000081">Daar is een (nu gesloten) user story voor: https://github.com/VNG-Realisatie/klantinteracties/issues/138. Functionaliteit lijkt bij nader inzien praktisch. Aanvullingen met argumentatie daarvoor zijn welkom.</span>

Onderscheid van productaanvragen API t.o.v. ZGW API's mag wat mij betreft duidelijker. Ik zie niet heel snel de toegevoegde waarde. Maar dat kan ook aan mij liggen.

<span style="color:#000081">Ligt niet aan jou. We moeten dit beter beschrijven. Staat op de planning, maar we nemen eerst de vragen rondom klanten op.</span>

[reactie bij opmerking hierboven] Productaanvraag is in terminologie van de klant. Zaak is ambtelijke term van de gegevensverzameling en procesafhandeling voor het leveren van het formele product. Kan 1:1 of 1:N of N:N zijn

<span style="color:#000081">Precies, dat is een heel mooi begin van het antwoord :)</span>

Betreft naamgeving 'productaanvraag': blijf ik een lastige vinden. Persoonlijk vind ik een klantvraag of een verzoek meer passend. Een verzoek is iets wat de klant vraagt aan de gemeente, bv. wat zijn de openingstijden (informatieverzoek), maar ook een productverzoek(aanvraag)

Vanuit sociaal domein is het een hulpvraag, waarbij pas bij het ondersteuningsplan en inzetten van instrumenten er sprake is van productaanvragen.

Naamgeving hierin is dus erg lastig en wellicht zelfs domeinspecifiek.

<span style="color:#000081">Goede suggesties. We gaan hier nog eens naar kijken.</span>

Naast productaanvragen ook ongevraagde (of uit initiatief gemeente) producten. bekendste de woz aanslag. in kader van integraal klantbeeld. hoe nemen we deze qua klantbeeld?

<span style="color:#000081">Als zaak :). Maar vanuit het oogpunt van consistentie zou ik die zaak dan ophangen aan het product dat met die zaak wordt geleverd. Dan bied je de klant dus een overzicht van ‘aangevraagde’ en ‘niet-aangevraagde’ producten.</span>
