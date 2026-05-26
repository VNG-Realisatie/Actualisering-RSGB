# Werkproces Actualisering RSGB

## Incrementeel creatieproces

Bij het actualiseren van  het RSGB hanteren we het hieronder geïllustreerde incrementele creatieproces. Daarbij maken we gebruik van het daarvoor ingerichte [Kanban bord](https://github.com/orgs/VNG-Realisatie/projects/24) met de in de illustratie genoemde kolommen:

1.	Todo
2.	In discussie (voor volgende sessie)
3.	Consensus bereikt
4.	Review verwerking in RSGB
5.	Done
<!-- 
![GitHub Proces](https://github.com/user-attachments/assets/cd2a7eda-0981-48b4-8471-67d16d90a3e7)

Daar waar een blok een vervolg naar zowel een blauwe als een oranje route kent lopen deze parallel aan elkaar. Bijv. na het afronden van een issue dat in _"In progress 'Uitleg'"_ staat wordt de oranje route naar _"Is PR nodig?"_ EN de blauwe route naar _"Is het een Begrippenmodel issue?"_ doorlopen.
Is een PR noodzakelijk dan heb je dus 2 items: 
1. het originele issue en
2. de PR. 

Alleen PR’s komen in de 5e Kanban kolom ( _"In review (PR’s)"_ ), en er kunnen meerdere PR’s per issue zijn (elke keer als in een fase via het oranje pad de vraag _“Is PR nodig?”_ bevestigend wordt beantwoord). Per PR kunnen meerdere isues worden opgelost. -->

## Uitgebreide review

Het in de voorgaande paragraaf beschreven proces is grotendeels gericht op enkelvoudige issues die in de onderliggende repository staan op stap 4 na.
De in die stap genoemde review betreft een review op een Respec document dat in [deze repository[(https://github.com/VNG-Realisatie/RSGB-Respec) wordt gegenereerd en waarin over het algemeen meerdere issues verwerkt zullen zijn. 
In dat Respec document kunnen reviewopmerkingen worden geplaatst aan de hand waarvan bekeken zal worden of nieuwe issues noodzakelijk zijn of juist alleen een terugkoppeling aan de reviewer.
Voor het kunnen plaatsen van reviewopmerkingen moet echter aan enkele voorwaarden worden voldaan.

Van elk document dat we willen onderwerpen aan een uitgebreide review dient eerst een snapshot vervaardigd te worden. 

Onder een snapshot verstaan we een in de tijd bevroren status van een document met een naam waarin het tijdstip waarop het bevroren is opgenomen. De conventie daarvoor is _[originele naam]-[yyyymmdd].[extensie]_. 
In de regel zal het gaan om een markdown of html bestand maar in principe kan het ook enig ander formaat betreffen zolang dat maar te bekijken is in een webbrowser, bijv. een html of een text bestand, en het via een url te benaderen is.

> Van een Respec document kan een snapshot vervaardigd worden door het te openen en rechtsboven op de _'Respec'_ button te klikken en vervolgens te kiezen voor _'Bewaar Snapshot...'_.
>
> <img width="1165" height="149" alt="image" src="https://github.com/user-attachments/assets/d8d10fc7-58fc-4104-b16c-65e78842d62c" />

Dit document wordt geplaatst in de folder 'snapshot'.

Dan zou bijvoorbeeld het document 'snapshots/RSG_Basisgegevens_2_02-20260526.html' geöpend kunnen worden via de url https://geonovum.github.io/mim-metamodel/snapshots/RSG_Basisgegevens_2_02-20260526.

Deze url dient gedeeld te worden met de groep van personen waarvan verwacht wordt dat deze de review uitvoert. 

Deze personen maken, voor het uitvoeren van de review, gebruik van '[Hypothesis](https://web.hypothes.is/)'. 

> Hypothesis werkt in elke moderne web browser versie die gereleased is in de laatste 12 maanden. waaronder:
> 
> * Chrome
> * Firefox
> * Safari
> * Microsoft Edge
> * Opera
> * Vivaldi
> * Brave
