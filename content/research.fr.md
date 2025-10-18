---
title: "Recherche"
# description: "Here are listed my professional as well as my academic backgrounds."
cascade:
  showReadingTime: false
layout: "simple"
---

<hr>

<span style='text-align: justify;'>

Rodrigue <span style="font-variant:small-caps;">Govan</span> est titulaire d'un Doctorat en Informatique (_Data Science_). L'intitulé de sa thèse est "_Apprentissage profond des graphes attribués pour la cartographie du risque de leptospirose_". Il a défendu sa thèse le 21 Août 2025 à l'Université de la Nouvelle-Calédonie.

Cette thèse a été réalisée sous la supervision de <a href="https://isea.unc.nc/membres/selmaoui-folcher/" target="_blank">Nazha <span style="font-variant:small-caps;">Selmaoui-Folcher</span></a>, Professeur des Universités en Informatique à l'Université de la Nouvelle-Calédonie, et <a href="https://www.philippe-fournier-viger.com" target="_blank">Philippe <span style="font-variant:small-caps;">Fournier-Viger</span></a>, Professeur en Informatique à l'Université de Shenzhen (Chine).

Les membres du jury de la thèse sont les suivants :
<ul style="margin-top:-1em">
  <li style="line-height: 150%">
    Christophe <span style="font-variant:small-caps;">Menkès</span>, Directeur de Recherche, <b>Président</b> — <span style="font-variant:small-caps;">Entropie</span>, Institut de Recherche pour le Développement, Nouvelle-Calédonie
  </li>
  <li style="line-height: 150%">
    Thomas <span style="font-variant:small-caps;">Guyet</span>, Chargé de Recherche (HDR), <b>Rapporteur</b> — AIstroSight, Centre INRIA, Lyon, France
  </li>
  <li style="line-height: 150%">
    Luiz-Angelo <span style="font-variant:small-caps;">Steffenel</span>, Professeur des Universités, <b>Rapporteur</b> — LICIIS, Université de Reims Champagne-Ardenne, France
  </li>
  <li style="line-height: 150%">
    Cyrille <span style="font-variant:small-caps;">Goarant</span>, Chercheur (HDR), <b>Examinateur</b> — Département de Santé Publique, Communauté du Pacifique, Nouvelle-Calédonie
  </li>
  <li style="line-height: 150%">
    Corina <span style="font-variant:small-caps;">Iovan</span>, Chargée de Recherche, <b>Examinateur</b> — <span style="font-variant:small-caps;">Entropie</span>, Institut de Recherche pour le Développement, Nouvelle-Calédonie
  </li>
  <li style="line-height: 150%">
    Nadia <span style="font-variant:small-caps;">Kabachi</span>, Professeure des Universités, <b>Examinateur</b> — ERIC, Université Claude Bernard Lyon 1, France
  </li>
</ul>

Le manuscrit de thèse est actuellement en cours de publication, mais la soutenance est disponible [ici](https://www.youtube.com/watch?v=7AvJPTxWxPU).

Cette thèse a exploré les méthodes d'apprentissage supervisé appliquées à la cartographie du risque de leptospirose en Nouvelle-Calédonie. Pour cela, une approche holistique est considérée, en collectant, pré-traitant et intégrant une large variété de données, qu'elles soient météorologiques, environnementales ou socio-démographiques. La cartographie du risque a été réalisée à l'aide de l'ensemble des cas de leptospirose entre 2011 et 2022, à une échelle spatiale plus fine que celle de la commune, le tout sur un pas de temps mensuel. Cette granularité spatio-temporelle s'est alors traduite en un véritable défi de données déséquilibrées. Couplées à maintes stratégies d'échantillonnage des données, deux approches ont été développées.

La première approche intègre un apprentissage ensembliste combiné à des stratégies de sous-échantillonnage et d'échantillonnage hybride pour l'apprentissage des modèles, ainsi qu'à des prédictions pondérées pour optimiser l'efficacité de cette approche. Face aux résultats concluants de cette approche ensembliste, une composante d'explicabilité est développée, permettant d'identifier les facteurs contribuant au risque de leptospirose. Cette première approche, bien que donnant des résultats satisfaisants, a nécessité l'utilisation de multiples modèles d'apprentissage supervisé.

En parallèle, cette thèse a exploré les méthodes de réseaux de neurones de graphes (GNN), plus précisément la problématique de la réduction optimale de graphes attribués au sein d'un modèle de GNN, en combinant les méthodes de pooling de la littérature. Cette méthode hybride, nommée <span style="font-variant: small-caps;">SpaPool</span>, s'est avérée équivalente aux méthodes existantes, mais montre une certaine supériorité lorsqu'il s'agit de graphes attribués de petite taille. La représentation en graphes attribués étant particulièrement efficace, la seconde approche de cartographie du risque de leptospirose a été développée à partir d'un modèle unique de GNN. Couplée à diverses stratégies d'échantillonnage, cette approche a donné des résultats prometteurs, avec des scores de sensibilité et de spécificité plus homogènes que l'approche ensembliste.

Les contributions présentées dans cette thèse, qu'elles soient méthodologiques ou applicatives, offrent de nouvelles opportunités pour d'autres phénomènes sanitaires et anthropiques.

Durant cette thèse, Rodrigue a également dispensé des enseignements aux étudiants de niveaux Licence et DEUST. Ses enseignements ont inclus notamment l'algorithmique et la programmation en Python, la théorie des graphes, ainsi que la gestion et manipulation de bases de données.

</span>

<br>

# Publications

<style>
td, thead, tbody, tr {
   background-color: none;
   vertical-align: top;
   text-align: justify;
   font-size: 1rem;
}

.bib{
  border:solid; 
  border-radius:5px;
  border-width:1px;
  padding-left:6px; 
  padding-right:6px; 
  padding-top:2px; 
  padding-bottom:2px;
  text-decoration: none;
}

.bib:hover{
  border-radius:5px;
  border-width:1px;
  border-color:var(--tw-prose-links);
  padding-left:6px; 
  padding-right:6px; 
  padding-top:2px; 
  padding-bottom:2px;
}
</style>

<table>
  <tr>
    <td style="text-align:center">[11]</td>
    <td style="text-align:justify">
      <b>Govan, R.</b>, Scherrer, R., Fournier-Viger, P., Selmaoui-Folcher, N. (2025). <b><span style="font-variant-caps: small-caps;">SpaPool</span>: Soft Partition Assignment Pooling for Graph Neural Networks</b>. In: Leung, C.K., Dignös, A., Kotsis, G., Tjoa, A.M., Khalil, I. (eds) <i>Big Data Analytics and Knowledge Discovery. DaWaK 2025</i>. Lecture Notes in Computer Science, vol 16048. Springer, Cham. <br><a href="https://dx.doi.org/10.1007/978-3-032-02215-8_27" class="bib" target="_blank">html</a> <a href="Govan2025d.bib" class="bib" target="_blank">bib</a>
    </td>
  </tr>
  
  <tr>
    <td style="text-align:center">[10]</td>
    <td style="text-align:justify">
      <b>Govan, R.</b>, Scherrer, R., Fournier-Viger, P., Selmaoui-Folcher, N. (2025). <b><i>Pooling</i> de <i>Graph Neural Networks</i> : une approche dense mais adaptative</b>. In: <i>CNIA 2025-Conférence Nationale en Intelligence Artificielle,</i> PFIA (No. 55-63). <br><a href="https://hal.science/hal-05197596v1" class="bib" target="_blank">html</a> <a href="Govan2025c.bib" class="bib" target="_blank">bib</a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center">[9]</td>
    <td style="text-align:justify">
      <b>Govan, R.</b>, Scherrer, R., Goarant, C., Cannet, A., Fournier-Viger, P., Selmaoui-Folcher, N. (2025, January). <b>Cartographie du risque épidémiologique : Le défi des données fortement déséquilibrées</b>. In: <i>Revue des Nouvelles Technologies de l'Information, 25èmes Journées Francophones Extraction et Gestion des Connaissances, EGC 2025</i>, vol. RNTI-E-41. (pp. 159-170). <br><a href="https://hal.science/hal-04945686" class="bib" target="_blank">html</a> <a href="Govan2025b.bib" class="bib" target="_blank">bib</a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center">[8]</td>
    <td style="text-align:justify">
      <b>Govan, R.</b>, Scherrer, R., Fougeron, B., Laporte-Magoni, C., Thibeaux, R., Genthon, P., Fournier-Viger, P., Goarant, C., Selmaoui-Folcher, N. (2025). <b>Spatio-temporal risk prediction of leptospirosis: A machine-learning-based approach</b>. In: <i>PLOS Neglected Tropical Diseases, 19</i>(1), e0012755. <br><a href="https://doi.org/10.1371/journal.pntd.0012755" class="bib" target="_blank">html</a> <a href="Govan2025a.bib" class="bib" target="_blank">bib</a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center">[7]</td>
    <td style="text-align:justify">
      Thibeaux, R., Genthon, P., <b>Govan, R.</b>, Selmaoui-Folcher, N., Tramier, C., Kainiu, M., Soupé-Gilbert, M.-E., Wijesuriya, K., Goarant, C. (2024). <b>Rainfall-driven resuspension of pathogenic Leptospira in a leptospirosis hotspot</b>. In: <i>Science of The Total Environment, 911</i>, 168700. <br><a href="https://doi.org/10.1016/j.scitotenv.2023.168700" class="bib" target="_blank">html</a> <a href="Thibeaux2024.bib" class="bib" target="_blank">bib</a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center">[6]</td>
    <td style="text-align:justify">
      <b>Govan, R.</b>, Selmaoui-Folcher, N., Giannakos, A., Fournier-Viger, P. (2023). <b>Co-location Pattern Mining Under the Spatial Structure Constraint</b>. In: Strauss, C., Amagasa, T., Kotsis, G., Tjoa, A.M., Khalil, I. (eds) <i>Database and Expert Systems Applications. DEXA 2023</i>. Lecture Notes in Computer Science, vol 14146. Springer, Cham. <br><a href="https://doi.org/10.1007/978-3-031-39847-6_13" class="bib" target="_blank">html</a> <a href="Govan2023b.bib" class="bib" target="_blank">bib</a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center">[5]</td>
    <td style="text-align:justify">
      <b>Govan, R.</b>, Selmaoui-Folcher, N., Giannakos, A., Fournier-Viger, P. (2023, July). <b>Extraction de co-localisations sous contrainte de la structure spatiale</b>. In: <i>CNIA 2023-Conférence Nationale en Intelligence Artificielle</i>, PFIA (No. 53-61). <br><a href="https://hal.science/hal-04164263/" class="bib" target="_blank">html</a> <a href="Govan2023a.bib" class="bib" target="_blank">bib</a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center">[4]</td>
    <td style="text-align:justify">
      Tokotoko, J., <b>Govan, R.</b>, Lemonnier, H., Selmaoui-Folcher, N. (2022). <b>Multiscale and Multivariate Time Series Clustering: A New Approach</b>. In: Ceci, M., Flesca, S., Masciari, E., Manco, G., Raś, Z.W. (eds) <i>Foundations of Intelligent Systems. ISMIS 2022</i>. Lecture Notes in Computer Science(), vol 13515. Springer, Cham. <br><a href="https://doi.org/10.1007/978-3-031-16564-1_27" class="bib" target="_blank">html</a> <a href="Tokotoko2022.bib" class="bib" target="_blank">bib</a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center">[3]</td>
    <td style="text-align:justify">
      Scherrer, R., <b>Govan, R.</b>, Quiniou, T., Jauffrais, T., Lemonnier, H., Bonnet, S., Selmaoui-Folcher, N. (2022). <b>Real-Time Automatic Plankton Detection, Tracking and Classification on Raw Hologram</b>. In: <i>International Meeting on Computational Intelligence Methods for Bioinformatics and Biostatistics</i> (pp. 25-39). Springer, Cham. <br><a href="https://doi.org/10.1007/978-3-031-20837-9_3" class="bib" target="_blank">html</a> <a href="Scherrer2022.bib" class="bib" target="_blank">bib</a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center">[2]</td>
    <td style="text-align:justify">
      Scherrer, R., <b>Govan, R.</b>, Quiniou, T., Jauffrais, T., Lemonnier, H., Bonnet, S., Selmaoui-Folcher, N. (2021, November). <b>Automatic Plankton Detection and Classification on Raw Hologram with a Single Deep Learning Architecture</b>. In: <i>CIBB 2021 Computational Intelligence Methods for Bioinformatics and Biostatistics</i>. <br><a href="https://hal.science/hal-03565469" class="bib" target="_blank">html</a> <a href="Scherrer2021.bib" class="bib" target="_blank">bib</a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center">[1]</td>
    <td style="text-align:justify">
      Tokotoko, J., Selmaoui-Folcher, N., <b>Govan, R.</b>, Lemonnier, H. (2021). <b>TSX-Means: An Optimal K Search Approach for Time Series Clustering</b>. In: Strauss, C., Kotsis, G., Tjoa, A.M., Khalil, I. (eds) <i>Database and Expert Systems Applications. DEXA 2021</i>. Lecture Notes in Computer Science(), vol 12924. Springer, Cham. <br><a href="https://doi.org/10.1007/978-3-030-86475-0_23" class="bib" target="_blank">html</a> <a href="Tokotoko2021.bib" class="bib" target="_blank">bib</a>
    </td>
  </tr>
</table>

<br>
