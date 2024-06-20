# UB2030 | Toekomst van Decentralized Science | GPT4 Samenvatting

## Management Samenvatting

- **Gast**: Professor Philipp Koelinger, econoom aan de Vrije Universiteit Amsterdam en oprichter van DeSci Labs en DeSci Foundation.
- **Onderwerp**: Decentralised Science (De-Sci) en de transformatie naar een open wetenschap ecosysteem voor FAIR (Findable, Accessible, Interoperable, Reusable) onderzoek.
- **Doel**: Transparant en repliceerbaar onderzoek mogelijk maken en beloningen bieden voor Open Science praktijken.

### Science is facing a Crisis

- **Uitdagingen**: Diepgewortelde problemen in wetenschappelijke publicatie en infrastructuur, zoals verouderde publicatietechnologie en beperkte toegankelijkheid van data.
- **Economische impact**: Hoge kosten door inefficiënties en niet-FAIR data, wat wetenschappelijke vooruitgang belemmert.

### Towards a Research Record of Versions

- **Huidige beperkingen**: Statische PDF's en minimale metadata zonder adequate infrastructuur voor data en code.
- **Oplossing**: Digitale onderzoeksobjecten die FAIR zijn, interactief en dynamisch, ondersteund door een open source infrastructuur.

### The interactive scientific paper of the future

- **Innovatie**: Interactieve wetenschappelijke papers die kernresultaten koppelen aan onderliggende data en code, en updates en bijdragen van derden mogelijk maken.

### DOI's are not persistent identifiers

- **Problemen met DOI's**: Onbetrouwbare resolutie (terug halen van het artikel aan de hand van een identifier) en inefficiënties in handmatige updates, wat hun rol als persistente identifiers ondermijnt.

### Content addressing based on hashes

- **Oplossing**: Gebruik van cryptografische hashes voor betrouwbare en unieke identificatie van content, wat problemen met linkrot en inhoudsverplaatsing oplost.

### DeSci Nodes

- **Publicatieprotocol**: Voor rijke digitale onderzoeksobjecten met permanente identifiers, gedistribueerd via een peer-to-peer infrastructuur en bijgehouden op een blockchain.
- **Voordelen**: Dynamische en interoperabele onderzoeksobjecten met versiecontrole en persistente identifiers.

### Provenance

- **Blockchain**: Updates worden vastgelegd in een openbaar grootboek, toegankelijk voor iedereen, wat de herkomst van onderzoeksobjecten traceerbaar maakt.

### Distribution

- **Redundante opslag**: Metadata wordt wereldwijd opgeslagen op verschillende servers, wat bescherming biedt tegen gegevensverlies en betaalmuren.

### Decentralized Persistent Identifiers (dPID)

- **Unieke adressen**: dPIDs bieden unieke en gedetailleerde verwijzingen naar onderzoeksobjecten en hun componenten.
- **Mensvriendelijk**: dPIDs combineren gebruiksvriendelijkheid, veiligheid en decentralisatie.

### Operations on research objects

- **Nieuwe mogelijkheden**: Metadata resolutie, gedecentraliseerde compute, importeren van bronnen en toevoegen van attestaties met dPIDs.

### Decentralized data storage

- **IPFS-systeem**: Gegevens worden redundantly en kostenefficiënt opgeslagen, met mogelijkheden voor beveiligde opslag en lange termijn archivering.

### FAIR-enabling metadata

- **Automatische generatie**: Minimale FAIR-metadata wordt automatisch gegenereerd vanuit onderzoeksobjecten zonder extra inspanning van de onderzoeker.

### Open-state repository for FAIR interoperable research objects

- **Volledige stack**: Gescheiden data- en applicatielagen voor het beheren en delen van onderzoeksobjecten.

### DEMO: DeSci Nodes

- **Gebruiksvriendelijkheid**: Browserinterface biedt toegang tot artikelen, code, data en annotaties, met functies voor versiegeschiedenis en attestaties (badges).

### Reporting: User Statistics on EtherScan

- **Transparantie**: Publiek toegankelijke metadata en gebruikersstatistieken beschikbaar via EtherScan.

### Open Source Software

- **Toegankelijkheid**: Broncodes en componenten zijn openbaar beschikbaar op GitHub, ondersteund door een actieve ontwikkelaarsgemeenschap.

### Gateways - Content Curation and Branding

- **Contentcuratie en branding**: Belangrijk voor het beheer van wetenschappelijke publicaties, mogelijk gemaakt door gateways die content surfacen en beheren.

### Brainstorm: FAIRpilot project with SURF

- **Samenwerkingsvoorstel**: Testen van de nieuwe infrastructuur met SURF om data FAIR en open te maken, met mogelijkheden voor een eigen gateway door SURF.

Deze samenvatting geeft een overzicht van de innovatieve benadering van DeSci Labs om wetenschap transparanter, toegankelijker en efficiënter te maken door gebruik van gedecentraliseerde technologieën.


## Uitgebreide samenvatting - DeSci a Decentralised Open Science Ecosystem for FAIR research

- **UB2030**: De podcast "UB2030" richt zich op de innovaties binnen de universiteitsbibliotheek als gevolg van technologische en beleidsmatige veranderingen in hoger onderwijs en onderzoek.
- **Beschrijving van de bonus track**: In deze bonus track spreekt professor Philipp Koelinger over zijn startup De-Sci Labs en De-Sci Foundation.
- **Wat is De-Sci?**: De-Sci staat voor Decentralised Science, een concept dat wetenschap wil transformeren naar een open wetenschap ecosysteem.
- **Doel van De-Sci**: Het doel is om onderzoek transparant en volledig repliceerbaar te maken.
- **Beloning voor Open Science praktijken**: Het ecosysteem beloont degenen die bijdragen met attestaties voor Open Science praktijken.

### Introduction

Hier zijn de belangrijkste punten van de introductie:

- **Introductie door Philipp Koellinger**: Philipp Koellinger stelt zichzelf voor als professor in de economie aan de Vrije Universiteit in Amsterdam, met een achtergrond in interdisciplinair onderzoek, sociale wetenschappen, genetica, big data, en open wetenschap praktijken.
- **Oprichting van DeSci Labs en DeSci Foundation**: Twee jaar geleden richtte hij DeSci Labs en DeSci Foundation op met als doel de manier waarop wetenschap wordt gepubliceerd en gefinancierd te verbeteren door middel van technologie.
- **Problemen in de wetenschap**: Philipp begint met het kort vermelden van de huidige problemen in de wetenschap die moeten worden aangepakt.
- **Oplossingen die worden ontwikkeld**: Vervolgens bespreekt hij de oplossingen die ze aan het ontwikkelen zijn, waaronder interoperabele persistente identifiers gebaseerd op content-addressed data storage.
- **Decentrale open data-opslag**: Hij zal ook praten over decentrale open data-opslag en interoperabele dynamische FAIR digitale onderzoeksobjecten, die DeSci nodes worden genoemd.
- **Beta testing van de applicatie**: Een applicatie die twee maanden geleden in bèta is gegaan en al wordt gebruikt, wordt besproken.
- **Content curation en branding**: Als er nog tijd over is, zal Philipp kort ingaan op de concepten van content curation en branding met behulp van gateways en brainstormen over een mogelijke pilot met SURF.

### Science is facing a Crisis

Hier zijn de belangrijkste punten van de sectie over de crisis in de wetenschap:

- **Systemische uitdagingen in de wetenschap**: Wetenschap kampt met diepgewortelde problemen op systemisch niveau die de vooruitgang belemmeren.
- **Verouderde publicatietechnologie**: Huidige wetenschappelijke publicatietechnologie is gebaseerd op concepten uit de 17e eeuw en is niet aangepast aan de moderne eisen van wetenschap.
- **Exponentiële groei van wetenschappelijke data**: Er bestaat momenteel ongeveer drie zetabytes aan wetenschappelijke data, wat enorme kosten en infrastructuurproblemen met zich meebrengt.
- **Beperkte toegankelijkheid van data**: Een groot deel van de wetenschappelijke data is niet toegankelijk voor het publiek of onderzoekers, wat de vooruitgang belemmert.
- **Kosten van datatoegang**: Voorbeeld van een onderzoeker aan Harvard en MIT die hoge kosten ondervond door veelgevraagde data, wat leidde tot afsluiting van de toegang tot de data.
- **Niet-FAIR data**: Veel data voldoet niet aan de FAIR-principes (Findable, Accessible, Interoperable, Reusable), wat leidt tot aanzienlijke economische kosten en inefficiënties.
- **Problemen met data-silo's en commerciële exploitatie**: Huidige internettechnologie creëert data-silo's die commerciële exploitatie mogelijk maken, wat nadelig is voor onderzoekers en de wetenschap.
- **Slechte prikkels en kwantitatieve maatstaven**: Problematische kwantitatieve maatstaven voor wetenschappelijke productiviteit en een gebrek aan infrastructuur voor repliceerbaarheid en reproduceerbaarheid creëren perverse prikkels die bijdragen aan een crisis van reproduceerbaarheid.

Deze problemen ondermijnen het vertrouwen in de wetenschap en vertragen de wetenschappelijke vooruitgang aanzienlijk.

### Towards a Research Record of Versions

Hier zijn de belangrijkste punten van de sectie over de verschuiving naar een onderzoeksverslag van versies:

- **Huidige kennisinfrastructuur**: De huidige wetenschappelijke publicatiestructuur is een digitale analoog van de drukpers met PDF's achter betaalmuren en minimale metadata.
- **Gebrek aan infrastructuur voor data en code**: Er is geen echte infrastructuur voor data, code of reproduceerbaarheid, waardoor belangrijke wetenschappelijke artefacten vaak verloren gaan, verborgen zijn of verspreid liggen.
- **Beperkte interactiemogelijkheden**: De huidige structuur biedt zeer beperkte mogelijkheden voor de onderzoekscommunity of het publiek om met data en code te interageren en deze opnieuw te gebruiken.
- **Noodzaak voor digitale onderzoeksobjecten**: Er moet een verschuiving plaatsvinden naar digitale onderzoeksobjecten die FAIR (Findable, Accessible, Interoperable, Reusable) zijn en interactief en dynamisch zijn, waardoor nieuwe manieren van delen en bijdragen mogelijk worden.
- **Open source infrastructuur**: De infrastructuur die deze verschuiving ondersteunt, moet open source zijn, zonder betaalmuren, met lees- en schrijfrechten voor iedereen, zonder datasilo's of vendor lock-in.

Deze veranderingen zijn essentieel om wetenschappelijk onderzoek toegankelijker, interactiever en reproduceerbaarder te maken.

### The interactive scientific paper of the future

Hier zijn de belangrijkste punten van de sectie over de interactieve wetenschappelijke paper van de toekomst:

- **Herdefiniëring van het wetenschappelijke paper**: In plaats van statische PDF's, denkt men aan interactieve wetenschappelijke papers die kernresultaten koppelen aan de onderliggende data en code.
- **Verifieerbaarheid van resultaten**: Lezers moeten direct de data en code kunnen controleren en uitvoeren om de resultaten in de figuren of tabellen van het paper te verifiëren.
- **Evoluerende papers**: Papers moeten updates over tijd mogelijk maken, waarbij auteurs samenwerken en verbeteringen kunnen aanbrengen.
- **Bijdragen van derden**: Het moet mogelijk zijn voor andere wetenschappers en data stewards om verbeteringen en aanvullingen te suggereren en toe te voegen aan de paper.
- **Samenstelbare auteurschapstabellen**: Gebruik van git-principes waarbij iedereen suggesties kan doen die vervolgens openbaar beschikbaar zijn en door de originele auteurs kunnen worden geaccepteerd, resulterend in een nieuwe versie van het onderzoeksobject met vermelding van nieuwe bijdragers.

Deze veranderingen maken wetenschappelijke papers dynamisch, interactief en beter verifieerbaar, wat de wetenschappelijke vooruitgang zal bevorderen.

### DOI's are not persistent identifiers

Hier zijn de belangrijkste punten van de sectie over waarom DOI's geen persistente identifiers zijn:

- **Belang van persistente identifiers**: Persistente identifiers zijn cruciaal voor het behouden en terugvinden van wetenschappelijke records over tijd.
- **Problemen met huidige internetarchitectuur**: URL's zijn geen persistente identifiers vanwege linkrot en inhoudsverplaatsing.
- **Huidige oplossing: DOI's**: DOI's (Digital Object Identifiers) zijn bedoeld om deze problemen op te lossen door als opzoektafel te fungeren, waar de uitgever de DOI aan een URL koppelt.
- **Praktische problemen met DOI's**: Ongeveer 50% van alle DOI's leidt niet consistent naar de juiste bron, met variërende resultaten afhankelijk van de aanvraagmethode en netwerkomgeving.
- **Inconsistentie en inefficiëntie**: Handmatige updates van DOI's door uitgevers zijn inefficiënt en kostenintensief, wat leidt tot inconsistente en onbetrouwbare resultaten.

Deze problemen tonen aan dat DOI's technisch gezien noch persistent noch unieke identifiers zijn, wat hun betrouwbaarheid ondermijnt.


### Content addressing based on hashes

Hier zijn de belangrijkste punten van de sectie over content addressing gebaseerd op hashes:

- **Oplossing vanuit het gedecentraliseerde web**: Het probleem van linkrot en inhoudsverplaatsing kan worden opgelost met technologieën uit het gedecentraliseerde web, namelijk content address data storage.
- **Cryptografische hashes**: Deze technologie maakt gebruik van cryptografische hashes om specifieke content te identificeren.
- **Wat is een cryptografische hash?**: Een cryptografische hash is een wiskundige functie die een string van willekeurige lengte omzet in een string van vaste lengte. Het is een eenrichtingsfunctie die het onmogelijk maakt om de originele input te reconstrueren vanuit de output.
- **Algoritmen voor hashes**: Een veelgebruikt algoritme is SHA-256, ontwikkeld door de NSA, dat een 64 hexadecimale string genereert voor elke input.
- **Unieke hashes**: Zelfs de kleinste verandering in de input (bijvoorbeeld een enkel woord of een komma) resulteert in een volledig andere hash, waardoor hashes statistisch uniek zijn.
- **Betrouwbaarheid en uniciteit**: De kans dat twee verschillende inhoudsobjecten dezelfde hash hebben, is praktisch nul vanwege het enorme aantal mogelijke hashes (10^77).
- **Controle van de inhoud**: Nadat een hash is gebruikt om toegang te krijgen tot de content, kan de inhoud worden gecontroleerd met een hash calculator om te bevestigen dat de inhoud overeenkomt met het adres.
- **Immuun voor linkrot en inhoudsverplaatsing**: Dit systeem van gegevensopslag voorkomt de problemen van linkrot en inhoudsverplaatsing, die veelvoorkomende problemen zijn in de huidige internetinfrastructuur.

Deze technologie biedt een robuuste oplossing voor het behoud en de betrouwbaarheid van digitale inhoud.


### DeSci Nodes

Hier zijn de belangrijkste punten van de sectie over DeSci Nodes:

- **Publicatieprotocol voor digitale onderzoeksobjecten**: DeSci Nodes creëren een publicatieprotocol voor rijke digitale onderzoeksobjecten met permanente identifiers, die geïndexeerd en doorzoekbaar zijn op een openbaar grootboek.
- **Componenten van onderzoeksobjecten**: Deze onderzoeksobjecten kunnen bestaan uit verschillende componenten zoals manuscripten, data en code, waarbij elk bestand een unieke hash krijgt die direct uit de content wordt gegenereerd.
- **Root Node**: Het onderzoeksobject heeft een root node met twee identifiers: een hash die een combinatie is van de hashes van de afzonderlijke componenten en een unieke willekeurige identifier.
- **Publicatie en distributie**: Wanneer auteurs klaar zijn om hun werk te publiceren, drukken ze op de publicatieknop, waarna het werk wordt gedistribueerd naar een gedecentraliseerde peer-to-peer infrastructuur en een invoer wordt geschreven in een blockchain smart contract.
- **Toevoegen en bijwerken van componenten**: Bij het toevoegen van nieuwe componenten, zoals een video, krijgt elke component een unieke hash en wordt de hash van de root node bijgewerkt, met een nieuwe invoer op de ledger. Bij updates, zoals een nieuwe versie van een manuscript, gebeurt hetzelfde proces.
- **Voordelen van het systeem**: Dit gedecentraliseerde peer-to-peer systeem maakt het mogelijk om het wetenschappelijke record te upgraden van statische manuscripten naar dynamische, interoperabele onderzoeksobjecten met persistente identifiers en versiecontrole.

Dit systeem biedt een robuuste en dynamische manier om wetenschappelijke werken te beheren en toegankelijk te maken.

### Provenance

Hier zijn de belangrijkste punten van de sectie over Provenance:

- **Publieke grootboek en blockchain**: Blockchains fungeren als openbare grootboeken waarin updates worden vastgelegd en toegankelijk zijn voor iedereen.
- **Metadata op blockchain**: De ingevoerde gegevens geven aan wie de update heeft gedaan, wanneer het is gebeurd, de huidige ID en unieke identifier van het onderzoeksobject.
- **Toegankelijkheid van metadata**: Zowel computerprogramma's als mensen kunnen de metadata opvragen en gebruiken.

### Distribution

Hier zijn de belangrijkste punten van de sectie over Distribution:

- **Redundante opslag**: Metadata wordt opgeslagen op verschillende servers en locaties door diverse opslagproviders, waarbij de blockchain consensusmechanismen ervoor zorgen dat dezelfde versie overal wordt opgeslagen.
- **Voordelen van blockchain-opslag**: Het protocol biedt opslagredundantie zonder mogelijkheid tot afsluiting of betaalmuren, in tegenstelling tot de huidige infrastructuur die data verkoopt tegen hoge prijzen.

### Decentralized Persistent Identifiers (dPID)

Hier zijn de belangrijkste punten van de sectie over dPIDs:

- **Unieke adressen voor onderzoeksobjecten**: dPIDs bieden unieke adressen voor elk onderzoeksobject, waarmee zowel de nieuwste als eerdere versies en specifieke onderdelen van het object kunnen worden gerefereerd.
- **Gedetailleerde verwijzingen**: Mogelijkheid om specifieke onderdelen zoals datasets, codebestanden of zelfs specifieke delen daarvan te adresseren.
- **Twee formaten van dPIDs**: Een lang, cryptografisch hash-formaat voor machines en een kort, mensvriendelijk formaat.
- **Oplossing voor Zooko's Triangle**: dPIDs combineren de drie eigenschappen van Zooko's Triangle: mensvriendelijkheid, veiligheid en decentralisatie, wat volgens Aaron Schwartz theoretisch mogelijk is.

Deze technologische innovaties verbeteren de toegankelijkheid, veiligheid en interoperabiliteit van wetenschappelijke gegevens aanzienlijk.

### Operations on research objects

Hier zijn de belangrijkste punten van de sectie over operaties op onderzoeksobjecten:

- **Metadata resolutie**: dPIDs maken het mogelijk om metadata via het HTTP-protocol op te vragen, wat real-time analyses en verbindingen tussen verschillende onderzoeksobjecten mogelijk maakt.
- **Gedecentraliseerde compute**: dPIDs kunnen worden gebruikt om code naar de server te sturen waar de dataset zich bevindt, wat efficiënte verwerking van grote datasets mogelijk maakt zonder ze te verplaatsen.
- **Importeren van bronnen**: dPIDs kunnen specifieke onderdelen van onderzoeksobjecten direct in lokale computervarianten importeren, zoals in Jupyter notebooks.
- **Attestaties toevoegen**: dPIDs kunnen worden gebruikt om kwaliteitsverklaringen (attestaties) aan onderzoeksobjecten toe te voegen, zoals beschikbaarheid van data, code of peer review status.

### Decentralized data storage

Hier zijn de belangrijkste punten van de sectie over gedecentraliseerde gegevensopslag:

- **Twee lagen systeem**: Het DeSci node systeem heeft een privé staging gebied voor auteurs en een gedecentraliseerd peer-to-peer netwerk genaamd IPFS voor publicatie.
- **Gegevensredundantie**: Publicaties worden opgeslagen in minstens vijf identieke kopieën, verspreid over drie verschillende opslagproviders in verschillende landen en continenten, wat bescherming biedt tegen gegevensverlies en vendor lock-in.
- **Open source deelname**: Iedereen kan deelnemen aan het IPFS-systeem, van individuele gebruikers tot professionele datacenters.
- **Beveiligde opslag**: Mogelijkheid om gevoelige gegevens privé op te slaan met gereguleerde toegang binnen het IPFS-systeem.
- **Kostenbesparingen**: IPFS biedt opslag tegen zeer concurrerende prijzen, tot 95% goedkoper dan commerciële oplossingen.
- **Sponsorship programma**: Voor grote en waardevolle datasets biedt de DeSci Foundation een sponsorprogramma voor langdurige archivering.

Deze innovaties verbeteren de opslag, toegankelijkheid en financiële haalbaarheid van wetenschappelijke gegevens aanzienlijk.


### FAIR-enabling metadata

Hier zijn de belangrijkste punten van de sectie over FAIR-enabling metadata:

- **FAIR-principes**: FAIR staat voor Findable, Accessible, Interoperable en Reusable.
- **Twee belangrijke bouwstenen**: Nodig voor FAIR zijn persistente identifiers en machineleesbare metadata.
- **Oplossingen en uitdagingen**: Huidige oplossingen zoals gecontroleerde vocabulaires en ontologieën zijn vaak niet schaalbaar en brengen extra bureaucratie en belasting voor onderzoekers met zich mee.
- **Samenwerking met Gopher Foundation**: Ontwikkeling van een minimale hoeveelheid FAIR-metadata die automatisch wordt gegenereerd vanuit de onderzoeksobjecten, zonder extra inspanning van de onderzoeker.

### Open-state repository for FAIR interoperable research objects

Hier zijn de belangrijkste punten van de sectie over een open-state repository voor FAIR interoperabele onderzoeksobjecten:

- **Volledige stack voor wetenschappelijk onderzoek**: Scheiding tussen de datalaag (IPFS-protocol) en de applicatielaag (DeSci Nodes applicatie).
- **Datalaag**: Onderzoeksgegevens worden opgeslagen en openbaar beschikbaar gesteld via het IPFS-protocol.
- **Applicatielaag**: Mogelijkheid om onderzoeksobjecten te creëren, bij te werken, te bekijken en ermee te interacteren.

### ... with compute integration

Hier zijn de belangrijkste punten van de sectie over integratie van compute:

- **Gedecentraliseerde compute**: Mogelijkheid om berekeningen uit te voeren op servers waar de data al is opgeslagen, wat reproduceerbaarheidstests en onderzoek mogelijk maakt zonder data te verplaatsen.
- **Registratielaag**: Indexeren van de recente versie van onderzoeksobjecten op een openbaar grootboek, cryptografisch verifieerbaar.
- **D PID systeem**: Interactie met onderzoeksobjecten en het ophalen van metadata.

### ... and shortened, human adapted PID's

Hier zijn de belangrijkste punten van de sectie over verkorte, mensvriendelijke PID's:

- **Toekomstige indexeringslaag**: Gebruik van GraphQL Indexers om real-time data-analyse mogelijk te maken op onderzoek in de open-state repository.

Deze innovaties zorgen voor verbeterde toegankelijkheid, efficiëntie en reproduceerbaarheid van wetenschappelijke gegevens en onderzoek.

### DEMO: DeSci Nodes

Hier zijn de belangrijkste punten van de sectie over de demonstratie van DeSci Nodes:

- **Beta testing van DeSci Nodes app**: De applicatie is momenteel in bèta en wordt getest door wetenschappers zoals NASA-programma-officier Megan Ansel.
- **Browser interface**: De interface biedt de mogelijkheid om door artikelen te scrollen en deze te downloaden, met een menu aan de rechterkant voor toegang tot andere componenten van het onderzoeksobject.
- **Verkenning van code en data**: Gebruikers kunnen door de geüploade code en datasets bladeren en deze specifiek adresseren en downloaden.
- **Interactie en annotaties**: Annotaties linken figuren aan de onderliggende data en code, en gebruikers kunnen deze figuren reproduceren door de code op de dataset uit te voeren.
- **Versiegeschiedenis en credits**: De applicatie toont de versiegeschiedenis van het onderzoeksobject, de bijdragen van verschillende personen en sponsoren.
- **Attestaties**: Onderzoeksobjecten kunnen attestaties krijgen die bepaalde kwaliteitskenmerken verifiëren, zoals samenwerking tussen auteurs en computational reproducibility, uitgegeven door vertrouwde entiteiten zoals de DeSci Foundation.

Deze functionaliteiten maken DeSci Nodes een krachtig hulpmiddel voor het beheren, verifiëren en delen van onderzoeksobjecten.

### Reporting: User Statistics on EtherScan

Hier zijn de belangrijkste punten van de sectie over gebruikersstatistieken op EtherScan:

- **Publiek toegankelijke metadata**: Het systeem creëert een openbaar record van gebruikersstatistieken.
- **Onderzoeksobjecten als tokens**: Elk onderzoeksobject is een token dat door een specifieke gebruiker wordt gemaakt, vertegenwoordigd door het wallet-adres.
- **Inzichten via EtherScan**: EtherScan toont hoeveel DeSci nodes zijn gepubliceerd, door hoeveel gebruikers en hoeveel nodes elke gebruiker heeft gecreëerd.

### Open Source Software

Hier zijn de belangrijkste punten van de sectie over open source software:

- **Open source project**: Alle broncodes zijn toegankelijk op GitHub bij DESI Labs.
- **Transparantie en gemeenschap**: Het DPID-systeem en andere componenten blijven openbaar, met een groeiende en actieve gemeenschap van ontwikkelaars.

Deze secties benadrukken de transparantie en toegankelijkheid van DeSci nodes, evenals de betrokkenheid van een actieve ontwikkelaarsgemeenschap.

### Gateways - Content Curation and Branding

Hier zijn de belangrijkste punten van de sectie over gateways voor contentcuratie en branding:

- **Belang van contentcuratie en branding**: Altijd belangrijk geweest in wetenschappelijke publicatie en zal in de toekomst nog belangrijker worden.
- **Proces van contentcuratie**: Kan plaatsvinden op persoonlijk niveau (whitelist gebruikers) of op inhoudsniveau (redactionele beslissingen).
- **Combineren van curatiemechanismen**: Mogelijkheid om zowel gebruikerswhitelisting als inhoudsniveau curatie te combineren voor een gereviewed repository.
- **Verschillende typen gateways**: 
  - **Inhoudsniveau curatie zonder whitelisting**: Functie als een tijdschrift of preprint server met lichte review functies.
  - **Whitelisting zonder inhoudsniveau curatie**: Functioneert als een institutionele preprint server die automatisch alles weergeeft wat vertrouwde gebruikers creëren.
  - **Geen curatie of whitelisting**: Gateway die toegang biedt tot alle nodes.

### Gateway functions

Hier zijn de belangrijkste punten van de sectie over gateway functies:

- **Weergave van content**: Surfaceert content van de open state repository via een eigen website.
- **Controleren van DPID prefix**: Gateways beheren hun eigen DPID prefix, bijvoorbeeld dpd.org/slash, voor branding en interface controle.
- **Branded Node Viewer**: Mogelijkheid voor branded weergave van PDF-viewers en andere content.
- **Attestaties en permissiebeheer**: Gateways kunnen attestaties verstrekken en gebruikersrechten beheren, zoals toegang tot edge computing en grote data-opslagplannen.

### Gateways - Frontend and Dashboard

Hier zijn de belangrijkste punten van de sectie over frontend en dashboard van gateways:

- **Frontend**: Website van de instelling waar Nodes kunnen worden vastgepind en weergegeven.
- **Backend dashboard**: Beheert curatiemechanismen, analytics, attestaties en integraties met andere softwaresystemen.

### Brainstorm: FAIRpilot project with SURF

Hier zijn de belangrijkste punten van de sectie over het FAIR-pilotproject met SURF:

- **Waardering voor SURF**: SURF's infrastructuur wordt enorm gewaardeerd door onderzoekers.
- **Pilot project voorstel**: Testen van de nieuwe infrastructuur door data van SURF te spiegelen en deze FAIR en open te maken.
- **Potentiële samenwerking**: Identificeren van datasets, samenwerken met onderzoekers om deze reproduceerbaar en openbaar te maken.
- **Toekomstige gateway mogelijkheden**: SURF kan een eigen gateway runnen om data FAIR en interoperabel te publiceren, in samenwerking met universiteiten en uitgevers.

Deze secties belichten de mogelijkheden en voordelen van gateways voor contentcuratie, branding en samenwerking binnen de wetenschappelijke gemeenschap.
