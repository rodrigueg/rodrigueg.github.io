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

Rodrigue is a Doctor in Computer Science (Data Science). His thesis is entitled "_Deep Learning on Attributed Graphs for Mapping Leptospirosis Risk_". He defended his PhD in August 2025 at the University of New Caledonia.

The thesis committee was composed of:
- Dr. Christophe Menkès, Senior Research Scientist, Chair -- ENTROPIE, French National Research Institute for Sustainable Development, New Caledonia
- Dr. Thomas Guyet, Full Researcher, Reviewer -- AIstroSight, INRIA, Lyon, France
- Pr. Luiz-Angelo Steffenel, Full Professor, Reviewer -- LICIIS, Université de Reims Champagne-Ardenne, France
- Dr. Cyrille Goarant, Habilitated Research Scientist, Examiner -- Public Health Department, South Pacific Community, New Caledonia
- Dr. Corina Iovan, Research Scientist, Examiner -- ENTROPIE, French National Research Institute for Sustainable Development, New Caledonia
- Pr. Nadia Kabachi, Full Professor, Examiner -- ERIC, University Claude Bernard Lyon 1, France

This thesis explored supervised learning methods applied to the risk mapping of leptospirosis in New Caledonia. To do so, a holistic approach is considered, by collecting, pre-processing and integrating a broad spectrum of variables, whether they are meteorological, environmental or socio-demographical. The risk mapping has been conducted according the leptospirosis surveillance data from 2011 to 2022, on a spatial scale finer than the municipal level, and on a monthly time step. This spatio-temporal granularity therefore posed a real challenge of imbalanced data. Combined with several sampling strategies, two approaches were developed.

The first approach involved an ensemble learning, coupled with under-sampling and hybrid sampling strategies for model training, as well as weighted prediction to optimize the approach's effectiveness. Given conclusive results, an explainability component was developed, enabling the identification of most contributing factors to the leptospirosis risk. Despite satisfying results, this first approach required a large number of supervised learning models.

In parallel, this thesis investigates graph neural network (GNN) methods, focusing specifically on the optimal reduction of attributed graphs within a GNN model by integrating existing pooling techniques from the literature. The resulting hybrid method, named <span style="font-variant: small-caps;">SpaPool</span>, performed comparably to established approaches and demonstrated superior results on datasets consisting of small attributed graphs. Given the effectiveness of graph-based representations, the second approach to map leptospirosis risk using a single GNN model was developed. Combined with various sampling strategies, this method produced promising outcomes, yielding more balanced sensitivity and specificity scores compared to the ensemble approach.

The contributions presented in the thesis, both methodological and applied, offer new opportunities for studying other health-related and anthropogenic phenomena.

This thesis was under supervision of <a href="https://isea.unc.nc/membres/selmaoui-folcher/" target="_blank">Prof. Nazha Selmaoui-Folcher</a>, Full Professor in Computer Science at the University of New Caledonia and <a href="https://www.philippe-fournier-viger.com" target="_blank">Prof. Philippe Fournier-Viger</a>, Distinguished Professor in Computer Science at the Shenzhen University (China).

During this thesis, Rodrigue has given classes to Bachelor students. His main courses involved Advanced programming in Python, Graph Theory, and Database management.

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

|   |  |
|:-:|--|
| [11] | <b>Govan, R.</b>, Scherrer, R., Fournier-Viger, P., Selmaoui-Folcher, N. (2025). <b><span style="font-variant-caps: small-caps;">SpaPool</span>: Soft Partition Assignment Pooling for Graph Neural Networks</b>. In : Leung, C.K., Dignös, A., Kotsis, G., Tjoa, A.M., Khalil, I. (eds) <i>Big Data Analytics and Knowledge Discovery. DaWaK 2025</i>. Lecture Notes in Computer Science, vol 16048. Springer, Cham. <br><a href="https://dx.doi.org/10.1007/978-3-032-02215-8_27" class="bib" target="_blank">html</a> <a href="Govan2025d.bib" class="bib" target="_blank">bib</a> |
| [10] | <b>Govan, R.</b>, Scherrer, R., Fournier-Viger, P., Selmaoui-Folcher, N. (2025). <b><i>Pooling</i> de <i>Graph Neural Networks</i> : une approche dense mais adaptative</b>. In <i>CNIA 2025-Conférence Nationale en Intelligence Artificielle,</i> PFIA (No. 55-63). <br><a href="https://hal.science/hal-05197596v1" class="bib" target="_blank">html</a> <a href="Govan2025c.bib" class="bib" target="_blank">bib</a> |
| [9] | <b>Govan, R.</b>, Scherrer, R., Goarant, C., Cannet, A., Fournier-Viger, P., Selmaoui-Folcher, N. (2025, January). <b>Cartographie du risque épidémiologique : Le défi des données fortement déséquilibrées</b>. In <i>Revue des Nouvelles Technologies de l'Information, 25èmes Journées Francophones Extraction et Gestion des Connaissances, EGC 2025</i>, vol. RNTI-E-41. (pp. 159-170). <br><a href="https://hal.science/hal-04945686" class="bib" target="_blank">html</a> <a href="Govan2025b.bib" class="bib" target="_blank">bib</a> |
| [8] | <b>Govan, R.</b>, Scherrer, R., Fougeron, B., Laporte-Magoni, C., Thibeaux, R., Genthon, P., Fournier-Viger, P., Goarant, C., Selmaoui-Folcher, N. (2025). <b>Spatio-temporal risk prediction of leptospirosis: A machine-learning-based approach</b>. <i>PLOS Neglected Tropical Diseases, 19</i>(1), e0012755. <br><a href="https://doi.org/10.1371/journal.pntd.0012755" class="bib" target="_blank">html</a> <a href="Govan2025a.bib" class="bib" target="_blank">bib</a> |
| [7] | Thibeaux, R., Genthon, P., <b>Govan, R.</b>, Selmaoui-Folcher, N., Tramier, C., Kainiu, M., Soupé-Gilbert, M.-E., Wijesuriya, K., Goarant, C. (2024). <b>Rainfall-driven resuspension of pathogenic Leptospira in a leptospirosis hotspot</b>. <i>Science of The Total Environment, 911</i>, 168700. <br><a href="https://doi.org/10.1016/j.scitotenv.2023.168700" class="bib" target="_blank">html</a> <a href="Thibeaux2024.bib" class="bib" target="_blank">bib</a> |
| [6] | <b>Govan, R.</b>, Selmaoui-Folcher, N., Giannakos, A., Fournier-Viger, P. (2023). <b>Co-location Pattern Mining Under the Spatial Structure Constraint</b>. In: Strauss, C., Amagasa, T., Kotsis, G., Tjoa, A.M., Khalil, I. (eds) <i>Database and Expert Systems Applications. DEXA 2023</i>. Lecture Notes in Computer Science, vol 14146. Springer, Cham. <br><a href="https://doi.org/10.1007/978-3-031-39847-6_13" class="bib" target="_blank">html</a> <a href="Govan2023b.bib" class="bib" target="_blank">bib</a> |
| [5] | <b>Govan, R.</b>, Selmaoui-Folcher, N., Giannakos, A., Fournier-Viger, P. (2023, July). <b>Extraction de co-localisations sous contrainte de la structure spatiale</b>. In <i>CNIA 2023-Conférence Nationale en Intelligence Artificielle</i>, PFIA (No. 53-61). <br><a href="https://hal.science/hal-04164263/" class="bib" target="_blank">html</a> <a href="Govan2023a.bib" class="bib" target="_blank">bib</a> |
| [4] | Tokotoko, J., <b>Govan, R.</b>, Lemonnier, H., Selmaoui-Folcher, N. (2022). <b>Multiscale and Multivariate Time Series Clustering: A New Approach</b>. In: Ceci, M., Flesca, S., Masciari, E., Manco, G., Raś, Z.W. (eds) <i>Foundations of Intelligent Systems. ISMIS 2022</i>. Lecture Notes in Computer Science(), vol 13515. Springer, Cham. <br><a href="https://doi.org/10.1007/978-3-031-16564-1_27" class="bib" target="_blank">html</a> <a href="Tokotoko2022.bib" class="bib" target="_blank">bib</a> |
| [3] | Scherrer, R., <b>Govan, R.</b>, Quiniou, T., Jauffrais, T., Lemonnier, H., Bonnet, S., & Selmaoui-Folcher, N. (2022). <b>Real-Time Automatic Plankton Detection, Tracking and Classification on Raw Hologram</b>. In <i>International Meeting on Computational Intelligence Methods for Bioinformatics and Biostatistics</i> (pp. 25-39). Springer, Cham. <br><a href="https://doi.org/10.1007/978-3-031-20837-9_3" class="bib" target="_blank">html</a> <a href="Scherrer2022.bib" class="bib" target="_blank">bib</a> |
| [2] | Scherrer, R., <b>Govan, R.</b>, Quiniou, T., Jauffrais, T., Lemonnier, H., Bonnet, S., & Selmaoui-Folcher, N. (2021, November). <b>Automatic Plankton Detection and Classification on Raw Hologram with a Single Deep Learning Architecture</b>. In <i>CIBB 2021 Computational Intelligence Methods for Bioinformatics and Biostatistics</i>. <br><a href="https://hal.science/hal-03565469" class="bib" target="_blank">html</a> <a href="Scherrer2021.bib" class="bib" target="_blank">bib</a> |
| [1] | Tokotoko, J., Selmaoui-Folcher, N., <b>Govan, R.</b>, Lemonnier, H. (2021). <b>TSX-Means: An Optimal K Search Approach for Time Series Clustering</b>. In: Strauss, C., Kotsis, G., Tjoa, A.M., Khalil, I. (eds) <i>Database and Expert Systems Applications. DEXA 2021</i>. Lecture Notes in Computer Science(), vol 12924. Springer, Cham. <br><a href="https://doi.org/10.1007/978-3-030-86475-0_23" class="bib" target="_blank">html</a> <a href="Tokotoko2021.bib" class="bib" target="_blank">bib</a> |

<br>
