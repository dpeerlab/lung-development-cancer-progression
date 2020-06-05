# Single Cell Analysis in Regenerative Lineages and Immune-mediated Pruning in Lung Cancer Metastasis

Laughney, A.M., Hu, J., Campbell, N.R. et al. Regenerative lineages and immune-mediated pruning in lung cancer metastasis. Nat Med 26, 259–269 (2020). https://doi.org/10.1038/s41591-019-0750-6


We used droplet-based single-cell RNA sequencing (scRNA-seq) and graph-based phenotypic analysis to explore tumor cell heterogeneity through the lens of epithelial regeneration in lung cancer metastasis, and to assess parallels between tumor cell plasticity and developmental hierarchies. Using patient tumors as well as a mouse model of lung cancer metastasis, our analyses identify regenerative cell types and lineage promiscuity in untreated primary tumors and reveal a range of embryonic lung morphogenic states in metastases.

## To Run Jupyter Notebook:

Navigate to directory of choice, then:

```bash
git clone https://github.com/dpeerlab/lung-development-cancer-progression.git

cd lung-development-cancer-progression

wget -P ./data/ https://s3.amazonaws.com/dp-lab-data-public/lung-development-cancer-progression/PATIENT_LUNG_ADENOCARCINOMA_ANNOTATED.h5

wget -P ./data/ https://s3.amazonaws.com/dp-lab-data-public/lung-development-cancer-progression/MOUSE_LUNG_ADENOCARCINOMA_METASTASIS_ANNOTATED.h5
```

Create a virtual environment to avoid any conflict with other packages. First, install Miniconda for Python 3+: https://docs.conda.io/en/latest/miniconda.html

```bash
conda create -n workspace python=3.8.2 pip
conda activate workspace
```

Install dependencies:

```bash
pip install Cython
pip install -r requirements.txt
```

Then, run the notebook with:

```bash
jupyter notebook NMED2019_Laughney_SCanalyses_edit.ipynb
```
