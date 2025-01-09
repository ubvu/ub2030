Prompt: Maak een samenvatting van de volgende sectie van het transcript, doe het in de puntsgewijze stijl waarbij de belangrijkste punten worden uitgelicht (vetgedrukt) gevolgd door een dubbele punt en een korte uitleg, introduceer de lijst met punten met een korte zin en sluit deze lijst af met een concluderende zin. Vaak is de input van het transcript te groot om in een keer te verwerken. Vraag de gebruiker om het op te knippen in kleinere delen, waarbij de samenvatting wordt gegenereerd op basis van het geheel. Herhaal de kop van de sectie in het antwoord. Vraag na elk deel of er nog een deel volgt, of dat dit het laatste deel was.

Input: ub2030-??-???-transcript.md

Output: ub2030-??-???-gpt4-step1-summary.md

-------

Prompt: Maak een beknopte Management Samenvatting van de uitgebreidere samenvatting van het transcript. 
Start met heading ## Management Samenvatting 
Beschrijf daar onder in een aantal paragrafen wie de **gasten** zijn, hun _rol_ binnen hun _organisatie_, wat het **onderwerp** is dat is besproken, wat de **kernpunten** zijn voor de _toekomst perspectieven_ en voor de _conclusies_.  

Input: ub2030-??-???-transcript.md

Output: append to >> ub2030-??-???-transcript.md

-------

Prompt: Extraheer uit de volgende samenvatting het lonkende toekomstperspectief:

Input: ub2030-??-???-gpt4-step1-summary.md

Output: ub2030-??-???-gpt4-step2-perspective.md

-------

Prompt: Gebruik het volgende lonkende toekomstperspectief van de universiteitsbibliotheek, en plaats het in een verhalend scenario:

Input: ub2030-??-???-gpt4-step2-perspective.md

Output: ub2030-??-???-gpt4-step2b-story_scenario.md

-------

Prompt: Welke vervolgstappen je kunnen beschrijven die op de korte, midden en lange termijn nodig zijn om het lonkende perspectief van de volgende kernpunten te bereiken?
of
Prompt: Je bent een doortastende hulpvaardige programmamanager. Je moet een programma opstellen om de verschillende doelen van het lonkende perspectief te bereiken. Welke projecten zou je voor elk van de doelen formuleren en op de roadmap plaatsen op de korte, midden en langetermijn, op basis van onderstaande input? Beschrijf per project de titel, het doel en ook de meetbare outcome indicatoren om de volwassenheidsstadia van de bereikte doelen te kunnen meten. 
 

Input: ub2030-??-???-gpt4-step2-perspective.md

Output: ub2030-??-???-gpt4-step3-next_steps.md

--------

Prompt: Gebruik de volgende roadmap, en plaats het in een verhalend scenario in de vorm van een dialoog tussen twee mensen uit een science-fiction roman:

Input: ub2030-??-???-gpt4-step3-next_steps.md

Output: ub2030-??-???-gpt4-step4-story_dialoge.md

--------

Prompt: Geef een overzicht welke doelen van de verschillende lonkende perspectieven van de verschillende afleveringen overlappen met elkaar. Geef aan op welke afleveringen dit van toepassing is. Sorteer de doelen met de meeste overlap boven aan.

Input: ub2030-[??]-[???]-gpt4-step2-perspective.md

Output: ub2030-overall-gpt4-common-goals.md


--------

Prompt:
Haal uit al deze markdown documenten de titel en de management samenvatting.
Ga als volgt te werk.
1. Sorteer de markdown bestanden op volgorde. 
2. voor elk bestand:
2a. Extraheer de exacte titel. Titels zijn aangeduid met heading 1 # 
2b. Extraheer de exacte Management Samenvatting. Management samenvattingen zijn aangeduid met heading 2 ## Management Samenvatting. De Managment samenvatting loop tot de volgende heading 2 ##.

Input: ub2030-??-???-gpt4-step1-summary.md

Output: ub2030-gpt4-combined_management_summaries.md

--------

Prompt: 
We gaan een gedachten experiment doen aan de hand van de Futures Triangle. een Methode uit innovatie managment op op basis van de beelden uit het verleden, heden en toekomst de meest waarschijnlijke toekomst te bepalen.
Maak een tabel met zes kolommen : Onderwerp, Last van het Verleden, Momentum van het Heden, Gewenste Toekomst, Waarschijnlijke Toekomst, Advies om Gewenste Toekomst te Bereiken (binnen de kaders van de mogelijkheden van de Universiteitsbibliotheek).
Maak rijen aan de hand van de Onderwerpen die in de input tekst wordt behandeld. 
Vul de cellen van de Onderwerpen en de drie kolommen -  Last van het Verleden, Momentum van het Heden, Gewenste Toekomst - in op basis van de input tekst.
Vul de een na laatste laatste kolom - Waarschijnlijke Toekomst - in door te beredeneren aan de hand van de drie voorgaande kolommen (Last van het Verleden, Momentum van het Heden, Gewenste Toekomst).
Beschrijf voor de tabel een inleidende paragraaf dat beschrijft dat er een interview heeft plaats gevonden met de gasten met hun functie en waar ze werken, dat dit de belangrijkste onderwerpen zijn die werde nbesproeken, en dat aan de hand van de Futures Triangle de meest waarschijnlijke toekomst wordt verkend voor de Universiteitsbibliotheek in 2030, en wat er nodig is de gewenste toekomst te bereiken. 
Beschrijf na de tabel een verklarende woorden lijst van de onderwerpen, op de volgende manier
1. **Onderwerp:** ...
  - **Definitie:** ...
  - **Context:** ...
Plaats bovenaan een titel ## Interview uitkomsten: Toekomst van (interview onderwerp)
En maak kopjes bij de inleiding (### Inleiding), tabel (### Tabel: Toekomstverkenning van besproken onderwerpen met de Futures Triangle) en Onderwerpenlijst (### Verklarende Onderwerpenlijst)

Input:  ub2030-??-???-gpt4-step1-summary.md

Output: ub2030-rapport-hoofdstuk-??-???.md