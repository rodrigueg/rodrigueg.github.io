---
title: "Research"
#description: "Here are listed my professional as well as my academic backgrounds."
cascade:
  showReadingTime: false
  showDate: false
layout: "simple"
---

<hr>

<span style='text-align: justify;'>

Rodrigue <span style="font-variant:small-caps;">Govan</span> holds a Ph.D. in Computer Science (Data Science). His dissertation is entitled "_Deep Learning on Attributed Graphs for Mapping Leptospirosis Risk_". He defended his thesis on August 21, 2025, at the University of New Caledonia.

This thesis was conducted under the supervision of <a href="https://isea.unc.nc/membres/selmaoui-folcher/" target="_blank">Nazha <span style="font-variant:small-caps;">Selmaoui-Folcher</span></a>, Full Professor of Computer Science at the University of New Caledonia, and <a href="https://www.philippe-fournier-viger.com" target="_blank">Philippe <span style="font-variant:small-caps;">Fournier-Viger</span></a>, Distinguished Professor of Computer Science at Shenzhen University (China).

The members of the thesis committee were as follows:
<ul style="margin-top:-1em">
  <li style="line-height: 150%">
    Christophe <span style="font-variant:small-caps;">Menkès</span>, Senior Research Scientist, <b>Chair</b> -- <span style="font-variant:small-caps;">Entropie</span>, French National Research Institute for Sustainable Development, New Caledonia
  </li>
  <li style="line-height: 150%">
    Thomas <span style="font-variant:small-caps;">Guyet</span>, Full Researcher, <b>Reviewer</b> -- AIstroSight, INRIA, Lyon, France
  </li>
  <li style="line-height: 150%">
    Luiz-Angelo <span style="font-variant:small-caps;">Steffenel</span>, Full Professor, <b>Reviewer</b> -- LICIIS, Université de Reims Champagne-Ardenne, France
  </li>
  <li style="line-height: 150%">
    Cyrille <span style="font-variant:small-caps;">Goarant</span>, Habilitated Research Scientist, <b>Examiner</b> -- Public Health Department, South Pacific Community (SPC), New Caledonia
  </li>
  <li style="line-height: 150%">
    Corina <span style="font-variant:small-caps;">Iovan</span>, Research Scientist, <b>Examiner</b> -- <span style="font-variant:small-caps;">Entropie</span>, French National Research Institute for Sustainable Development, New Caledonia
  </li>
  <li style="line-height: 150%">
    Nadia <span style="font-variant:small-caps;">Kabachi</span>, Full Professor, <b>Examiner</b> -- ERIC, Claude Bernard University Lyon 1, France
  </li>
</ul>

The Ph.D. manuscript is currently being prepared for publication, but the defense presentation is available [here](https://www.youtube.com/watch?v=7AvJPTxWxPU).

This thesis explored supervised learning methods applied to leptospirosis risk mapping in New Caledonia. A holistic approach was adopted, involving the collection, preprocessing, and integration of a wide range of data, including meteorological, environmental, and socio-demographic variables. Risk mapping was performed using all leptospirosis cases recorded between 2011 and 2022, at a spatial scale finer than the municipality level, and on a monthly temporal resolution. This spatio-temporal granularity introduced a significant challenge of imbalanced data. Combined with several data sampling strategies, two main approaches were developed.

The first approach integrates ensemble learning with under-sampling and hybrid sampling strategies for model training, along with weighted prediction mechanisms to optimize its performance. Following the conclusive results obtained with this ensemble-based method, an explainability component was developed to identify the main factors contributing to leptospirosis risk. Although this first approach produced satisfactory results, it required the use of multiple supervised learning models.

In parallel, the thesis investigated graph neural network (GNN) methods, specifically the problem of optimal reduction of attributed graphs within a GNN model by combining existing pooling techniques. This hybrid method, named <span style="font-variant: small-caps;">SpaPool</span>, proved comparable to existing methods, while demonstrating a certain advantage when dealing with small attributed graphs. Given the effectiveness of attributed graph representations, the second approach for leptospirosis risk mapping was based on a single GNN model. Combined with various sampling strategies, this approach yielded promising results, achieving more balanced sensitivity and specificity scores than the ensemble-based approach.

The contributions presented in this thesis, both methodological and applicative, open new opportunities for studying other health-related and anthropogenic phenomena.

During his Ph.D., Rodrigue also taught undergraduate students (Bachelor’s and DEUST levels). His teaching activities included algorithm design and Python programming, graph theory, as well as database management and manipulation.

</span>

<br>

# Publications

<style>
td, thead, tbody, tr {
   background-color: none;
   vertical-align: top;
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
      <b>Govan, R.</b>, Scherrer, R., Fournier-Viger, P., Selmaoui-Folcher, N. (2025). <b><span style="font-variant-caps: small-caps;">SpaPool</span>: Soft Partition Assignment Pooling for Graph Neural Networks</b>. In : Leung, C.K., Dignös, A., Kotsis, G., Tjoa, A.M., Khalil, I. (eds) <i>Big Data Analytics and Knowledge Discovery. DaWaK 2025</i>. Lecture Notes in Computer Science, vol 16048. Springer, Cham. <br><a href="https://dx.doi.org/10.1007/978-3-032-02215-8_27" class="bib" target="_blank">html</a> <a href="Govan2025d.bib" class="bib" target="_blank">bib</a>
    </td>
  </tr>
  
  <tr>
    <td style="text-align:center">[10]</td>
    <td style="text-align:justify">
      <b>Govan, R.</b>, Scherrer, R., Fournier-Viger, P., Selmaoui-Folcher, N. (2025). <b><i>Pooling</i> de <i>Graph Neural Networks</i> : une approche dense mais adaptative</b>. In <i>CNIA 2025-Conférence Nationale en Intelligence Artificielle,</i> PFIA (No. 55-63). <br><a href="https://hal.science/hal-05197596v1" class="bib" target="_blank">html</a> <a href="Govan2025c.bib" class="bib" target="_blank">bib</a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center">[9]</td>
    <td style="text-align:justify">
      <b>Govan, R.</b>, Scherrer, R., Goarant, C., Cannet, A., Fournier-Viger, P., Selmaoui-Folcher, N. (2025, January). <b>Cartographie du risque épidémiologique : Le défi des données fortement déséquilibrées</b>. In <i>Revue des Nouvelles Technologies de l'Information, 25èmes Journées Francophones Extraction et Gestion des Connaissances, EGC 2025</i>, vol. RNTI-E-41. (pp. 159-170). <br><a href="https://hal.science/hal-04945686" class="bib" target="_blank">html</a> <a href="Govan2025b.bib" class="bib" target="_blank">bib</a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center">[8]</td>
    <td style="text-align:justify">
      <b>Govan, R.</b>, Scherrer, R., Fougeron, B., Laporte-Magoni, C., Thibeaux, R., Genthon, P., Fournier-Viger, P., Goarant, C., Selmaoui-Folcher, N. (2025). <b>Spatio-temporal risk prediction of leptospirosis: A machine-learning-based approach</b>. <i>PLOS Neglected Tropical Diseases, 19</i>(1), e0012755. <br><a href="https://doi.org/10.1371/journal.pntd.0012755" class="bib" target="_blank">html</a> <a href="Govan2025a.bib" class="bib" target="_blank">bib</a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center">[7]</td>
    <td style="text-align:justify">
      Thibeaux, R., Genthon, P., <b>Govan, R.</b>, Selmaoui-Folcher, N., Tramier, C., Kainiu, M., Soupé-Gilbert, M.-E., Wijesuriya, K., Goarant, C. (2024). <b>Rainfall-driven resuspension of pathogenic Leptospira in a leptospirosis hotspot</b>. <i>Science of The Total Environment, 911</i>, 168700. <br><a href="https://doi.org/10.1016/j.scitotenv.2023.168700" class="bib" target="_blank">html</a> <a href="Thibeaux2024.bib" class="bib" target="_blank">bib</a>
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
      <b>Govan, R.</b>, Selmaoui-Folcher, N., Giannakos, A., Fournier-Viger, P. (2023, July). <b>Extraction de co-localisations sous contrainte de la structure spatiale</b>. In <i>CNIA 2023-Conférence Nationale en Intelligence Artificielle</i>, PFIA (No. 53-61). <br><a href="https://hal.science/hal-04164263/" class="bib" target="_blank">html</a> <a href="Govan2023a.bib" class="bib" target="_blank">bib</a>
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
      Scherrer, R., <b>Govan, R.</b>, Quiniou, T., Jauffrais, T., Lemonnier, H., Bonnet, S., Selmaoui-Folcher, N. (2022). <b>Real-Time Automatic Plankton Detection, Tracking and Classification on Raw Hologram</b>. In <i>International Meeting on Computational Intelligence Methods for Bioinformatics and Biostatistics</i> (pp. 25-39). Springer, Cham. <br><a href="https://doi.org/10.1007/978-3-031-20837-9_3" class="bib" target="_blank">html</a> <a href="Scherrer2022.bib" class="bib" target="_blank">bib</a>
    </td>
  </tr>
  <tr>
    <td style="text-align:center">[2]</td>
    <td style="text-align:justify">
      Scherrer, R., <b>Govan, R.</b>, Quiniou, T., Jauffrais, T., Lemonnier, H., Bonnet, S., Selmaoui-Folcher, N. (2021, November). <b>Automatic Plankton Detection and Classification on Raw Hologram with a Single Deep Learning Architecture</b>. In <i>CIBB 2021 Computational Intelligence Methods for Bioinformatics and Biostatistics</i>. <br><a href="https://hal.science/hal-03565469" class="bib" target="_blank">html</a> <a href="Scherrer2021.bib" class="bib" target="_blank">bib</a>
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
