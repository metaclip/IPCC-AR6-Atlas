# IPCC-AR6-Atlas
Controlled METACLIP vocabulary for the IPCC-AR6 WGI Atlas (http://interactive-atlas.ipcc.ch) based on the core [METACLIP semantic ontologies](https://github.com/metaclip/ontologies) for data sources (mainly CMIP5/6 and CORDEX subsets), postprocessing (temporal aggregation, regrdding, etc.), callibration methods (bias ajustment in this case) and graphical products (geographical extent, color bars, displayed entities, etc.). 

This vocabulary is used to produce the linked provenance information for the climatic products produced by the Atlas (see [AR6 WGI Atlas Chapter, Sec. 2.3](https://www.ipcc.ch/report/ar6/wg1/chapter/atlas/#Atlas.2.3) for full details). This information can be visualized as a semmantic graph (see figure below) and downloaed (json format) from the Atlas describing the end-to-end provenance of the different products. The figure below shows an example for the number of days with maximum temperature over 35º, displaying the future change for a 2º Global Warming Level (right panel) from the CMIP6 ensemble of cliamte projections. The lef panel displays the semmantic graph linking the different provenance elements, including the different datasets involved (historical and future CMIP6 projections and observations), together with the processing chain, down to the final product -the climate change signal-).

<img width="1145" alt="Captura de pantalla 2024-07-26 a las 11 25 52" src="https://github.com/user-attachments/assets/81e68d35-8b5c-49cc-84e1-933ffab671dd">

This information is accesible in the Interactice Atlas in the following [link](https://interactive-atlas.ipcc.ch/permalink/2ftNwPFM) (click on the "metadata" button on the right to display the metadata information). The different provenance elements can be displayed clicking on the different elements of the graph (ensemble members, 20-year periods for the warming levels of the different models, particular gridding, index calculation, etc.).

