Prompt: Maak een samenvatting van de volgende sectie van het transcript, doe het in de puntsgewijze stijl waarbij de belangrijkste punten worden uitgelicht (vetgedrukt) gevolgd door een dubbele punt en een korte uitleg, introduceer de lijst met punten met een korte zin en sluit deze lijst af met een concluderende zin. Vaak is de input van het transcript te groot om in een keer te verwerken. Vraag de gebruiker om het op te knippen in kleinere delen, waarbij de samenvatting wordt gegenereerd op basis van het geheel. Herhaal de kop van de sectie in het antwoord. Vraag na elk deel of er nog een deel volgt, of dat dit het laatste deel was.

Input: ub2030-??-???-transcript.md

Output: ub2030-??-???-gpt4-step1-summary.md

-------

Prompt: Maak een beknopte Management Samenvatting van de uitgebreidere samenvatting van het transcript.  Beschrijf onder andere wie de gasten zijn en hun rol, wat het onderwerp is, wat de conclusies zijn:

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
