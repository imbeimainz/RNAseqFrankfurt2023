# RNAseqFrankfurt2023

This repository contains

* A compact lecture, rendered as html slides (`RNAseq_Frankfurt_lecture.html`)
* A full version of that lecture, rendered as html slides (`RNAseq_one_full_day.html`)
* A practical session document (`RNAseq_Frankfurt_practical.html`)
* The source files for each of these files

For the practical session, open the `RNAseq_Frankfurt.Rproj` file in RStudio, and 
open the `RNAseq_Frankfurt_practical.Rmd` file to follow along the different chunks.

To make sure you're all set for running the code interactively, run this command:

```
install.packages("BiocManager")
BiocManager::install()
BiocManager::install(
  c("knitr",
    "rmarkdown",
    "DESeq2",
    "tximeta",
    "org.Hs.eg.db",
    "ExploreModelMatrix",
    "pcaExplorer",
    "ideal",
    "macrophage",
    "apeglm",
    "pheatmap",
    "iSEE",
    "GeneTonic",
    "topGO",
    "clusterProfiler"
  )
)
```
