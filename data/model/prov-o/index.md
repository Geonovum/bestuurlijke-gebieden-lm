## View PROV-O {#informatiemodel_lgm_bg_view_prov_o}

<figure data-md-diagram="ac43bc70-70d3-3601-8785-ebd0398d1368">
<div data-include="data/model/prov-o/package-view.svg" data-include-format="html"><img src="data/model/prov-o/package-view.png" alt="View PROV-O" loading="lazy"></div>
<figcaption>View PROV-O</figcaption>
</figure>

### Objecttypen

#### Entiteit {#informatiemodel_lgm_bg_view_prov_o_objecttype_entiteit}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://www.w3.org/ns/prov#Entity</td>
</tr>
<tr>
<th>Naam</th>
<td>Entiteit</td>
</tr>
<tr>
<th>Herkomst</th>
<td>LGM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een entiteit is een fysiek, digitaal, conceptueel of ander soort ding met een aantal vaste aspecten; entiteiten kunnen echt of denkbeeldig zijn.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>PROV-O</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2026-02-04</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Ja</td>
</tr>
<tbody>
</tbody>
</table>

#### Actor {#informatiemodel_lgm_bg_view_prov_o_objecttype_actor}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://www.w3.org/ns/prov#Agent</td>
</tr>
<tr>
<th>Naam</th>
<td>Actor</td>
</tr>
<tr>
<th>Herkomst</th>
<td>LGM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een actor is een entiteit die verantwoordelijk is voor het plaatsvinden van een activiteit, het bestaan van een entiteit, of voor de activiteit van een andere actor.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>PROV-O</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2026-02-04</td>
</tr>
<tr>
<th>Indicatie abstract object</th>
<td>Ja</td>
</tr>
<tbody>
</tbody>
</table>

#### Organisatie {#informatiemodel_lgm_bg_view_prov_o_objecttype_organisatie}

<table style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://www.w3.org/ns/prov#Organization</td>
</tr>
<tr>
<th>Naam</th>
<td>Organisatie</td>
</tr>
<tr>
<th>Herkomst</th>
<td>LGM-BG</td>
</tr>
<tr>
<th>Definitie</th>
<td>Een organisatie is een actor in de vorm van een sociaal of legaal samenwerkingsverband.</td>
</tr>
<tr>
<th>Herkomst definitie</th>
<td>PROV-O</td>
</tr>
<tr>
<th>Datum opname</th>
<td>2026-02-04</td>
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
<table id="informatiemodel_lgm_bg_view_prov_o_objecttype_organisatie_generalisatie_actor" style="width: 100%">
<colgroup style="width: 30%"></colgroup>
<colgroup style="width: 70%"></colgroup>
<tr>
<th>Identificatie</th>
<td>http://www.w3.org/ns/prov#Organisatie.generalisatie-Actor</td>
</tr>
<tr>
<th>Subtype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_prov_o_objecttype_organisatie">Organisatie</a>
</td>
</tr>
<tr>
<th>Supertype</th>
<td>
<a class="link" href="#informatiemodel_lgm_bg_view_prov_o_objecttype_actor">Actor</a>
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
