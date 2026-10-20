## Registratie {#informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/nen3610#Registratie</td>
</tr>
<tr>
<th>Naam</th>
<td>Registratie</td>
</tr>
<tr>
<th>Herkomst</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Definitie</th>
<td>Vastlegging van een versie van een set gegevens.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://definities.geostandaarden.nl/nen3610-2022/id/begrip/objectregistratie ">http://definities.geostandaarden.nl/nen3610-2022/id/begrip/objectregistratie </a></td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-11-18</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table id="informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie_generalisatie_entiteit" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#Registratie.generalisatie-Entiteit</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie">Registratie</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_prov_o_objecttype_entiteit">Entiteit</a>
</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2026-02-04</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

<section class="notoc">
<h3>Overzicht attribuutsoorten</h3>    
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 18%"></colgroup>
<colgroup style="width: 7%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie_attribuutsoort_versie">versie</a>
</td>
<td>
Versieaanduiding van een informatieobject.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie_attribuutsoort_status_registratie">statusRegistratie</a>
</td>
<td>
Fase van de levenscyclus waarin een object zich bevindt.</td>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_registratiegegevens_enumeratie_status_registratie">StatusRegistratie</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie_attribuutsoort_begin_geldigheid">beginGeldigheid</a>
</td>
<td>
Start van de periode waarop deze versie van het informatieobject geldig is.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Date</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie_attribuutsoort_eind_geldigheid">eindGeldigheid</a>
</td>
<td>
Eind van de periode waarop deze versie van het informatieobject geldig is. De periode is tot aan deze tijdsaanduiding. Wanneer deze waarde niet is ingevuld, is de versie nog geldig.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> Date</a>
</td>
<td>
0..1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie_attribuutsoort_tijdstip_registratie">tijdstipRegistratie</a>
</td>
<td>
Tijdsaanduiding van het moment waarop deze versie van het informatieobject is opgenomen in de registratie.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> DateTime</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie_attribuutsoort_eind_registratie">eindRegistratie</a>
</td>
<td>
Eind van de periode dat deze versie van het informatieobject actueel is in de registratie. De periode is tot aan deze tijdsaanduiding. Wanneer deze waarde niet is ingevuld, is de versie nog actueel.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> DateTime</a>
</td>
<td>
0..1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h3>Overzicht Relatiesoorten</h3>
<table style="width: 100%">
<colgroup style="width: 25%"></colgroup>
<colgroup style="width: 50%"></colgroup>
<colgroup style="width: 18%"></colgroup>
<colgroup style="width: 7%"></colgroup>
<tbody>
<tr>
  <th>Naam</th>
  <th>Definitie</th>
  <th>Type</th>
  <th>Kard</th>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie_relatiesoort_afgeleid_van">afgeleidVan</a>
</td>
<td>
Een afleiding is een transformatie van een entiteit naar een andere, een update van een entiteit die resulteert in een nieuwe entiteit, of de constructie van een nieuwe entiteit op basis van een reeds bestaande entiteit.</td>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_brondocument">Brondocument</a>
</td>
<td>
0..*</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h3>Details attribuutsoorten</h3>
<section class="notoc" id="informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie_attribuutsoort_versie">
<h4>versie</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/nen3610#versie</td>
</tr>
<tr>
<th>Naam</th>
<td>versie</td>
</tr>
<tr>
<th>Herkomst</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Definitie</th>
<td>Versieaanduiding van een informatieobject.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://definities.geostandaarden.nl/nen3610-2022/id/begrip/versie">http://definities.geostandaarden.nl/nen3610-2022/id/begrip/versie</a></td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-11-18</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Ja</td>
</tr>
<tr>
<th>heeft tijdlijn geldigheid</th>
<td>Nee</td>
</tr>
<tr>
<th>heeft tijdlijn registratie</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Authentiek</th>
<td>Overig</td>
</tr>
<tr>
<th>Indicatie afleidbaar</th>
<td>Nee</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Mogelijk geen waarde</th>
<td>Nee</td>
</tr>
<tr>
<th>Lengte</th>
<td>1..50</td>
</tr>
<tr>
<th>Patroon</th>
<td>Waarde van attribuut versie mag maximaal 50 karakters bevatten.</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie_attribuutsoort_status_registratie">
<h4>statusRegistratie</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#statusRegistratie</td>
</tr>
<tr>
<th>Naam</th>
<td>statusRegistratie</td>
</tr>
<tr>
<th>Alias</th>
<td>status registratie</td>
</tr>
<tr>
<th>Herkomst</th>
<td>LGM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Fase van de levenscyclus waarin een object zich bevindt.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>LGM-BG</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-11-18</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>heeft tijdlijn geldigheid</th>
<td>Nee</td>
</tr>
<tr>
<th>heeft tijdlijn registratie</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Authentiek</th>
<td>Overig</td>
</tr>
<tr>
<th>Indicatie afleidbaar</th>
<td>Ja</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Mogelijk geen waarde</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie_attribuutsoort_begin_geldigheid">
<h4>beginGeldigheid</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/nen3610#beginGeldigheid</td>
</tr>
<tr>
<th>Naam</th>
<td>beginGeldigheid</td>
</tr>
<tr>
<th>Alias</th>
<td>begin geldigheid</td>
</tr>
<tr>
<th>Herkomst</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Definitie</th>
<td>Start van de periode waarop deze versie van het informatieobject geldig is.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://definities.geostandaarden.nl/nen3610-2022/id/begrip/begin_geldigheid">http://definities.geostandaarden.nl/nen3610-2022/id/begrip/begin_geldigheid</a></td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-11-18</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>heeft tijdlijn geldigheid</th>
<td>Nee</td>
</tr>
<tr>
<th>heeft tijdlijn registratie</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Authentiek</th>
<td>Overig</td>
</tr>
<tr>
<th>Indicatie afleidbaar</th>
<td>Nee</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Mogelijk geen waarde</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie_attribuutsoort_eind_geldigheid">
<h4>eindGeldigheid</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bestuurlijke-gebieden#eindGeldigheid</td>
</tr>
<tr>
<th>Naam</th>
<td>eindGeldigheid</td>
</tr>
<tr>
<th>Alias</th>
<td>eind geldigheid</td>
</tr>
<tr>
<th>Herkomst</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Definitie</th>
<td>Eind van de periode waarop deze versie van het informatieobject geldig is. De periode is tot aan deze tijdsaanduiding. Wanneer deze waarde niet is ingevuld, is de versie nog geldig.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://definities.geostandaarden.nl/nen3610-2022/id/begrip/eind_geldigheid">http://definities.geostandaarden.nl/nen3610-2022/id/begrip/eind_geldigheid</a></td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-11-18</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>heeft tijdlijn geldigheid</th>
<td>Nee</td>
</tr>
<tr>
<th>heeft tijdlijn registratie</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>0..1</td>
</tr>
<tr>
<th>Authentiek</th>
<td>Overig</td>
</tr>
<tr>
<th>Indicatie afleidbaar</th>
<td>Nee</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Mogelijk geen waarde</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie_attribuutsoort_tijdstip_registratie">
<h4>tijdstipRegistratie</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/nen3610#tijdstipRegistratie</td>
</tr>
<tr>
<th>Naam</th>
<td>tijdstipRegistratie</td>
</tr>
<tr>
<th>Alias</th>
<td>tijdstip registratie</td>
</tr>
<tr>
<th>Herkomst</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Definitie</th>
<td>Tijdsaanduiding van het moment waarop deze versie van het informatieobject is opgenomen in de registratie.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://definities.geostandaarden.nl/nen3610-2022/id/begrip/tijdstip_registratie">http://definities.geostandaarden.nl/nen3610-2022/id/begrip/tijdstip_registratie</a></td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-11-18</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>heeft tijdlijn geldigheid</th>
<td>Nee</td>
</tr>
<tr>
<th>heeft tijdlijn registratie</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Authentiek</th>
<td>Overig</td>
</tr>
<tr>
<th>Indicatie afleidbaar</th>
<td>Nee</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Mogelijk geen waarde</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie_attribuutsoort_eind_registratie">
<h4>eindRegistratie</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/nen3610#eindRegistratie</td>
</tr>
<tr>
<th>Naam</th>
<td>eindRegistratie</td>
</tr>
<tr>
<th>Alias</th>
<td>eind registratie</td>
</tr>
<tr>
<th>Herkomst</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Definitie</th>
<td>Eind van de periode dat deze versie van het informatieobject actueel is in de registratie. De periode is tot aan deze tijdsaanduiding. Wanneer deze waarde niet is ingevuld, is de versie nog actueel.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://definities.geostandaarden.nl/nen3610-2022/id/begrip/eind_registratie">http://definities.geostandaarden.nl/nen3610-2022/id/begrip/eind_registratie</a></td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-11-18</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>heeft tijdlijn geldigheid</th>
<td>Nee</td>
</tr>
<tr>
<th>heeft tijdlijn registratie</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>0..1</td>
</tr>
<tr>
<th>Authentiek</th>
<td>Overig</td>
</tr>
<tr>
<th>Indicatie afleidbaar</th>
<td>Nee</td>
</tr>
<tr>
<th>Indicatie classificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>Mogelijk geen waarde</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>

<section class="notoc">
<h3>Details Relatiesoorten</h3>
<section class="notoc" id="informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie_relatiesoort_afgeleid_van">
<h4>afgeleidVan</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://www.w3.org/ns/prov#wasDerivedFrom</td>
</tr>
<tr>
<th>Naam</th>
<td>afgeleidVan</td>
</tr>
<tr>
<th>Herkomst</th>
<td>LGM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een afleiding is een transformatie van een entiteit naar een andere, een update van een entiteit die resulteert in een nieuwe entiteit, of de constructie van een nieuwe entiteit op basis van een reeds bestaande entiteit.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>PROV-O</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2026-02-06</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>heeft tijdlijn geldigheid</th>
<td>Nee</td>
</tr>
<tr>
<th>heeft tijdlijn registratie</th>
<td>Nee</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>0..*</td>
</tr>
<tr>
<th>Kardinaliteit relatie bron</th>
<td>0..*</td>
</tr>
<tr>
<th>Unidirectioneel</th>
<td>Ja</td>
</tr>
<tr>
<th>Aggregatietype</th>
<td>Geen</td>
</tr>
<tr>
<th>Authentiek</th>
<td>Overig</td>
</tr>
<tr>
<th>Indicatie afleidbaar</th>
<td>Nee</td>
</tr>
<tr>
<th>Mogelijk geen waarde</th>
<td>Nee</td>
</tr>
<tr>
<th>Bron</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie">Registratie</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_brondocument">Brondocument</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>
