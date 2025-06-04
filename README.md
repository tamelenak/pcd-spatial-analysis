# Spatial analysis of paraneoplastic cerebellar degeneration in ovarian cancer with anti-Yo antibody positivity

This repository contains code and resources for quantitative MRI analysis of cerebellar atrophy and network alterations in anti-Yo paraneoplastic cerebellar degeneration (PCD), healthy controls, and SCA1 patients. It includes scripts for morphometric analysis, network construction, and machine learning classification to identify imaging biomarkers for early diagnosis and subgroup stratification.

## Getting Started

### 1. Clone the repository

```sh
git clone https://github.com/tamelenak/pcd-spatial-analysis.git
cd pcd-spatial-analysis
```

### 2. Create a new conda environment

```sh
conda env create -f environment.yml
conda activate pcdanalysis
```

### 3. Install requirements

```sh
pip install -r requirements.txt
```

### 4. Add the environment as a Jupyter kernel

```sh
pip install ipykernel
python -m ipykernel install --user --name=pcdanalysis
```

You are now ready to run the scripts and generate figures as described in the project documentation, and use the `pcdanalysis` kernel in your Jupyter notebooks.
