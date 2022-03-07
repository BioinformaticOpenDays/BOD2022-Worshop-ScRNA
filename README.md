# BOD2022 Workshop ScRNA - One cell at a time
A workshop to explore the current methods for processing and analysing scRNA-seq datasets. From the read count matrices to cell trajectories and other advanced insights.

## Details

1h 30min duration
K participants

## Presenters

- Ana Luisa Falcão 
- Diogo Macedo 
- Mónica Fernandes 

## Curriculum

- Data Intake and Read Mapping
  - Cell Ranger Danger
- Preprocessing Read Counts
  - Quality Control
    - Count depth
    - Number of genes per barcode
  - Normalization
    - z-scores
  - Filtering
    - Highly expressed genes
  - Data Correction
    - Doublets prediction
    - Batch effect
  - Data Integration
- Analysing Read Counts
  - Visualization and Dimensionality Reduction
  - Clustering
    - Leiden Comunity
    - Inter group
    - Inter sample
  - Trajectory Inferance
    - DPT pseudeotime
  - Marker Genes
    - Dot Plot
    - Inter group
    - Inter sample
    

## What to do before you join us

```bash

conda env create diodupmia/bodxi_scrna_workshop
source activate bodxi_scrna_workshop

```

```bash
conda env create -f bodxi_scrna_workshop.yml
source activate bodxi_scrna_workshop
```

### Link for env

https://anaconda.org/diodupima/bodxi_scrna_workshop
