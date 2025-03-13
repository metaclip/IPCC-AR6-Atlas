# METACLIP provenance for the IPCC-AR6 WGI Atlas
Controlled METACLIP vocabulary for the IPCC-AR6 WGI Atlas (http://interactive-atlas.ipcc.ch) based on the core [METACLIP semantic ontologies](https://github.com/metaclip/ontologies) for data sources (mainly CMIP5/6 and CORDEX subsets), postprocessing (temporal aggregation, regrdding, etc.), callibration methods (bias ajustment in this case) and graphical products (geographical extent, color bars, displayed entities, etc.). 

This vocabulary is used to produce the provenance information for the different climatic products produced by the Atlas (see [AR6 WGI Atlas Chapter, Sec. 2.3](https://www.ipcc.ch/report/ar6/wg1/chapter/atlas/#Atlas.2.3) for full details). This information can be visualized as a semantic graph (see figure below) and downloaed (json format) from the Atlas, and describes the end-to-end provenance of the different products. The figure below shows an example for the _number of days with bias adjusted maximum temperature over 35º_ (right panel), displaying the future change for a 2º Global Warming Level from the CMIP6 ensemble of climate projections. The left panel displays the semantic graph linking the different provenance elements, including the different datasets involved (historical and future CMIP6 projections and observations), together with the processing chain and index calculation, down to the final graphical product.

<img width="1145" alt="Captura de pantalla 2024-07-26 a las 11 25 52" src="https://github.com/user-attachments/assets/81e68d35-8b5c-49cc-84e1-933ffab671dd">

This information is accesible in the [Interactive Atlas](https://interactive-atlas.ipcc.ch/permalink/2ftNwPFM) clicking on the "metadata" button on the right toolbar to display the metadata information. Full deatils on the different provenance elements can be displayed clicking on the nodes of the graph, from the data sources in the top to the graphical products in the bottom. 

You can also have a look to our [2024 AGU Interactive Poster](https://agu24.ipostersessions.com/Default.aspx?s=50-0B-A2-D6-50-24-05-87-67-9B-4A-09-A3-FE-B3-3D)

