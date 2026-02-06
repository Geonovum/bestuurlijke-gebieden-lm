# Overzicht

## Naam en Acroniemen

Logisch Gegevensmodel Bestuurlijke Gebieden (LGM-BG)

## Definitie

Het LGM-BG beschrijft de gegevens die nodig zijn om bestuurlijke gebieden te registreren, beheren en uitwisselen. Het is een logische uitwerking van het Conceptueel Informatiemodel Bestuurlijke Gebieden [[CIM-BG]].

## Beschrijving

Op basis van het [[CIM-BG]] is het mogelijk om meerdere logische gegevensmodellen te maken, afhankelijk van de beoogde implementatie. Dit logisch gegevensmodel is opgesteld als basis voor de Basisvoorziening Bestuurlijke Gebieden (BVBG).

Het LGM-BG is een logisch informatiemodel conform de [[MIM12]] standaard (niveau 3). Dit betekent dat het model de gegevensstructuur beschrijft op een implementatie-onafhankelijke manier, maar wel met voldoende detail om als basis te dienen voor technische implementaties zoals API-specificaties en databaseschema's.

Inhoudelijk is het LGM-BG afgeleid van het [[CIM-BG]], dat weer is gebaseerd op [[NEN3610-2022]]. Het logisch model voegt daaraan de registratiegegevens, identificatie en overige implementatieaspecten toe die in de [algemene uitgangspunten](#algemene-uitgangspunten) zijn beschreven.

## Inhoud van het model

### Bestuurlijke gebieden

Dit domein beschrijft de bestuurlijke gebieden zelf. Het abstracte objecttype [`RegistratieveRuimte`](#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_registratieve_ruimte) vormt de basis, met [`BestuurlijkGebied`](#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied) als specialisatie. De bestuurlijke gebieden volgen de bestuurlijke indeling van Nederland: het [`Landgebied`](#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_landgebied) is onderverdeeld in [`Provinciegebieden`](#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_provinciegebied), die weer zijn onderverdeeld in [`Gemeentegebieden`](#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_gemeentegebied). Daarnaast kent het model [`Waterschapsgebieden`](#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_waterschapsgebied) en [`Veiligheidsregiogebieden`](#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_veiligheidsregiogebied), die een eigen ruimtelijke indeling kennen die niet samenvalt met de provinciale of gemeentelijke indeling.

Naast de gebieden aan de landszijde van de [basislijn](https://geonovum.github.io/bestuurlijke-gebieden-cm/#maritieme-zones) beschrijft het domein ook de maritieme zones die onder de bestuurlijke verantwoordelijkheid van het Rijk vallen: de [`TerritorialeZee`](#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_territoriale_zee), [`AansluitendeZone`](#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_aansluitende_zone), [`ExclusieveEconomischeZone`](#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_exclusieve_economische_zone) en het [`ContinentaalPlat`](#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_continentaal_plat). Deze zones zijn gemodelleerd als specialisatie van [`MaritiemeZone`](#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_maritieme_zone).

Zie het [[CIM-BG]] voor de [conceptuele beschrijving](https://geonovum.github.io/bestuurlijke-gebieden-cm/#beschrijving-inhoud) van deze objecttypen en hun onderlinge relaties.

### Registratiegegevens

Het model beschrijft ook de gegevens die nodig zijn voor het beheren van objectregistraties. Elk object in het model wordt gekoppeld aan een [`Registratie`](#informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie) die de versie, tijdlijnen en status van de gegevens vastlegt. De herkomst van gegevens wordt bijgehouden via een verwijzing naar een [`Bronentiteit`](#informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_bronentiteit), waarvan [`Brondocument`](#informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_brondocument) een specifieke vorm is. Zie [Registratiegegevens](#registratiegegevens) in de algemene uitgangspunten voor een toelichting op het bitemporale historiemodel en het herkomstmodel.

### Externe modellen

Tot slot bevat het model een extern package en twee views op externe modellen. Een <a data-cite="MIM12#extern">extern package</a> is in [[MIM12]] een groepering van modelelementen die een externe instantie beheert en beschikbaar stelt aan een informatiemodel en die in het informatiemodel ongewijzigd gebruikt worden. Een <a data-cite="MIM12#view">view</a> is een groepering van modelelementen die gespecificeerd zijn in een extern informatiemodel en vanuit het perspectief van het eigen informatiemodel inzicht geeft welke gegevens van deze objecttypen relevant zijn binnen het eigen informatiemodel. In beide gevallen worden de objecttypen niet door het eigen model beheerd, maar door een extern model of een externe registratie. Door deze op te nemen kan het eigen model verwijzen naar externe objecttypen en ze in samenhang met de eigen gegevens uitleveren.

#### Extern NEN 3610

Het LGM-BG is een extensie op het Basismodel Geo-informatie [[NEN3610-2022]]. Het model bevat een extern package met de objecttypen uit NEN 3610 waarvan de objecttypen in het LGM-BG een specialisatie zijn. Dit betreft de hiërarchie [`GeoObject`](#informatiemodel_nen3610_domein_semantisch_model_objecttype_geo_object) > [`VirtueleRuimte`](#informatiemodel_nen3610_domein_semantisch_model_objecttype_virtuele_ruimte) > [`RegistratieveRuimte`](#informatiemodel_nen3610_domein_semantisch_model_objecttype_registratieve_ruimte). De `RegistratieveRuimte` uit het LGM-BG is gemodelleerd als specialisatie van de NEN 3610 `RegistratieveRuimte`.

#### View TOOI

Elk bestuurlijk gebied wordt bestuurd door een regionaal openbaar lichaam. De gegevens over overheidsorganisaties worden beheerd door KOOP in de TOOI-ontologie ([[TOOI-ONT-1.6.2]]). Het LGM-BG neemt een view op van een deel van deze ontologie, zodat de BVBG de gegevens over bestuurlijke gebieden en de bijbehorende overheidsorganisaties in samenhang kan uitleveren.

Via het objecttype [`RegionaalOpenbaarLichaam`](#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_regionaal_openbaar_lichaam) wordt de koppeling gelegd tussen een bestuurlijk gebied en de [`Overheidsorganisatie`](#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_overheidsorganisatie) die erover bestuurt. Voor samenwerkingsverbanden zoals veiligheidsregio's wordt het objecttype [`Samenwerkingsorganisatie`](#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_samenwerkingsorganisatie) gebruikt.

#### View PROV-O

Het LGM-BG past een deel van de W3C standaard [[PROV-O]] toe om herkomstgegevens op een gestandaardiseerde manier vast te leggen. De [`Registratie`](#informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie) is gemodelleerd als specialisatie van een PROV-O [`Entiteit`](#informatiemodel_lgm_bg_view_prov_o_objecttype_entiteit), waardoor deze kan worden toegeschreven aan een verantwoordelijke [`Actor`](#informatiemodel_lgm_bg_view_prov_o_objecttype_actor) en gekoppeld aan een primaire bron.

## Bronnen en afnemers

De geometrie van bestuurlijke gebieden wordt afgeleid uit verschillende bronnen. De belangrijkste afnemers gebruiken bestuurlijke gebieden voor het bepalen van bevoegd gezag en ruimtelijke afbakening. Zie het [[CIM-BG]] voor een [uitgebreide beschrijving van bronnen en afnemers](https://geonovum.github.io/bestuurlijke-gebieden-cm/#cim-bg-in-context).

## Standaarden

Het LGM-BG sluit aan op de volgende standaarden:

- [[NEN3610-2022]] — Basismodel Geo-informatie, voor identificatie, tijdlijnen en geometrie
- [[MIM12]] — Metamodel Informatie Modellering, voor de structuur van het gegevensmodel
- [[TOOI-ONT-1.6.2]] — Thesaurus en Ontologie Overheidsinformatie, voor de beschrijving van overheidsorganisaties
- [[PROV-O]] — W3C standaard voor het beschrijven van herkomst
- [[EMSO]] — Eisen aan model samenhangende objectenregistratie, voor de modelleeruitgangspunten

Zie het [[CIM-BG]] voor een [uitgebreide beschrijving van de standaarden](https://geonovum.github.io/bestuurlijke-gebieden-cm/#standaarden-en-organisaties) en hun toepassing.
