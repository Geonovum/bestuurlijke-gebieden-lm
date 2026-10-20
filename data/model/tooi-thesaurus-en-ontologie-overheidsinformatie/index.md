## View TOOI - Thesaurus en Ontologie Overheidsinformatie {#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie}

<figure data-md-diagram="4aa3f909-f9d8-37bd-9d1f-33bf97e67eed">
<div data-include="data/model/tooi-thesaurus-en-ontologie-overheidsinformatie/package-view.svg" data-include-format="html"><img src="data/model/tooi-thesaurus-en-ontologie-overheidsinformatie/package-view.png" alt="View TOOI - Thesaurus en Ontologie Overheidsinformatie" loading="lazy"></div>
<figcaption>View TOOI - Thesaurus en Ontologie Overheidsinformatie</figcaption>
</figure>

### Objecttypen

#### Overheidsorganisatie {#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_overheidsorganisatie}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/Overheidsorganisatie</td>
</tr>
<tr>
<th>Naam</th>
<td>Overheidsorganisatie</td>
</tr>
<tr>
<th>Herkomst</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een organisatie die namens de overheid taken uitvoert en onder het gezag en toezicht van de overheid valt.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/overheidsorganisatie">http://begrippen.geostandaarden.nl/bg/id/begrip/overheidsorganisatie</a></td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-11-18</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Ja</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table id="informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_overheidsorganisatie_generalisatie_organisatie" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/Overheidsorganisatie.generalisatie-Organisatie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_overheidsorganisatie">Overheidsorganisatie</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_prov_o_objecttype_organisatie">Organisatie</a>
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
<h5>Overzicht attribuutsoorten</h5>    
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
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_overheidsorganisatie_attribuutsoort_uri">uri</a>
</td>
<td>
De URI van het object.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> URI</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_overheidsorganisatie_attribuutsoort_naam">naam</a>
</td>
<td>
De voorkeursnaam van de organisatie</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_overheidsorganisatie_attribuutsoort_officiele_naam_excl_soort">officieleNaamExclSoort</a>
</td>
<td>
De officiële naam van de organisatie zonder soortaanduiding, bijvoorbeeld &#39;&#39;s-Gravenhage&#39;</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_overheidsorganisatie_attribuutsoort_officiele_naam_incl_soort">officieleNaamInclSoort</a>
</td>
<td>
De officiële naam van de organisatie met soortaanduiding, bijvoorbeeld &#39;gemeente &#39;s-Gravenhage&#39;</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_overheidsorganisatie_attribuutsoort_organisatiecode">organisatiecode</a>
</td>
<td>
De organisatiecode.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h5>Details attribuutsoorten</h5>
<section class="notoc" id="informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_overheidsorganisatie_attribuutsoort_uri">
<h6>uri</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://purl.org/dc/terms/identifier</td>
</tr>
<tr>
<th>Naam</th>
<td>uri</td>
</tr>
<tr>
<th>Herkomst</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Definitie</th>
<td>De URI van het object.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2026-02-04</td>
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
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_overheidsorganisatie_attribuutsoort_naam">
<h6>naam</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://www.w3.org/2000/01/rdf-schema#label</td>
</tr>
<tr>
<th>Naam</th>
<td>naam</td>
</tr>
<tr>
<th>Herkomst</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Definitie</th>
<td>De voorkeursnaam van de organisatie</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
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
<section class="notoc" id="informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_overheidsorganisatie_attribuutsoort_officiele_naam_excl_soort">
<h6>officieleNaamExclSoort</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/officieleNaamExclSoort</td>
</tr>
<tr>
<th>Naam</th>
<td>officieleNaamExclSoort</td>
</tr>
<tr>
<th>Alias</th>
<td>Officiële naam exclusief soort</td>
</tr>
<tr>
<th>Herkomst</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Definitie</th>
<td>De officiële naam van de organisatie zonder soortaanduiding, bijvoorbeeld &#39;&#39;s-Gravenhage&#39;</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2026-02-04</td>
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
<section class="notoc" id="informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_overheidsorganisatie_attribuutsoort_officiele_naam_incl_soort">
<h6>officieleNaamInclSoort</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/officieleNaamInclSoort</td>
</tr>
<tr>
<th>Naam</th>
<td>officieleNaamInclSoort</td>
</tr>
<tr>
<th>Alias</th>
<td>Officiële naam inclusief soort</td>
</tr>
<tr>
<th>Herkomst</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Definitie</th>
<td>De officiële naam van de organisatie met soortaanduiding, bijvoorbeeld &#39;gemeente &#39;s-Gravenhage&#39;</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
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
<section class="notoc" id="informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_overheidsorganisatie_attribuutsoort_organisatiecode">
<h6>organisatiecode</h6>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/organisatiecode</td>
</tr>
<tr>
<th>Naam</th>
<td>organisatiecode</td>
</tr>
<tr>
<th>Alias</th>
<td>Organisatiecode</td>
</tr>
<tr>
<th>Herkomst</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Definitie</th>
<td>De organisatiecode.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Deze is uniek voor elke organisatie en fungeert bovendien als local name (gegeven de namespace-conventies binnen de registers).</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/organisatiecode">http://begrippen.geostandaarden.nl/bg/id/begrip/organisatiecode</a></td>
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
</section>

#### RegionaalOpenbaarLichaam {#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_regionaal_openbaar_lichaam}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/RegionaalOpenbaarLichaam</td>
</tr>
<tr>
<th>Naam</th>
<td>RegionaalOpenbaarLichaam</td>
</tr>
<tr>
<th>Alias</th>
<td>Regionaal openbaar lichaam</td>
</tr>
<tr>
<th>Herkomst</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een regionaal openbaar lichaam is, in de bestuurlijke indeling van het Koninkrijk der Nederlanden, een overheid die wettelijk bepaalde taken uitvoert binnen een bepaald ruimtelijk gebied.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Toelichting</th>
<td>De belangrijkste regionale openbare lichamen zijn het Rijk, de provincies, de gemeenten en de waterschappen. De provincies en gemeenten worden in artikel 123 en verder van de Nederlandse Grondwet geregeld. De waterschappen in artikel 133.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/regionaal_openbaar_lichaam">http://begrippen.geostandaarden.nl/bg/id/begrip/regionaal_openbaar_lichaam</a></td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-11-18</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Ja</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table id="informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_regionaal_openbaar_lichaam_generalisatie_overheidsorganisatie" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/RegionaalOpenbaarLichaam.generalisatie-Overheidsorganisatie</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_regionaal_openbaar_lichaam">RegionaalOpenbaarLichaam</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_overheidsorganisatie">Overheidsorganisatie</a>
</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-11-18</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

#### OpenbaarLichaamUitGemeenschappelijkeRegeling {#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_openbaar_lichaam_uit_gemeenschappelijke_regeling}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/OpenbaarLichaamUitGemeenschappelijkeRegeling</td>
</tr>
<tr>
<th>Naam</th>
<td>OpenbaarLichaamUitGemeenschappelijkeRegeling</td>
</tr>
<tr>
<th>Alias</th>
<td>Openbaar lichaam uit gemeenschappelijke regeling</td>
</tr>
<tr>
<th>Herkomst</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een organisatie die in het leven is geroepen om een gemeenschappelijke regeling uit te voeren uit hoofde van de Wet gemeenschappelijke regelingen (Wgr).</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/openbaar_lichaam_uit_gemeenschappelijke_regeling">http://begrippen.geostandaarden.nl/bg/id/begrip/openbaar_lichaam_uit_gemeenschappelijke_regeling</a></td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-11-18</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Ja</td>
</tr>
<tbody>
</tbody>
</table>

<section class="notoc">
<h5>Overzicht generalisaties</h5>
<table id="informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_openbaar_lichaam_uit_gemeenschappelijke_regeling_generalisatie_regionaal_openbaar_lichaam" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/OpenbaarLichaamUitGemeenschappelijkeRegeling.generalisatie-RegionaalOpenbaarLichaam</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_openbaar_lichaam_uit_gemeenschappelijke_regeling">OpenbaarLichaamUitGemeenschappelijkeRegeling</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_regionaal_openbaar_lichaam">RegionaalOpenbaarLichaam</a>
</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-11-18</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

#### Gemeente {#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_gemeente}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/Gemeente</td>
</tr>
<tr>
<th>Naam</th>
<td>Gemeente</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een gemeente is het kleinste territoriaal openbaar lichaam met algemene bevoegdheden.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/gemeente">http://begrippen.geostandaarden.nl/bg/id/begrip/gemeente</a></td>
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
<table id="informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_gemeente_generalisatie_regionaal_openbaar_lichaam" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/Gemeente.generalisatie-RegionaalOpenbaarLichaam</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_gemeente">Gemeente</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_regionaal_openbaar_lichaam">RegionaalOpenbaarLichaam</a>
</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-11-18</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

#### Provincie {#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_provincie}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/Provincie</td>
</tr>
<tr>
<th>Naam</th>
<td>Provincie</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een provincie is een territoriaal openbaar lichaam met algemene bevoegdheden tussen gemeente en Rijk.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/provincie">http://begrippen.geostandaarden.nl/bg/id/begrip/provincie</a></td>
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
<table id="informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_provincie_generalisatie_regionaal_openbaar_lichaam" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/Provincie.generalisatie-RegionaalOpenbaarLichaam</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_provincie">Provincie</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_regionaal_openbaar_lichaam">RegionaalOpenbaarLichaam</a>
</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-11-18</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

#### Rijk {#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_rijk}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/Rijk</td>
</tr>
<tr>
<th>Naam</th>
<td>Rijk</td>
</tr>
<tr>
<th>Alias</th>
<td>De Rijksoverheid</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>De klasse Rijk is de (singleton-) klasse van onderdelen van de Nederlandse overheid die wettelijke taken hebben op landelijk niveau: de ‘centrale overheid’</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/rijk">http://begrippen.geostandaarden.nl/bg/id/begrip/rijk</a></td>
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
<table id="informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_rijk_generalisatie_regionaal_openbaar_lichaam" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/Rijk.generalisatie-RegionaalOpenbaarLichaam</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_rijk">Rijk</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_regionaal_openbaar_lichaam">RegionaalOpenbaarLichaam</a>
</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-11-18</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

#### Waterschap {#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_waterschap}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/Waterschap</td>
</tr>
<tr>
<th>Naam</th>
<td>Waterschap</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een waterschap is een territoriaal openbaar lichaam dat uitsluitend bevoegd is met betrekking tot de waterhuishouding.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>TOOI - Ontologie 1.6.2</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/waterschap">http://begrippen.geostandaarden.nl/bg/id/begrip/waterschap</a></td>
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
<table id="informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_waterschap_generalisatie_regionaal_openbaar_lichaam" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/Waterschap.generalisatie-RegionaalOpenbaarLichaam</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_waterschap">Waterschap</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_regionaal_openbaar_lichaam">RegionaalOpenbaarLichaam</a>
</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-11-18</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>

#### Veiligheidsregio {#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_veiligheidsregio}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/Veiligheidsregio</td>
</tr>
<tr>
<th>Naam</th>
<td>Veiligheidsregio</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een veiligheidsregio is een openbaar lichaam voor de samenwerking door verschillende besturen en diensten ten aanzien van taken op het terrein van brandweerzorg, rampenbeheersing, crisisbeheersing, geneeskundige hulpverlening en handhaving van de openbare orde en veiligheid.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>https://www.vrgooienvechtstreek.nl/onze-organisatie/de-veiligheidsregio</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/veiligheidsregio">http://begrippen.geostandaarden.nl/bg/id/begrip/veiligheidsregio</a></td>
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
<table id="informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_veiligheidsregio_generalisatie_openbaar_lichaam_uit_gemeenschappelijke_regeling" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>https://identifier.overheid.nl/tooi/def/ont/Veiligheidsregio.generalisatie-OpenbaarLichaamUitGemeenschappelijkeRegeling</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_veiligheidsregio">Veiligheidsregio</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_openbaar_lichaam_uit_gemeenschappelijke_regeling">OpenbaarLichaamUitGemeenschappelijkeRegeling</a>
</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2025-11-18</td>
</tr>
<tr>
<th>Mixin</th>
<td>Nee</td>
</tr>
<tbody>
</tbody>
</table>
</section>
