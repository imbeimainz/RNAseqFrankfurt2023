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
  c(
    ## some packages for basic operations
    "knitr",
    "rmarkdown",
    ## the main DE framework we will use
    "DESeq2",
    ## the data package
    "macrophage",
    ## for the enrichment analyses
    "topGO",
    "clusterProfiler",
    ## some interactive shiny apps and packages
    "pcaExplorer",
    "ideal",
    "GeneTonic",
    "iSEE",
    ## some corollary packages required to run all the code
    "tximeta",
    "org.Hs.eg.db",
    "ExploreModelMatrix",
    "apeglm",
    "pheatmap",
    "iSEEu",
    "edgeR"
  )
)
```

