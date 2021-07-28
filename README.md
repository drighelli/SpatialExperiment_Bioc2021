# Bioc2021 SpatialExperiment Workshop

This three-parts workshop provides basics backgroud and the instruments 
to start to work with spatial transcriptomics with R/Bioconductor.

The first part is an overview of the most widely used technologies for 
spatially resolved transcriptomics, such as seqFISH and 10x Genomics Visium, 
and the main differences between them.

The second part is mainly focused on the `SpatialExperiment` class and how to handle
its methods for storing and retrieving spatial coordinates, images, and how to manage them.

The third part will show how to store/retrieve already stored spatial datasets 
from the `STexampleData` and `10xVisiumData` packages and how to generate plots 
with `ggspavis`.

The workshop will end with a mini-challenge for the attendees to handle with 
provided tools during the sessions.

# Authors:

- [Dario Righelli](github.com/drighelli) (dario.righelli@gmail.com)
- [Helena L. Crowell](github.com/HelenaLC) (helena.crowell@uzh.ch)
- [Lukas M. Weber](https://lmweber.org/) (lukas.weber@jhu.edu)


# Pre-requisites

- Basic R syntax knowledge and R data structures
- Familiarity with [SingleCellExperiment](https://bioconductor.org/packages/SingleCellExperiment/) and/or [SummarizedExperiment](https://bioconductor.org/packages/SummarizedExperiment/) classes 



# Available Resources

- Link to the `pkgdown` [website](https://drighelli.github.io/SpatialExperiment_Bioc2021/).
- Link to [Docker image](https://hub.docker.com/r/drighelli/spatialexperiment_bioc2021).
- The `SpatialExperiment` [link](https://bioconductor.org/packages/SpatialExperiment/). 
- The `STexampleData` package [link](https://bioconductor.org/packages/STexampleData).
- The `TENxVisiumData` package [link](https://bioconductor.org/packages/TENxVisiumData).
- The `ggspavis` package [link](https://github.com/lmweber/ggspavis).


## To use the Docker image:

We highly suggest to use the docker image within all the needed material.

```sh
docker run -e PASSWORD=<SET_A_PASSWORD> -p 8787:8787 drighelli/spatialexperiment_bioc2021
```

Once running, navigate to https://localhost:8787/ and then login with `rstudio`:`<YourChosenPassword>`.

