# Dendro, AIND nextflow ephys pipeline, Slurm cluster

## Setup for MIT Engaging cluster

For using conda:

```bash
module load engaging/anaconda
```

For creating a new conda environment:

```bash
conda create --name env_nextflow python==3.9
```

For activating the conda environment:

```bash
conda activate env_nextflow
```

For installing nextflow in the conda environment:

```bash
conda activate env_nextflow
conda install bioconda::nextflow
```

Where the large data belongs, for now:

```bash
cd /orcd/data/dandi/002
```

Download an example dataset from 000409

https://neurosift.app/?p=/nwb&url=https://api.dandiarchive.org/api/assets/c04f6b30-82bf-40e1-9210-34f0bcd8be24/download/&dandisetId=000409&dandisetVersion=draft

```bash
wget https://api.dandiarchive.org/api/assets/c04f6b30-82bf-40e1-9210-34f0bcd8be24/download/ -O 000409-sub-CSHL045_ses-46794e05-3f6a-4d35-afb3-9165091a5a74_behavior+ecephys+image.nwb
```



