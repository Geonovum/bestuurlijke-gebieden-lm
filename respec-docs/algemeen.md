# Algemene uitgangspunten

## Identificatie

Aan elk <a data-cite="MIM12#object">object</a> wordt een unieke identificatie toegekend. Zolang het object bestaat, mag deze identificatie niet veranderen. De objectidentificatie moet uniek, betekenisloos, permanent en overal geldig (systeemonafhankelijk) zijn.

Het LGM-BG volgt hier de richtlijnen van [[NEN3610-2022]]. De identificatie identificeert het object. Als men het over het object met een bepaalde identificatie heeft (of er naar verwijst) dan wil men zeker weten dat daadwerkelijk dat ene object wordt bedoeld en niet dat er meerdere objecten aangewezen worden.

Daarnaast is het van belang dat de identificatie betekenisloos is. Dit betekent dat de identificatie geen informatie mag bevatten over het object zelf, zoals bijvoorbeeld de locatie, de eigenaar of de tijd van ontstaan. Dit voorkomt dat de identificatie moet worden aangepast als deze informatie verandert.

Een identificatie is permanent en identificeert een object in de beschouwde werkelijkheid, onafhankelijk van de gegevens die erover verwerkt worden. Gedurende de gehele levenscyclus van een object blijft de identificatie gelijk. De identificatie van een object identificeert dus niet een versie van de gegevens over dat object. Voor het identificeren van een specifieke versie van de gegevens over een object wordt gebruik gemaakt van eigenschappen beschreven in [[[#domein-registratiegegevens]]].

### Identificatie en Domein (namespace) attributen

In [[NEN3610-2022]] wordt beschreven dat de identificatie uniek moet zijn binnen een bepaald domein. Dit betekent dat de identificatie alleen uniek is binnen een bepaalde context, zoals een organisatie of een systeem. Om ervoor te zorgen dat de identificatie overal uniek is, wordt er gebruik gemaakt van een domein attribuut.

Een domein attribuut heeft als datatype een URI. De URI verwijst naar de context waarin de identificatie uniek is. Door het domein attribuut te combineren met de identificatie, wordt ervoor gezorgd dat de identificatie overal uniek is.

<figure>
  <img src="media/nen3610-identificatie.png" alt="NEN 3610 identificatie">
  <figcaption>Modelleerpatroon voor identificatie in NEN 3610</figcaption>
</figure>

## Levenscyclus

Objecttypen in het LGM-BG kunnen een levenscyclusstatus toegekend krijgen. Hiermee wordt het mogelijk om aan te geven in welke fase een object verkeert. De levenscyclus begint op het gedefinieerde ontstaansmoment en eindigt wanneer een object niet meer bestaat in de werkelijkheid.

Het [[CIM-BG]] onderscheidt vier levenscyclusstatussen voor registratieve ruimten: `Ontwerp`, `Niet gerealiseerd`, `Vastgesteld` en `Ingetrokken`. Zie het [[CIM-BG]] voor een [uitgebreide beschrijving van de levenscyclus](https://geonovum.github.io/bestuurlijke-gebieden-cm/#levenscyclus).

In het LGM-BG wordt een beperktere set statussen gehanteerd. Er worden alleen de volgende statussen ondersteund:

- `Vastgesteld` — Object dat door het bevoegd gezag is benoemd of afgebakend op grond van wet- of regelgeving
- `Ingetrokken` — Object dat door het bevoegd gezag is ingetrokken op grond van wet- of regelgeving

De statussen `Ontwerp` en `Niet gerealiseerd` worden in dit logisch model niet ondersteund. Er zijn momenteel geen bronnen ingericht om deze statussen te vullen en de informatiebehoefte hiervoor is nog niet in kaart gebracht. In een toekomstige versie van het model kunnen deze statussen worden toegevoegd wanneer daar behoefte aan ontstaat.

## Geometrie

Voor de representatie van de locatie en vorm van bestuurlijke gebieden worden in dit model geometrieën gebruikt. Het [[CIM-BG]] beschrijft uitgebreid de [uitgangspunten voor geometrie](https://geonovum.github.io/bestuurlijke-gebieden-cm/#geometrie), waaronder geometrietypen, dimensies en ruimtelijke relaties. Deze uitgangspunten zijn ook van toepassing op het LGM-BG.

Bestuurlijke gebieden worden tweedimensionaal vastgelegd. In het logisch model is het geometrietype voor bestuurlijke gebieden gedefinieerd als `VlakOfMultivlak`: een keuze tussen `GM_Surface` (vlak) of `GM_MultiSurface` (multivlak). Dit zijn geometrietypen uit [[ISO-19107-2019]], conform de [[ISO-19125]] Simple Features standaard.

Het model hanteert uitsluitend expliciete geometrie en lineaire interpolatie; bogen zijn niet toegestaan. Zie [[GIMEG]] voor een uitgebreidere toelichting op de toepassing van ISO 19107-geometrietypen.
