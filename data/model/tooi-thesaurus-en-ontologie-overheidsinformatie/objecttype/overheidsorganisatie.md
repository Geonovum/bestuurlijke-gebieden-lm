## Overheidsorganisatie {#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_overheidsorganisatie}

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
<h3>Details attribuutsoorten</h3>
<section class="notoc" id="informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_overheidsorganisatie_attribuutsoort_uri">
<h4>uri</h4>
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
<h4>naam</h4>
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
<h4>officieleNaamExclSoort</h4>
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
<h4>officieleNaamInclSoort</h4>
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
<h4>organisatiecode</h4>
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
