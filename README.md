# sc-pert - Machine learning for perturbational single-cell omics

*This repository provides a community-maintained summary of models and datasets. It was initially curated for [(Cell Systems, 2021)](https://doi.org/10.1016/j.cels.2021.05.016).*

We [curated a list of perturbation-related tools at scrna-tools](https://www.scrna-tools.org/tools?sort=name&cats=Perturbations). Please consider further updating and tagging tools [there](https://github.com/scRNA-tools/scRNA-tools).

This [spreadsheet of a subset of perturbation models](https://docs.google.com/spreadsheets/d/1nqNg0DW1-Om7WtvRS20q-6b28usVRv5czOcxgj83Sgg/) includes more details, and is the basis of the table in the article.

Below, we curated a table of perturbation datasets based on [Svensson *et al.* (2020)](https://doi.org/10.1093/database/baaa073).
| Shorthand                                                          | Title&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;                                                                                                                                                   |     Date | Reported cells total   | Organism     | Tissue               | Technique            | Data location   | Panel size   | Measurement   | Cell source                            |   Disease | Contrasts             |   Developmental stage |   Number of reported cell types or clusters | Cell clustering   | Pseudotime   | RNA Velocity   | PCA   | tSNE   |   H5AD location | Isolation            | BC --> Cell ID _OR_ BC --> Cluster ID                              |   Number individuals |
|--------------------------------------------------------------------|---------------------------------------------------------------------------------------------------------------------------------------------------------|----------|------------------------|--------------|----------------------|----------------------|-----------------|--------------|---------------|----------------------------------------|-----------|-----------------------|-----------------------|---------------------------------------------|-------------------|--------------|----------------|-------|--------|-----------------|----------------------|--------------------------------------------------------------------|----------------------|
| [Jaitin *et al.* Science](doi.org/10.1126/science.1247651)         | Massively Parallel Single-Cell RNA-Seq for Marker-Free Decomposition of Tissues into Cell Types                                                         | 20140214 | 4,468                  | Mouse        | Spleen               | MARS-seq             | GSE54006        | nan          | RNA-seq       | CD11c+ enriched splenocytes            |       nan | nan                   |                   nan |                                           9 | Yes               | No           | nan            | No    | No     |             nan | Sorting (FACS)       | nan                                                                |                  nan |
| [Adamson *et al.* Cell](doi.org/10.1016/j.cell.2016.11.048)        | A Multiplexed Single-Cell CRISPR Screening Platform Enables Systematic Dissection of the Unfolded Protein Response                                      | 20161215 | 86,000                 | Human        | nan                  | Perturb-seq          | GSE90546        | nan          | RNA-seq       | nan                                    |       nan | nan                   |                   nan |                                         nan | nan               | nan          | nan            | nan   | Yes    |             nan | nan                  | nan                                                                |                  nan |
| [Dixit *et al.* Cell](doi.org/10.1016/j.cell.2016.11.038)          | Perturb-Seq: Dissecting Molecular Circuits with Scalable Single-Cell RNA Profiling of Pooled Genetic Screens                                            | 20161215 | 200,000                | Human, Mouse | Culture              | Perturb-seq          | GSE90063        | nan          | RNA-seq       | BMDCs, K562                            |       nan | nan                   |                   nan |                                         nan | nan               | nan          | nan            | nan   | No     |             nan | Nanodroplet dilution | nan                                                                |                  nan |
| [Datlinger *et al.* NMeth](doi.org/10.1038/nmeth.4177)             | Pooled CRISPR screening with single-cell transcriptome readout                                                                                          | 20170118 | 5,905                  | Human, Mouse | Culture              | CROP-seq             | GSE92872        | nan          | RNA-seq       | HEK293T, 3T3, Jurkat                   |       nan | nan                   |                   nan |                                         nan | nan               | nan          | nan            | nan   | No     |             nan | nan                  | nan                                                                |                  nan |
| [Hill *et al.* NMethods](doi.org/10.1038/nmeth.4604)               | On the design of CRISPR-based single-cell molecular screens                                                                                             | 20180219 | nan                    | Human        | Culture              | CROP-seq             | GSE108699       | nan          | RNA-seq       | MCF10a cells                           |       nan | nan                   |                   nan |                                         nan | nan               | nan          | nan            | nan   | nan    |             nan | nan                  | https://github.com/shendurelab/single-cell-ko-screens#result-files |                  nan |
| [Gasperini *et al.* Cell](doi.org/10.1016/j.cell.2018.11.029)      | A Genome-wide Framework for Mapping Gene Regulation via Cellular Genetic Screens                                                                        | 20190103 | 207,324                | Human        | Culture              | CROP-seq             | GSE120861       | nan          | RNA-seq       | K562 Cells                             |       nan | CRISPR Screen         |                   nan |                                         nan | nan               | nan          | nan            | nan   | nan    |             nan | nan                  | nan                                                                |                  nan |
| [Shin *et al.* SAdvances](doi.org/10.1126/sciadv.aav2249)          | Multiplexed single-cell RNA-seq via transient barcoding for simultaneous expression profiling of various drug perturbations                             | 20190516 | 3,091                  | Mouse, Human | Culture              | Drop-seq             | PRJNA493658     | nan          | RNA-seq       | HEK293T, NIIH3T3, A375, SW480, K562    |       nan | 45 perturbations      |                   nan |                                         nan | nan               | nan          | nan            | nan   | nan    |             nan | nan                  | nan                                                                |                  nan |
| [Jin *et al.* bioRxiv](doi.org/10.1101/791525)                     | In vivo Perturb-Seq reveals neuronal and glial abnormalities associated with Autism risk genes                                                          | 20191008 | 46,770                 | Mouse        | Brain                | Perturb-seq          | nan             | nan          | RNA-seq       | nan                                    |       nan | nan                   |                   nan |                                         nan | nan               | nan          | nan            | nan   | nan    |             nan | nan                  | nan                                                                |                  nan |
| [Srivatsan *et al.* Science](doi.org/10.1126/science.aax6234)      | Massively multiplex chemical transcriptomics at single-cell resolution                                                                                  | 20191206 | 650,000                | Human        | Culture              | sci-Plex             | GSE139944       | nan          | RNA-seq       | Cancer cell lines A549, K562, and MCF7 |       nan | 5,000 drug conditions |                   nan |                                           3 | Yes               | Yes          | No             | Yes   | No     |             nan | nan                  | nan                                                                |                  nan |
| [McFarland *et al.* bioRxiv](doi.org/10.1101/868752)               | Multiplexed single-cell profiling of post-perturbation transcriptional responses to define cancer vulnerabilities and therapeutic mechanism of action   | 20191209 | nan                    | Human        | Culture              | MIX-seq              | nan             | nan          | RNA-seq       | nan                                    |       nan | nan                   |                   nan |                                         nan | nan               | nan          | nan            | nan   | nan    |             nan | nan                  | nan                                                                |                  nan |
| [Zhao *et al.* bioRxiv](doi.org/10.1101/2020.04.22.056341)         | Deconvolution of Cell Type-Specific Drug Responses in Human Tumor Tissue with Single-Cell RNA-seq                                                       | 20200424 | 48,404                 | Human        | Brain, Tumor         | SCRB-seq (microwell) | GSE148842       | nan          | RNA-seq       | nan                                    |       nan | nan                   |                   nan |                                         nan | nan               | nan          | nan            | nan   | nan    |             nan | nan                  | nan                                                                |                    6 |
| [Schraivogel *et al.* NMethods](doi.org/10.1038/s41592-020-0837-5) | Targeted Perturb-seq enables genome-scale genetic screens in single cells                                                                               | 20200601 | 231,667                | Human, Mouse | Bone marrow, Culture | TAP-seq              | GSE135497       | 1,000        | RNA-seq       | nan                                    |       nan | nan                   |                   nan |                                         nan | nan               | nan          | nan            | nan   | Yes    |             nan | nan                  | nan                                                                |                  nan |
| [Ursu *et al.* bioRxiv](doi.org/10.1101/2020.11.16.383307)         | Massively parallel phenotyping of variant impact in cancer with Perturb-seq reveals a shift in the spectrum of cell states induced by somatic mutations | 20201118 | 162,314                | Human        | Lung                 | Perturb-seq          | nan             | nan          | RNA-seq       | nan                                    |       nan | nan                   |                   nan |                                         nan | nan               | nan          | nan            | nan   | nan    |             nan | nan                  | nan                                                                |                  nan |
| [Frangieh *et al.* NGenetics](doi.org/10.1038/s41588-021-00779-1)  | Multimodal pooled Perturb-CITE-seq screens in patient models define mechanisms of cancer immune evasion                                                 | 20210301 | 218,331                | Human        | Culture              | Perturb-CITE-seq     | SCP1064         | nan          | RNA-seq       | nan                                    |       nan | nan                   |                   nan |                                         nan | nan               | nan          | nan            | nan   | nan    |             nan | nan                  | nan                                                                |                  nan |