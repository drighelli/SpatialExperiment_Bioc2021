# Bioc2021 SpatialExperiment Workshop

This three-part workshop provides background and tools to start working with 
spatially resolved transcriptomics data with R/Bioconductor.

The first part is an overview of the most widely used technologies for 
spatially resolved transcriptomics, such as 10x Genomics Visium and seqFISH, 
and the main differences between them.

The second part is focused on the `SpatialExperiment` class and how to handle
its methods for storing and retrieving spatial coordinates, images, and how to 
manage them.

The third part will show how to retrieve datasets in `SpatialExperiment` format 
from the `STexampleData` and `10xVisiumData` packages, and how to generate plots 
with the `ggspavis` package.

The workshop will end with a mini-challenge for attendees using the tools 
provided during the sessions.


# Link

https://drighelli.github.io/SpatialExperiment_Bioc2021/index.html


# Authors

- [Dario Righelli](github.com/drighelli) (dario.righelli@gmail.com)
- [Helena L. Crowell](github.com/HelenaLC) (helena.crowell@uzh.ch)
- [Lukas M. Weber](https://lmweber.org/) (lukas.weber@jhu.edu)


# Pre-requisites

- Basic R syntax knowledge and R data structures
- Familiarity with [SingleCellExperiment](https://bioconductor.org/packages/SingleCellExperiment/) and/or [SummarizedExperiment](https://bioconductor.org/packages/SummarizedExperiment/) classes 


# Available resources

- Link to the `pkgdown` [website](https://drighelli.github.io/SpatialExperiment_Bioc2021/).
- Link to [Docker image](https://hub.docker.com/r/drighelli/spatialexperiment_bioc2021).
- The `SpatialExperiment` package [link](https://bioconductor.org/packages/SpatialExperiment/). 
- The `STexampleData` package [link](https://bioconductor.org/packages/STexampleData).
- The `TENxVisiumData` package [link](https://bioconductor.org/packages/TENxVisiumData).
- The `ggspavis` package [link](https://github.com/lmweber/ggspavis).


# To use the Docker image

We highly recommend using the Docker image, which contains all the needed material.

```sh
docker run -e PASSWORD=<SET_A_PASSWORD> -p 8787:8787 drighelli/spatialexperiment_bioc2021
```

Once running, navigate to https://localhost:8787/ and then login with `rstudio`:`<YourChosenPassword>`.

