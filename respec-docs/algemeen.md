# Algemene uitgangspunten

In dit hoofdstuk wordt onderscheid gemaakt tussen een *domeinobject* en een *gegevensobject*. Een domeinobject is een <a data-cite="MIM12#object">object</a> in de beschouwde werkelijkheid, zoals een gemeentegebied of een provinciegebied. Een gegevensobject is een set van gegevens die uitdrukkingen bevat over een domeinobject, zoals de naam, geometrie en levenscyclusstatus. Het gegevensobject komt overeen met wat in [[NEN3610-2022]] een *informatieobject* wordt genoemd. Over elk gegevensobject worden daarnaast registratiegegevens vastgelegd, zoals versie, tijdlijnen en herkomst, die het gegevensobject zelf als onderwerp hebben.

## Identificatie

Aan elk domeinobject wordt een unieke identificatie toegekend. Zolang het domeinobject bestaat, mag deze identificatie niet veranderen. De objectidentificatie moet uniek, betekenisloos, permanent en overal geldig (systeemonafhankelijk) zijn.

Het LGM-BG volgt hier de richtlijnen van [[NEN3610-2022]]. De identificatie identificeert het domeinobject. Als men het over het domeinobject met een bepaalde identificatie heeft (of er naar verwijst) dan wil men zeker weten dat daadwerkelijk dat ene domeinobject wordt bedoeld en niet dat er meerdere domeinobjecten aangewezen worden.

Daarnaast is het van belang dat de identificatie betekenisloos is. Dit betekent dat de identificatie geen informatie mag bevatten over het domeinobject zelf, zoals bijvoorbeeld de locatie, de eigenaar of de tijd van ontstaan. Dit voorkomt dat de identificatie moet worden aangepast als deze informatie verandert.

Een identificatie is permanent en identificeert een domeinobject in de beschouwde werkelijkheid, onafhankelijk van de gegevens die erover verwerkt worden. Gedurende de gehele levenscyclus van een domeinobject blijft de identificatie gelijk. De identificatie van een domeinobject identificeert dus niet een gegevensobject of een versie daarvan. Voor het identificeren van een specifieke versie van de gegevens over een domeinobject wordt gebruik gemaakt van eigenschappen beschreven in [[[#domein-registratiegegevens]]].

### Identificatie en Domein (namespace) attributen

In [[NEN3610-2022]] wordt beschreven dat de identificatie uniek moet zijn binnen een bepaald domein. Dit betekent dat de identificatie alleen uniek is binnen een bepaalde context, zoals een organisatie of een systeem. Om ervoor te zorgen dat de identificatie overal uniek is, wordt er gebruik gemaakt van een domein attribuut.

Een domein attribuut heeft als datatype een URI. De URI verwijst naar de context waarin de identificatie uniek is. Door het domein attribuut te combineren met de identificatie, wordt ervoor gezorgd dat de identificatie overal uniek is.

<figure>
  <img src="media/nen3610-identificatie.png" alt="NEN 3610 identificatie">
  <figcaption>Modelleerpatroon voor identificatie in NEN 3610</figcaption>
</figure>

## Levenscyclus

Objecttypen in het LGM-BG kunnen een levenscyclusstatus toegekend krijgen. Hiermee wordt het mogelijk om aan te geven in welke fase een domeinobject verkeert. De levenscyclus begint op het gedefinieerde ontstaansmoment en eindigt wanneer een domeinobject niet meer bestaat in de werkelijkheid. De levenscyclusstatus is een eigenschap van het domeinobject, niet van het gegevensobject.

Het [[CIM-BG]] onderscheidt vier levenscyclusstatussen voor registratieve ruimten: `Ontwerp`, `Niet gerealiseerd`, `Vastgesteld` en `Ingetrokken`. Zie het [[CIM-BG]] voor een [uitgebreide beschrijving van de levenscyclus](https://geonovum.github.io/bestuurlijke-gebieden-cm/#levenscyclus).

In het LGM-BG wordt een beperktere set statussen gehanteerd. Er worden alleen de volgende statussen ondersteund:

- `Vastgesteld`: Domeinobject dat door het bevoegd gezag is benoemd of afgebakend op grond van wet- of regelgeving
- `Ingetrokken`: Domeinobject dat door het bevoegd gezag is ingetrokken op grond van wet- of regelgeving

De statussen `Ontwerp` en `Niet gerealiseerd` worden in dit logisch model niet ondersteund. Er zijn momenteel geen bronnen ingericht om deze statussen te vullen en de informatiebehoefte hiervoor is nog niet in kaart gebracht. In een toekomstige versie van het model kunnen deze statussen worden toegevoegd wanneer daar behoefte aan ontstaat.

## Geometrie

Voor de representatie van de locatie en vorm van bestuurlijke gebieden worden in dit model geometrieën gebruikt. Het [[CIM-BG]] beschrijft uitgebreid de [uitgangspunten voor geometrie](https://geonovum.github.io/bestuurlijke-gebieden-cm/#geometrie), waaronder geometrietypen, dimensies en ruimtelijke relaties. Deze uitgangspunten zijn ook van toepassing op het LGM-BG.

Bestuurlijke gebieden worden tweedimensionaal vastgelegd. 3D- of 2.5D-geometrieën worden in dit model niet gebruikt. In het logisch model is het geometrietype voor bestuurlijke gebieden gedefinieerd als `VlakOfMultivlak`: een keuze tussen `GM_Surface` (vlak) of `GM_MultiSurface` (multivlak). Dit zijn tweedimensionale geometrietypen uit [[ISO-19107-2019]], conform de [[ISO-19125]] Simple Features standaard.

Het model hanteert uitsluitend expliciete geometrie en lineaire interpolatie; bogen zijn niet toegestaan. Zie [[GIMEG]] voor een uitgebreidere toelichting op de toepassing van ISO 19107-geometrietypen.

## Coördinaatreferentiesystemen

Het Basismodel Geo-informatie [[NEN3610-2022]] stelt dat iedere geometrie voorzien moet zijn van een verwijzing naar het coördinaatreferentiesysteem (CRS) waarin de coördinaten zijn beschreven. Welk CRS van toepassing is, wordt bepaald door de dimensionaliteit van de geometrie en het toepassingsgebied.

Het toepassingsgebied van het LGM-BG betreft het Europese grondgebied van het Koninkrijk der Nederlanden, inclusief de daarbij behorende territoriale wateren en maritieme zones. Bestuurlijke gebieden worden tweedimensionaal vastgelegd. Zie het [[CIM-BG]] voor een [uitgebreide beschrijving van coördinaatreferentiesystemen](https://geonovum.github.io/bestuurlijke-gebieden-cm/#co%C3%B6rdinaatreferentiesystemen).

### Aanlevering

Voor het CRS van 2D-geometrieën gelden bij aanlevering de volgende CRS'en:

| CRS-Naam | Code  | URI                                              |
|----------|-------|--------------------------------------------------|
| RD       | 28992 | http://www.opengis.net/def/crs/EPSG/9.9.1/28992 |
| ETRF2000 | 9067  | http://www.opengis.net/def/crs/EPSG/9.9.1/9067  |

Er zijn verschillende realisaties van ETRS89 in omloop. Het LGM-BG neemt het advies van het *Regional Reference Frame Sub-Commission for Europe* (EUREF) over om de **ETRF2000-realisatie** te gebruiken. Maak bij aanlevering gebruik van een **lijnlengte van maximaal 200 meter**. Dit volgt het langelijnenadvies van het NSGI, dat is overgenomen in [[gebruik-crs]] in verband met compatibiliteit met RDNAPTRANS.

### Uitlevering

Bij uitlevering zijn dezelfde CRS'en als bij aanlevering beschikbaar. Daarnaast kan de geometrie als het geografisch ensemble van ETRS89 CRS'en worden uitgeleverd:

| CRS-Naam     | Code | URI                                              |
|--------------|------|--------------------------------------------------|
| ETRS89 (2D)  | 4258 | http://www.opengis.net/def/crs/EPSG/9.9.1/4258  |

Uitlevering via WGS 84 is ook mogelijk via nultransformatie, [zoals beschreven](https://docs.geostandaarden.nl/crs/crs/#wgs-84-gelijkstellen-aan-etrs89-nultransformatie) in [[gebruik-crs]]:

| CRS-Naam    | Code   | URI                                              |
|-------------|--------|--------------------------------------------------|
| WGS 84 (2D) | 4326  | http://www.opengis.net/def/crs/EPSG/9.9.1/4326  |
| WGS 84      | CRS84  | http://www.opengis.net/def/crs/OGC/1.3/CRS84    |

Hierbij is de OGC-code CRS84 de longitude-latitude-variant van de 2D WGS 84-realisatie met EPSG-code 4326. Aanbevolen wordt om in de metadata te vermelden dat een nultransformatie vanaf ETRF2000 is gebruikt.

## Registratiegegevens

In de BVBG worden gegevens geregistreerd over bestuurlijke gebieden. Voor elk domeinobject worden gegevensobjecten vastgelegd die de eigenschappen van dat domeinobject beschrijven. Over elk gegevensobject worden daarnaast registratiegegevens bijgehouden die het gegevensobject zelf als onderwerp hebben. De volgende registratiegegevens worden per gegevensobject vastgelegd:

- Registratiestatus
- Versie
- Tijdlijn geldigheid
- Tijdlijn registratie
- Herkomst en bronverwijzing

Deze registratiegegevens zijn afgeleid van de registratiegegevens zoals beschreven in [[NEN3610-2022]], [[PROV-O]] en [[EMSO]]. De volgende paragrafen lichten deze registratiegegevens verder toe. Zie het [informatiemodel](#domein-registratiegegevens) voor de volledige specificatie van het domein Registratiegegevens.

### Versie, tijdlijn geldigheid en tijdlijn registratie

In de levenscyclus van domeinobjecten kunnen kenmerken veranderen. Om deze veranderingen te kunnen vastleggen en raadplegen, worden opeenvolgende gegevensobjecten over dat domeinobject bijgehouden. Iedere versie van de gegevens over een domeinobject wordt vastgelegd als gegevensobject, beschreven door een [[NEN3610-2022]] Registratie-object. Over elk gegevensobject worden registratiegegevens vastgelegd, waaronder een versie en eigenschappen die de geldigheidstijdlijn en registratietijdlijn beschrijven.

De **geldigheidstijdlijn** beschrijft de periode waarin een domeinobject in de beschouwde werkelijkheid bestaat of geldig is. Hiervoor worden de eigenschappen `beginGeldigheid` en `eindGeldigheid` gebruikt.

De **registratietijdlijn** beschrijft de periode waarin een gegevensobject in de registratie bestaat. Hiervoor worden de eigenschappen `tijdstipRegistratie` en `eindRegistratie` gebruikt.

Een domeinobject heeft gedurende zijn levenscyclus op ieder moment in de gecombineerde tijdlijn geldigheid en registratie minimaal één gegevensobject.

<figure>
  <img src="data/media/registratiegegevens.png" alt="NEN 3610 Registratiegegevens">
  <figcaption>Registratiegegevens in NEN 3610:2022</figcaption>
</figure>

Met behulp van de tijdlijn geldigheid kan een afnemer bepalen welke gegevens *actueel* (nu geldig) zijn:

- **Actueel**: gegevens waarvan de `beginGeldigheid` nu of in het verleden ligt en `eindGeldigheid` leeg is of in de toekomst ligt.
- **Tijdreizen**: door een specifieke datum op te geven kunnen gegevens worden opgevraagd die op dat moment geldig waren.

<aside class="example" title="Gemeentelijke herindeling">
Bij een gemeentelijke herindeling wordt de nieuwe gemeentegrens vastgesteld door de provincie. De `beginGeldigheid` van het nieuwe gemeentegebied is de datum waarop de herindeling ingaat (vaak 1 januari). Tot die datum blijft het oude gemeentegebied actueel. Afnemers kunnen zo zowel de huidige als toekomstige situatie raadplegen.
</aside>

### Registratiestatus en afgevoerde registraties

Een domeinobject kan op ieder moment in de gecombineerde tijdlijn geldigheid en registratie een of meerdere gegevensobjecten kennen. Elk gegevensobject heeft een registratiestatus. De registratiestatus geeft aan of het gegevensobject actief is, of dat het een afgevoerd gegevensobject betreft:

- `Actief`: Het gegevensobject is actueel in de registratie.
- `Afgevoerd`: Het gegevensobject is niet meer actief, maar blijft bewaard in de tijdlijn registratie.

Er mag maar één gegevensobject zijn met de registratiestatus `Actief` op een bepaald moment in de gecombineerde tijdlijn geldigheid en registratie.

### Herkomst en bronverwijzing

Voor elk gegevensobject wordt opgenomen waar de gegevens vandaan komen en hoe deze tot stand zijn gekomen. Dit gebeurt door het registreren van herkomst- en bronverwijzingen. De herkomst maakt het mogelijk om de oorspronkelijke bronhouder en het gebruikte brondocument te identificeren.

Het herkomstmodel in het LGM-BG is gebaseerd op de W3C standaard [[PROV-O]]. Door aansluiting op PROV-O is het mogelijk om op een gestandaardiseerde en interoperabele manier de herkomst en bronverwijzingen van gegevensobjecten te registreren en te interpreteren. In het model is de minimale set van herkomst- en bronverwijzingen opgenomen:

- `afgeleidVan`: Een verwijzing naar de bronentiteit (bijvoorbeeld een brondocument) op basis waarvan het gegevensobject tot stand is gekomen.
- `verantwoordelijkePartij`: De actor die verantwoordelijk is voor de gegevens over het domeinobject.

## Afleidbare eigenschappen

In het LGM-BG worden naast direct geregistreerde eigenschappen ook afleidbare eigenschappen opgenomen. Afleidbare eigenschappen zijn eigenschappen die niet direct worden geregistreerd, maar die kunnen worden afgeleid uit andere geregistreerde eigenschappen, bijvoorbeeld door berekeningen of logica toe te passen op de geregistreerde gegevens.

Afleidbare eigenschappen hebben in het gegevensmodel de waarde `Ja` voor het metagegeven <a data-cite="MIM12#metagegeven-indicatie-afleidbaar">indicatie afleidbaar</a> en zijn in de modeldiagrammen aangeduid met een `/` als prefix bij de naam van de eigenschap.

## Modelleerregels

Het [[CIM-BG]] beschrijft per objecttype de modelleerprincipes en ruimtelijke relaties die gelden voor bestuurlijke gebieden. Zie de [detailbeschrijvingen in het CIM-BG](https://geonovum.github.io/bestuurlijke-gebieden-cm/#beschrijving-inhoud) voor de volledige uitwerking per objecttype. De belangrijkste regels zijn:

- Gemeentegebieden vormen samen een vlakdekkend geheel binnen een provinciegebied, zonder gaten of overlappingen.
- Provinciegebieden vormen samen een vlakdekkend geheel binnen een provinciaal ingedeeld landgebied, zonder gaten of overlappingen.
- Elk gemeentegebied ligt in precies één provinciegebied en in precies één veiligheidsregiogebied.
- Elk provinciegebied ligt in precies één landgebied.
