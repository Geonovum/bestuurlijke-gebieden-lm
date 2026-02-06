# Inleiding

Dit document beschrijft het Logisch Gegevensmodel Bestuurlijke Gebieden (LGM-BG). Het model is een uitwerking van het Conceptueel Informatiemodel Bestuurlijke Gebieden [[CIM-BG]] en beschrijft de gegevens die nodig zijn om de in het [[CIM-BG]] beschreven objecten te registreren, beheren en uitwisselen.

## Doel

Het [[CIM-BG]] beschrijft bestuurlijke gebieden op conceptueel niveau: welke objecten bestaan er, wat zijn hun eigenschappen en hoe verhouden ze zich tot elkaar. Het logisch gegevensmodel werkt dit verder uit naar een niveau dat geschikt is voor implementatie. Het LGM-BG vormt de basis voor de Basisvoorziening Bestuurlijke Gebieden (BVBG).

Dit betekent dat het LGM-BG aanvullende aspecten beschrijft die op conceptueel niveau nog geen rol spelen, zoals:

- De identificatie van objecten
- Het historiemodel met tijdlijnen voor geldigheid en registratie
- De concrete geometrietypen en ondersteunde coördinaatreferentiesystemen
- De registratiegegevens, inclusief versie-informatie en bronverwijzingen

## Aansluiting op het conceptueel model CIM-BG

Het LGM-BG is een uitwerking van het [[CIM-BG]]. Het logisch model heeft niet altijd dezelfde structuur als het conceptueel model. De belangrijkste verschillen zijn:

- In het logisch model zijn attributen opgenomen die nodig zijn voor de registratie van objecten, maar die niet in het conceptueel model zijn beschreven. Denk aan identificatie, versie, tijdlijnen en bronverwijzingen.
- Het logisch model bevat het domein *Registratiegegevens* dat het bitemporale historiemodel en de herkomstgegevens beschrijft. Dit domein is niet aanwezig in het conceptueel model.
- Het logisch model neemt een *view* op van de TOOI-ontologie ([[TOOI-ONT-1.6.2]]) voor de beschrijving van overheidsorganisaties die bestuurlijke gebieden besturen.

Voor de conceptuele beschrijvingen van de objecttypen, hun definities en onderlinge relaties wordt verwezen naar het [[CIM-BG]].

## Aansluiting op NEN 3610

Het LGM-BG is opgesteld volgens de richtlijnen van [[NEN3610-2022]] en het [[MIM12]]. Dit betekent dat het model is opgebouwd uit objecttypen, attribuutsoorten en relatiesoorten. Daarnaast wordt gebruik gemaakt van de in NEN 3610 beschreven basisprincipes voor identificatie, tijdlijnen en geometrieën.

## Scope

Het LGM-BG hanteert dezelfde scope als het [[CIM-BG]]. De volgende typen bestuurlijke gebieden zijn in scope:

- Landgebied
- Provinciegebied
- Gemeentegebied
- Waterschapsgebied
- Veiligheidsregiogebied
- Maritieme zones: territoriale zee, aansluitende zone, exclusieve economische zone en het continentaal plat

Zie de [inleiding van het CIM-BG](https://geonovum.github.io/bestuurlijke-gebieden-cm/#inleiding) voor de volledige scopebeschrijving, achtergrond en afbakening.

## Leeswijzer

- Hoofdstuk 2 beschrijft de algemene uitgangspunten van het logisch model: identificatie, levenscyclus, geometrie, coördinaatreferentiesystemen en registratiegegevens.
- Hoofdstuk 3 geeft een overzicht van het model en plaatst het in context.
- Hoofdstuk 4 bevat het informatiemodel in detail, met alle objecttypen, attributen en relaties.
