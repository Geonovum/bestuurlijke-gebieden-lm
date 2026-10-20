## Waterschapsgebied {#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_waterschapsgebied}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#Waterschapsgebied</td>
</tr>
<tr>
<th>Naam</th>
<td>Waterschapsgebied</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Bij wet afgebakend gedeelte van het grondgebied van Nederland, onder zeggenschap van een waterschap welke de waterstaatskundige verzorging van dat gebied ten doel heeft, ingesteld op basis van artikel 133 van de Grondwet en de Waterschapswet.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>Grondwet, Waterschapswet en INSPIRE</td>
</tr>
<tr>
<th>Toelichting</th>
<td>Het &#39;Waterschapsgebied&#39; wordt aangeduid met de administratieve grens gebruikt. De Waterschapswet gaat op in de Omgevingswet. De Administratieve grens is grens die in de Omgevingswet als waterschapsgrens wordt gehanteerd en overeenkomt met de registratieve grens in de SOR en in INSPIRE.

Het Administratief gebied betreft de geografische representatie van de verkiezingsgrenzen zoals die door de waterschappen zijn vastgelegd. Het gaat bij dit begrip nadrukkelijk om het grondgebied en niet om de juridische entiteit (bevoegd gezag).

Deze grens is inclusief de grote wateren die niet door de waterschappen beheerd worden, maar door Rijkswaterstaat. Het gaat dus om het gebied waarin het waterschap de verkiezingen uitschrijft.</td>
</tr>
<tr>
<th>Begrip</th>
<td>
<a href="http://begrippen.geostandaarden.nl/bg/id/begrip/waterschapsgebied">http://begrippen.geostandaarden.nl/bg/id/begrip/waterschapsgebied</a></td>
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
<table id="informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_waterschapsgebied_generalisatie_bestuurlijk_gebied" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#Waterschapsgebied.generalisatie-BestuurlijkGebied</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_waterschapsgebied">Waterschapsgebied</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_bestuurlijk_gebied">BestuurlijkGebied</a>
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
<a class="link" href="#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_waterschapsgebied_relatiesoort_is_waterschapsgebied_van">isWaterschapsgebiedVan</a>
</td>
<td>
Relatie die aangeeft dat dit object een waterschapsgebied van een regionaal openbaar lichaam is.</td>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_waterschap">Waterschap</a>
</td>
<td>
1</td>
</tr>
</tbody>
</table>
</section>

<section class="notoc">
<h3>Details Relatiesoorten</h3>
<section class="notoc" id="informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_waterschapsgebied_relatiesoort_is_waterschapsgebied_van">
<h4>isWaterschapsgebiedVan</h4>
<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://modellen.geostandaarden.nl/def/bg#isWaterschapsgebiedVan</td>
</tr>
<tr>
<th>Naam</th>
<td>isWaterschapsgebiedVan</td>
</tr>
<tr>
<th>Alias</th>
<td>is waterschapsgebied van</td>
</tr>
<tr>
<th>Herkomst</th>
<td>CIM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Relatie die aangeeft dat dit object een waterschapsgebied van een regionaal openbaar lichaam is.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>CIM-BG</td>
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
<td>Landelijk kerngegeven</td>
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
<a class="link" href="#informatiemodel_lgm_bg_domein_bestuurlijk_gebied_objecttype_waterschapsgebied">Waterschapsgebied</a>
</td>
</tr>
<tr>
<th>Doel</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_tooi_thesaurus_en_ontologie_overheidsinformatie_objecttype_waterschap">Waterschap</a>
</td>
</tr>
<tbody>
</tbody>
</table>
</section>
</section>
