---
title: "Complexiteit"
date: 1997-0-01T10:39:52+02:00
---

Tactiek! Positiespel! Strategie!

Kom, kom ... Laten we gewoon een potje schaken!

Met deze houding is natuurlijk niets mis. Er is ook niets mis met enkel Sudoku's op 'Beginner's Level' op te lossen.

Wij - deelnemers aan de tweede reeks - denken daar toch wat anders overs: we willen het fijne weten achter die zetten. 
We willen meer genieten van de partijen van de grootmeesters en wereldkampioenen.

We willen meer diepgang geven aan onze partijen. Onze creaties moeten meer kwaliteit vertonen.

*En vooral: we willen meer winnen!*

Dit artikel kleurt wat buiten de lijntjes: het gaat over de vraag *Wat is complex ?*

In het artikel staan ook verschillende covers van boeken. Het is waarschijnlijk niet schadelijk voor de gezondheid om deze ook te lezen.

## P versus NP

![P vs NP](/chess/images/pnp.jpg)

Vraag je je soms wel eens af: “Wat is het moeilijkste wiskundige probleem” ? 

Wel, de Amerikaans miljardair Landon T. Clay stelde zich ook deze vraag. De man bleef niet bij de pakken zitten en richtte in 1998 het “Clay Mathematics Institute” op. Dit instituut formuleerde de *“7 Millenium Problems”*: zeven wiskundige problemen waarvan sommige al eeuwen op een oplossing wachten.  Per oplossing krijg je 1 miljoen dollar! 

In 2002 wist de Rus [Grigoriy Perelman](https://nl.wikipedia.org/wiki/Grigori_Perelman) de zogenaamde “Poincaré Conjecture“ op te lossen. Er nog even aan toevoegen dat Grigoriy, die in een armtierig appartementje in Moscow leefde, het niet zag zitten om zijn moedertje alleen te laten om de prijs gaan op te halen.

Één van overblijvende problemen is het “P vs NP Problem”. Dit is, mijns inziens, het moeilijkste probleem!  

Uitleggen – aan schakers – waarover dit probleem precies gaat, is best eenvoudig: *“Mag je, in het algemeen zeggen, als je de oplossing van een probleem eenvoudig kunt verifiëren, dat dan het probleem zelf niet veel moeilijker is op te lossen?”*

Laten we dat even uitleggen in schaaktermen: reeds in stap 1 van de jeugdopleiding leert elk schakertje hoe hij/zij kan zien of de tegenstander schaakmat staat. Je weet het wel: de koning moet schaak staan en mag geen vluchtveld hebben, de aanvaller mag niet kunnen worden geslagen en er mag geen stuk kunnen tussen springen.

Als het “P vs NP Problem” affirmatief kan worden beantwoord, dan mogen we hieruit concluderen dat er een niet zo heel moeilijk te vinden weg is van beginstelling tot eindpositie!

Nu, *“dat niet zo heel moeilijk”* neem je best met een korreltje zout: het “P vs NP Problem” is een wiskundig probleem en wordt in heel rigoureuze termen gedefinieerd. Maar toch … *“dat niet zo heel moeilijk”*  heeft enorme implicaties en niet alleen voor wiskunde en filosofie: elke menselijke bezigheid wordt erdoor geraakt! 

Om je een idee te geven, stel dat je kan bewijzen dat P = NP (met andere woorden: je bewijst dat het probleem met ‘ja’ wordt beantwoord). Als het Clay Institute jouw antwoord eenvoudig kan verifiëren (en met 1 miljoen dollar klaar staat), dan betekent dit meteen dat je een relatief simpele weg hebt tot het vinden van een oplossing tot elk probleem. Het is slecht een kwestie van tijd of je geneest kanker en je bereikt kernfusie. Net als Perelman vind je het op dat moment waarschijnlijk ook de moeite niet meer om dat 1 miljoen dollar gaan op te halen.

als je meer wil weten over *complexity theory*, raad ik je aan het *"The Book of Why / Judea Pearl"* te lezen. Je kan het bij Amazon op Kindle kopen voor 10 dollar!

![The Book of Why](/chess/images/judea.jpg)


## Hoe complex is schaken

Nu dat we weet hebben van het “P vs NP Problem”, is het antwoord op deze vraag: “Het hangt er wat van af …”.  Is P=NP, dan valt het allemaal nogal mee.

Een goede indicatie is het aantal posities die mogelijk zijn in het schaken.

Als je dacht dat ik dat nu ga uitrekenen, dan ben je niet goed snik. Ik sta daarvoor liever op de schouder van een reus. 

Iedereen kent het getal **π**. 

Wel, er bestaan nog andere getallen die een naam hebben: zo is er **“het getal van Shannon”**. 

Dit getal stelt precies het aantal partijen met gemiddeld 40 zetten. 

“Shannon !? Wie is dat nu weer ?”

Iedereen kent de grote wetenschappers: Archimedes, Newton, Gauss, Einstein. 

Maar er zijn van die wetenschappers die minder goed zijn in het verzorgen van hun public relations, maar die misschien nog belangrijker waren: mensen zoals John Von Neumann, Kurt Gödel, Alan Turing, Alexander Grothendieck en  … Claude Shannon.

![Einstein en Gödel in de tuinen van Princton: mijn absoluut favoriete Internet foto](/chess/images/godel.jpg)


Ik vermeld expliciet deze namen omdat ik hoop daar later (en niet enkel in deze tekst) nog met uit te pakken!
Laten we het hier houden op Claude Shannon.  De man vond het elektronisch circuit uit, legde eigenhandig de basisregels voor digitale communicatie vast en stampte de moderne informatietheorie uit de grond.  Veel meer moet dat niet zijn! Oh ja, hij was ook een befaamd goochelaar.

![Claude Shannon](/chess/images/shannon.jpg)

De voornaamste reden waarom u nog niet gehoord hebt over de man, heeft te maken met de aard en de kwaliteit van zijn werk: zijn wetenschappelijke resultaten waren zo belangrijk dat de Amerikaanse overheid pas op het einde van de 20e eeuw de publicatie ervan toeliet.

Shannon was een excentriek man: hij hield van goochelen, bouwde een computer die gebaseerd was op Romeinse getallen, maakte muziek op een schuiftrompet die vuur kon spuwen en … was een fervent schaakenthousiast!

Ach, vergeef mij mijn uitweidingen, maar uiteindelijk zijn we terug waar we moeten zijn: het getal van Shannon.

Shannon berekende een ondergrens voor het aantal verschillende posities die op een schaakbord kunnen verschijnen. Hij vond het getal 10.000.000.000.000.000.000.000.000.000.000.000.000.000.000 (of: 10^43). Als je weet dat er ongeveer 10^25 zandkorrels op aarde zijn, dan kunnen we wel zeggen dat dit veel is.

Maar waarom is dit “veel” zo belangrijk als we het hebben over de complexiteit van het schaken?
