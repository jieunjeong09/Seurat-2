# Seurat-2

# Vignette for spatial transcriptomic preliminary analysis

## The main source

This Rmarkdown is based on `https://satijalab.org/seurat/articles/spatial_vignette.html`
with some changes in graphics etv


## What we do

`SpatialTransc_jieun.Rmd` is the markdown file with initial processing of data from 10 X
Visium technology, obtained by testing and modifying (sometimes necessary) the main source.
For practical use, one
can add file saving commands for computed files and figures, and skip chunks with unwanted
figures etc.

This R markdown was tested and knitted, but sometimes its pdf does not display, so it may be necessary to download and view locally.

## Visual exploration

`shiny_two_layer.zip` packages an Rshiny application to explore gene expression distribution in voxels that have color-coded clusters.
It allows to assess distribution of markers of cell types like Vim, anatomic features like Plp1 etc., and it can be developed to a multi-functional dashboard.
After downloading and de-compression, it can be used as instructeed in `shiny_two_layer/README.txt`
