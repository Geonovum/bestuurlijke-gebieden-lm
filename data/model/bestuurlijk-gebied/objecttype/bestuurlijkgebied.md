## BestuurlijkGebied {#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#BestuurlijkGebied</td>
</tr>
<tr>
<th>Naam</th>
<td>BestuurlijkGebied</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een bestuurlijk gebied is een registratieve ruimte die op basis van wet- of regelgeving als eenheid geldt van bestuurlijke verantwoordelijkheid.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Dit betreft bijvoorbeeld de gebieden behorende bij de vier formele bestuurslagen uit de Grondwet (Rijk, provincie, waterschap, gemeente), maar kan ook gebieden van bestuurlijke samenwerkingsverbanden met eigen politiek/bestuurlijke verantwoordelijkheid omvatten. Een voorbeeld daarvan betreft de veiligheidsregio’s.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/bestuurlijk_gebied">http://begrippen.geostandaarden.nl/bg/id/begrip/bestuurlijk_gebied</a></td>
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
<table id="informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_generalisatie_registratieve_ruimte" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#BestuurlijkGebied.generalisatie-RegistratieveRuimte</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied">BestuurlijkGebied</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_registratieve_ruimte">RegistratieveRuimte</a>
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
<a class="link" href="#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_attribuutsoort_identificatie">identificatie</a>
</td>
<td>
Unieke identificatiecode van een informatieobject binnen de context van een registratie.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_attribuutsoort_domein">domein</a>
</td>
<td>
Aanduiding van het domein waarbinnen de identificatie uniek is.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_attribuutsoort_naam">naam</a>
</td>
<td>
Naam van een object.</td>
<td>
<a class="external-link" href="https://docs.geostandaarden.nl/mim/mim/#primitief-datatype-1"> CharacterString</a>
</td>
<td>
0..1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_attribuutsoort_geometrie">geometrie</a>
</td>
<td>
Geometrische representatie van een gebied op land dat door een openbaar lichaam wordt bestuurd.</td>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_keuze_datatype__vlak_of_multivlak">VlakOfMultivlak</a>
</td>
<td>
1</td>
</tr>
<tr>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_attribuutsoort_geometrie_zonder_binnenwateren">geometrieZonderBinnenwateren</a>
</td>
<td>
Geometrische representatie van een gebied op land (zonder binnenwateren) dat door een openbaar lichaam wordt bestuurd.</td>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_keuze_datatype__vlak_of_multivlak">VlakOfMultivlak</a>
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
<a class="link" href="#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_relatiesoort_geregistreerd_met">geregistreerdMet</a>
</td>
<td>
Gegevens over de registratie van het object als informatieobject.</td>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie">Registratie</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h3>Details attribuutsoorten</h3>
<section class="notoc" id="informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_attribuutsoort_identificatie">
<h4>identificatie</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/nen3610#identificatie</td>
</tr>
<tr>
<th>Naam</th>
<td>identificatie</td>
</tr>
<tr>
<th>Herkomst</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Definitie</th>
<td>Unieke identificatiecode van een informatieobject binnen de context van een registratie.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Toelichting</th>
<td>&#39;identificatie&#39; is de identificatiecode die een object heeft binnen een registratie of binnen een ketenproces voor data-uitwisseling. Binnen de registratie of de data-uitwisseling is het object uniek identificeerbaar. In combinatie met het attribuut domein wordt een object hiermee uniek identificeerbaar op het niveau van verschillende registraties, uitwisselprocessen en ook wereldwijd uniek.
De reguliere expressie voor de toegestane tekens is: [a-zA-Z|0-9|_|.|-|\/|:|]</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://definities.geostandaarden.nl/nen3610-2022/id/begrip/identificatie">http://definities.geostandaarden.nl/nen3610-2022/id/begrip/identificatie</a></td>
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
<th>Patroon</th>
<td>Alleen de volgende karakters mogen in een waarde van het attribuut identificatie voorkomen: {&#39;A&#39; ... &#39;Z&#39;, &#39;a&#39; ... &#39;z&#39;, &#39;0&#39; ... &#39;9&#39;, &#39;_&#39;, &#39;-&#39;, &#39;,&#39;, &#39;.&#39;, &#39;/&#39;, &#39;:&#39;}</td>
</tr>
<tr>
<th>Formeel patroon</th>
<td>([a-z]|[A-Z]|[0-9]|\_|\-|\,|\.|\:|\/)+</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_attribuutsoort_domein">
<h4>domein</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/nen3610#domein</td>
</tr>
<tr>
<th>Naam</th>
<td>domein</td>
</tr>
<tr>
<th>Herkomst</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Definitie</th>
<td>Aanduiding van het domein waarbinnen de identificatie uniek is.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://definities.geostandaarden.nl/nen3610-2022/id/begrip/domein">http://definities.geostandaarden.nl/nen3610-2022/id/begrip/domein</a></td>
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
<th>Patroon</th>
<td>Alleen de volgende karakters mogen in een waarde van het attribuut domein voorkomen: {&#39;A&#39; ... &#39;Z&#39;, &#39;a&#39; ... &#39;z&#39;, &#39;0&#39; ... &#39;9&#39;, &#39;_&#39;, &#39;-&#39;, &#39;,&#39;, &#39;.&#39;, &#39;/&#39;, &#39;:&#39;}</td>
</tr>
<tr>
<th>Formeel patroon</th>
<td>([a-z]|[A-Z]|[0-9]|\_|\-|\,|\.|\:|\/)+</td>
</tr>
<tbody>
</tbody>
</table>
</section>
<section class="notoc" id="informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_attribuutsoort_naam">
<h4>naam</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#naam</td>
</tr>
<tr>
<th>Naam</th>
<td>naam</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Naam van een object.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Breed geaccepteerde benaming van een gebied zoals deze is toegekend of zoals deze in de volksmond bekend staat.</td>
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
<td>Ja</td>
</tr>
<tr>
<th>heeft tijdlijn registratie</th>
<td>Ja</td>
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
<section class="notoc" id="informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_attribuutsoort_geometrie">
<h4>geometrie</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#geometrie</td>
</tr>
<tr>
<th>Naam</th>
<td>geometrie</td>
</tr>
<tr>
<th>Herkomst</th>
<td>EMSO</td>
</tr>
<tr>
<th>Definitie</th>
<td>Geometrische representatie van een gebied op land dat door een openbaar lichaam wordt bestuurd.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>EMSO</td>
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
<td>Ja</td>
</tr>
<tr>
<th>heeft tijdlijn registratie</th>
<td>Ja</td>
</tr>
<tr>
<th>Kardinaliteit</th>
<td>1</td>
</tr>
<tr>
<th>Authentiek</th>
<td>Landelijk kerngegeven</td>
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
<section class="notoc" id="informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_attribuutsoort_geometrie_zonder_binnenwateren">
<h4>geometrieZonderBinnenwateren</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#geometrieZonderBinnenwateren</td>
</tr>
<tr>
<th>Naam</th>
<td>geometrieZonderBinnenwateren</td>
</tr>
<tr>
<th>Herkomst</th>
<td>LGM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Geometrische representatie van een gebied op land (zonder binnenwateren) dat door een openbaar lichaam wordt bestuurd.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>LGM-BG</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2026-10-05</td>
</tr>
<tr>
<th>Identificerend</th>
<td>Nee</td>
</tr>
<tr>
<th>heeft tijdlijn geldigheid</th>
<td>Ja</td>
</tr>
<tr>
<th>heeft tijdlijn registratie</th>
<td>Ja</td>
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
<section class="notoc" id="informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied_relatiesoort_geregistreerd_met">
<h4>geregistreerdMet</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/nen3610#geregistreerdMet</td>
</tr>
<tr>
<th>Naam</th>
<td>geregistreerdMet</td>
</tr>
<tr>
<th>Alias</th>
<td>geregistreerd met</td>
</tr>
<tr>
<th>Herkomst</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Definitie</th>
<td>Gegevens over de registratie van het object als informatieobject.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>NEN 3610:2022 nl</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://definities.geostandaarden.nl/nen3610-2022/id/begrip/registratiegegevens">http://definities.geostandaarden.nl/nen3610-2022/id/begrip/registratiegegevens</a></td>
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
<th>Kardinaliteit relatie bron</th>
<td>1</td>
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
<a class="link" href="#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied">BestuurlijkGebied</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_registratiegegevens_objecttype_registratie">Registratie</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>
