| Eigenaar | Ingevuld door |
| --- | --- |
| Kennis Centrum Architectuur | Johan Boer, Ilias Cheqri, Robert Melskens |
<hr/>


# Inleiding

Voor het project "Actualiseren informatiemodellen" is het primaire doel er voor te zorgen dat de informatiemodellen RSGB en RGBZ geactualiseerd worden en het beheer van deze modellen weer regulier uitgevoerd kan worden. 

Dit pakken we volgordelijk op. Deze repository gaat over het actualiseren van het RSGB. Dit wordt als eerste uitgevoerd en zodra de beschikbaarheid van resources het toelaat wordt het actualiseren van het RGBZ gestart. 

# Documentatie

De documentatie die bij de meest recente stand van zaken van dit project hoort is te vinden op https://vng-realisatie.github.io/RSGB-Respec/ 
Deze documentatie wordt indien van toepassing telkens bijgewerkt naar aanleiding van verwerkte issues. 

# Doelstelling actualiseren RSGB

We willen het RSGB zodanig aanpassen dat het conform MIM 1.1 is opgesteld, dat het consistent is met de informatiemodellen van de gerelateerde domeinen (basisregistraties) en dat het toekomstige ontwikkelingen optimaal ondersteunt. Vertrekpunt hierbij is de laatst vastgestelde versie van het RSGB (2.02). Ook worden hierbij inzichten rond domeingrenzen die opgedaan zijn in het traject rond de API-Referentie Architectuur (ARA) meegewogen.  

# Aanpak
Om dit te bereiken zijn er 13 milestones gedefinieerd. Per milestone worden issues gedefinieerd die opgelost moeten worden om de betreffende milestone te bereiken.
Ook is er per milestone gedefinieerd wat de primaire input is. Dat neemt niet weg dat er ook andere bronnen worden geraadpleegd om issues te identificeren en formuleren. 

Kanttekening hierbij is dat er 5 jaar geleden een RSGB versie 3.02 is opgeleverd. Deze versie is destijds niet vatsgesteld, maar zal voor dit traject zeer waardevolle input leveren in iedere milestone. 

Voor iedere milestone is er een analyse-fase waarin wordt onderzocht welke issues er moeten worden opgelost. Uiteraard zal tijdens de behandeling en verwerking van de issues binnen een mileston de situatie kunnen onstaan dat er nieuwe issues worden geconstateerd. Die nieuwe issues worden toegekend aan de milestones waar ze bij horen en daarbinnen opgepakt. 

Naast de issues die uit de analyse-fase voortkomen staat het de community deelnemers vrij issues in te dienen. 

# Milestones

0. RSGB 2.02 vermimmen

    - Voordat we stappen kunnen maken met het informatiemodel RSGB moeten we de (grote) stap naar MIM maken. In deze milestone gaan we alleen alle regels van het MIM toepassen op het IM en geen inhoudelijke wijzigingen doorvoeren.
    - Input: MIM documentatie en RSGB 3.02

1. RSGB 2.02 up-to-date maken met LO-BRP Q3 2025

    - We inventariseren welke verschillen er nu tussen het huidige RSGB 2.02 en LO-BRP Q3 2025 zijn. Op basis van die verschillen worden issues geformuleerd om RSGB en LO-BRP Q3 2025 weer met elkaar in lijn te brengen.
      Tevens wordt gevisualiseerd in het RSGB welk deel gerelateerd is aan de BRP.
    - Input: LO-BRP Q3 2025 en RSGB 3.02 


2. RSGB 2.021 up-to-date maken aan StUF-BG 3.10 patch 33.1

    - In de loop van de afgelopen jaren zijn er enkele patches op StUF-BG 3.10 doorgevoerd. Gezien de pauze in het beheer van het RSGB is de kans aanwezig dat     door deze patches in de uitwisselings-schema's of door aanpassingen in het gebruik van extraElementen er een discrepantie is ontstaan met het RSGB.
      Alle issues die hiervan het gevolg zijn worden in deze milestone geadresseerd.
    - Input: Overzicht van de wijzigingen per StUF-BG patch.

3. Wijzigingsvoorstellen n.a.v. een analyse van het GGM verwerken 

    - In deze versie van het RSGB worden wijzigingen die binnen het GGM-traject zijn aangebracht in RSGB2.02 objecten beoordeeld en, indien gewenst en noodzakelijk, opgenomen in het RSGB.
    - Input: Propopsal.doc, opgeleverd door de GGM-community

4. RSGB 3.02-wijzigingen beoordelen voor opname in RSGB 2.03

    - In de modeelering van RSGB 3.02 zijn wijzigingen doorgevoerd t.o.v. RSGB 2.02. Wijzigingen die te relateren zijn aan het LO-BRP moeten beoordeeld worden in hoeverre deze ook in de RSGB versie "in control" moeten landen en welke wijzigingen eventueel naar een nieuwe versie moeten worden getild. 
    - Input: RSGB 3.02 (niet vastgesteld)

5. RSGB compliant maken aan IMBAG

    - In deze versie van het RSGB wordt gevisualiseerd welke onderdelen van het RSGB hun oorsprong in het IMBAG hebben. Tevens wordt de modellering van het IMBAG onverkort overgenomen voor die objecten die des IMBAG's zijn. Her-modelleringskeuzes worden zoveel mogelijk geëlimineerd, tenzij de levering van deze "ge-hermodelleerde" resources door de LV-BAG wordt aangeboden. (Gemeentelijke view op BAG-gegevens).
    - Input Catalogus BAG 2018 en RSGB 3.02

6. RSGB compliant maken aan huidige versie van IMKAD

    - In deze versie van het RSGB wordt gevisualiseerd welke onderdelen van het RSGB hun oorsprong in het IMKAD hebben. Tevens wordt de modellering van het IMKAD onverkort overgenomen voor die objecten die des IMKAD's zijn. Her-modelleringskeuzes worden zoveel mogelijk geëlimineerd tenzij de "gehermodelleerde" resources door het BRK worden aangeboden. (Gemeentelijke vie op Kadaster-gegevens)
    - Input: Imkad 2.3 en RSGB 3.02

7. RSGB compliant maken aan het Handelsregister

    - In deze versie van het RSGB wordt gevisualiseerd welke onderdelen van het RSGB hun oorsprong in het HandelsRegister hebben hebben. Tevens wordt de modellering van het Handelsregister onverkort overgenomen voor die objecten die des Handelsregisters zijn. Hermodelleringskeuzes worden zoveel mogelijk geëlimineerd. , tenzij de levering van deze "ge-hermodelleerde" resources door de KVK wordt aangeboden. (Gemeentelijke view op HR-gegevens).
    - Input: Gegevenscatalogus 3.0.4h (april 2022) en RSGB 3.02

8. RSGB compliant maken aan de IMWOZ

    - In deze versie van het RSGB wordt gevisualiseerd welke onderdelen van het RSGB hun oorsprong in het IMWOZ hebben hebben. Tevens wordt de modellering van het IMWOZ onverkort overgenomen voor die objecten die des IMWOZ's zijn. Hermodelleringskeuzes worden zoveel mogelijk geëlimineerd. , tenzij de levering van deze "ge-hermodelleerde" resources door de LV-WOZ wordt aangeboden. (Gemeentelijke view op WOZ-gegevens).
    - Input: IMWOZ 03.12 en RSGB 3.02

9. RSGB compliant maken aan de BGT / IMGEO

    - In deze versie van het RSGB wordt gevisualiseerd welke onderdelen van het RSGB hun oorsprong in de BGT en/of het IMGEO hebben. Tevens wordt de modellering van de BGT/IMGEO onverkort overgenomen voor die objecten die des BGT's of IMGEO's zijn. Hermodelleringskeuzes worden zoveel mogelijk geëlimineerd. , tenzij de levering van deze "ge-hermodelleerde" resources door de Basisregistratie Grootschalige Topografie wordt aangeboden. (Gemeentelijke view op BGT-gegevens).
    - Input: Gegevenscatalogus BGT 1.2 en Gegevenscatalogus IMGeo 2.2

10. Herstructurering om bestaande functionaliteitsissues te elimineren

11. Herstructurering om complexiteit binnen het RSGB te reduceren

12. Herstructurering om hergebruik van objecttypen uit basisregistraties te faciliteren


Elke afgeronde milestone KAN tot een versie van het RSGB leiden dat in gebruik kan worden genomen. Dit wordt door de community bepaald. 
De mate waarin deze versies dan worden geformaliseerd worden met de community en binnen het beheer-model van VNG-Realisatie afgestemd.

# Deelname

Mocht u vanuit uw rol binnen een gemeente, samenwerkingsverband of leverancier reden zien om deel te nemen aan de community dan kunt u daarvoor contact opnemen met Ilias.Cheqri@VNG.NL




