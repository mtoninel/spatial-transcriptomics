# Resources for Spatial Transcriptomics data analysis

## _Data Processing_
- 10X provides a dedicated [pipeline](https://support.10xgenomics.com/spatial-gene-expression/software/pipelines/latest/what-is-space-ranger) for the analysis of Visium data, similar to the already existing cellranger for scRNA-seq

## _Integrated and Initial Data Analysis_
- Squidpy: an analytical framework based on the Scanpy platform. Palla, G., Spitzer, H., Klein, M. et al. *Squidpy: a scalable framework for spatial omics analysis.* _Nat Methods_ 19, 171–178 (2022). https://doi.org/10.1038/s41592-021-01358-2
- *SpaceMake, an integrated snakemake pipeline for the analysis of spatial data.* Tamas Ryszard Sztanka-Toth, Marvin Jens, Nikos Karaiskos, Nikolaus Rajewsky _bioRxiv_ 2021.11.07.467598  https://doi.org/10.1101/2021.11.07.467598
- Nextflow-based spatial transcriptomics [pipeline](https://github.com/nf-core/spatialtranscriptomics) from nf-core with the main downstream analytical approaches for Visium data.

## _Segmentation and Territories_
- Vesalius, a machine-learning approach exploiting image-analysis techniques identifies tissue anatomies based on transcriptional data.  Martin P.C.N. _et al_., 
_bioRxiv_ 2021.08.13.456235; doi: https://doi.org/10.1101/2021.08.13.456235
- SPACE: deep learning-based image segmentation approach for spatial transcriptomics.

## _Data Integration_
- [CellTrek](https://github.com/navinlabcode/CellTrek), mapping gene expression onto spatial coordinates. Wei, R., He, S., Bai, S. et al. *Spatial charting of single-cell transcriptomes in tissues.* _Nat Biotechnol_ (2022). https://doi.org/10.1038/s41587-022-01233-1 
- [Tangram](https://github.com/broadinstitute/Tangram) Biancalani, T., Scalia, G., Buffoni, L. et al. *Deep learning and alignment of spatially resolved single-cell transcriptomes with Tangram.* _Nat Methods_ 18, 1352–1362 (2021). https://doi.org/10.1038/s41592-021-01264-7
- [MultiVI](https://github.com/scverse/scvi-tools) by Gayoso, A., Lopez, R., Xing, G. et al. *A Python library for probabilistic analysis of single-cell omics data.* _Nat Biotechnol_ 40, 163–166 (2022). https://doi.org/10.1038/s41587-021-01206-w
- [DestVI](https://docs.scvi-tools.org/en/stable/user_guide/models/destvi.html) for deconvolution (uses deep-learning based Variational Inference, requiring a GPU for fast computation). Lopez, R., Li, B., Keren-Shaul, H. et al. *DestVI identifies continuums of cell types in spatial transcriptomics data.* _Nat Biotechnol_ (2022). https://doi.org/10.1038/s41587-022-01272-8
- [cell2location](https://github.com/BayraktarLab/cell2location) by Kleshchevnikov, V., Shmatko, A., Dann, E. et al., *Cell2location maps fine-grained cell types in spatial transcriptomics.* _Nat Biotechnol_ (2022) https://doi.org/10.1038/s41587-021-01139-4 
- [TACCO](https://github.com/simonwm/tacco) by Mages, S. et al., *TACCO unifies annotation transfer and decomposition of cell identities for single-cell and spatial omics* _Nat Biotechnol_ (2023). https://doi.org/10.1038/s41587-023-01657-3 

## _Deconvolution and Reconstruction_
- [BayesSpace](https://github.com/edward130603/BayesSpace), a Bayesian model for clustering and enhancing the resolution of spatial gene expression experiments. Zhao, E., Stone, M.R., Ren, X. et al. *Spatial transcriptomics at subspot resolution with BayesSpace.* _Nat Biotechnol_ 39, 1375–1384 (2021). https://doi.org/10.1038/s41587-021-00935-2
- BayesPrism: a fully Bayesian approach to deconvolve the tumor microenvironment, also applicable to spatial transcriptomics data. Chu, T., Wang, Z., Pe’er, D. et al. *Cell type and gene expression deconvolution with BayesPrism enables Bayesian integrative analysis across bulk and single-cell RNA sequencing in oncology.* _Nat Cancer_ (2022). https://doi.org/10.1038/s43018-022-00356-3
- *NovoSpaRc*: a framework for spatial tissue reconstruction starting from scRNA-seq data. [introductory paper](https://www.nature.com/articles/s41586-019-1773-3) and [methodological paper](https://www.nature.com/articles/s41596-021-00573-7)
- [RCTD](https://github.com/dmcable/spacexr), an R package to inspect celltype admixtures in spatial transcriptomics data. *Robust decomposition of cell type mixtures in spatial transcriptomics*, _Nat Biotechnol_. https://doi.org/10.1038/s41587-021-00830-w 

## _Further downstream analysis_
- [ncem](https://github.com/theislab/ncem) by David S. Fischer, Anna C. Schaar, Fabian J. Theis, *Learning cell communication from spatial graphs of cells*, bioRxiv (2021), https://doi.org/10.1101/2021.07.11.451750
- [C-SIDE](https://github.com/dmcable/spacexr) by Dylan M. Cable, Evan Murray, Fei Chen _et al._, *Cell type-specific inference of differential expression in spatial transcriptomics*, _Nature Methods_ (2022). https://doi.org/10.1038/s41592-022-01575-3
- [CellCharter](https://github.com/CSOgroup/cellcharter) by Marco Varrone _et al._, *CellCharter: a scalable framework to chart and compare cell niches across multiple samples and spatial -omics technologies*, _bioRxiv_ (2022). https://doi.org/10.1101/2023.01.10.523386 
- [COMMOT](https://www.nature.com/articles/s41592-022-01728-4) by Cang, Z. et al., *Screening cell–cell communication in spatial transcriptomics via collective optimal transport* _Nat Methods_ (2023). https://doi.org/10.1038/s41592-022-01728-4
- [SpiceMix](https://www.nature.com/articles/s41588-022-01256-z#citeas) by Childester, B. et al., *SpiceMix enables integrative single-cell spatial modeling of cell identity* _Nat Genet_ (2023). https://doi.org/10.1038/s41588-022-01256-z

## _Reviews_
- Moses, L., Pachter, L. *Museum of spatial transcriptomics.* _Nat Methods_ (2022). https://doi.org/10.1038/s41592-022-01409-2
- Longo, S.K., Guo, M.G., Ji, A.L. et al. *Integrating single-cell and spatial transcriptomics to elucidate intercellular tissue dynamics.* _Nat Rev Genet_ 22, 627–644 (2021). https://doi.org/10.1038/s41576-021-00370-8. Nice review with a focus on studying the tumor micronvironment.
- Palla, G., Fischer, D.S., Regev, A. et al. *Spatial components of molecular tissue biology.* _Nat Biotechnol_ 40, 308–318 (2022). https://doi.org/10.1038/s41587-021-01182-1
- Zeng, Z., Li, Y., Li, Y. et al. *Statistical and machine learning methods for spatially resolved transcriptomics data analysis.* _Genome Biol_ 23, 83 (2022). https://doi.org/10.1186/s13059-022-02653-7
- Liu, B., Li, Y., Zhang, L. *Analysis and Visualization of Spatial Transcriptomic Data* _Front. Genet._ (2022). https://doi.org/10.3389/fgene.2021.785290
- Williams, C.G. et al., *An introduction to spatial transcriptomics for biomedical research* _Genome Medicine_ (2022). https://doi.org/10.1186/s13073-022-01075-1
- Liu, Z. et al. *Evaluation of cell‑cell interaction methods by integrating single‑cell RNA sequencing data with spatial information* _Genome Biology_ (2022). https://doi.org/10.1186/s13059‑022‑02783‑y
- Li, H. et al., *A comprehensive benchmarking with practical guidelines for cellular deconvolution of spatial transcriptomics* _Nat Commun_ (2023). https://doi.org/10.1038/s41467-023-37168-7

## _Other resources_
Online workshops and explanations on several analytical approaches for spatial transcriptomics data analysis can be found [here](https://www.singlecell.de/index.php/resources/media/).
A book on geographical data science in Python: https://geographicdata.science/book/intro.html 
