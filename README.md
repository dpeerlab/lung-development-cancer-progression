## lung-development-cancer-progression
# Single cell analysis in regenerative lineages and immune-mediated pruning in lung cancer metastasis

We used droplet-based single-cell RNA sequencing (scRNA-seq) and graph-based phenotypic analysis to explore tumor cell heterogeneity through the lens of epithelial regeneration in lung cancer metastasis, and to assess parallels between tumor cell plasticity and developmental hierarchies. Using patient tumors as well as a mouse model of lung cancer metastasis, our analyses identify regenerative cell types and lineage promiscuity in untreated primary tumors and reveal a range of embryonic lung morphogenic states in metastases.

# To run this Jupyter notebook:
Navigate to directory of choice, then:
` 
git clone https://github.com/dpeerlab/lung-development-cancer-progression.git
cd lung-development-cancer-progression
wget -P ./data/ https://s3.amazonaws.com/dp-lab-data-public/lung-development-cancer-progression/PATIENT_LUNG_ADENOCARCINOMA_ANNOTATED.h5
wget -P ./data/ https://s3.amazonaws.com/dp-lab-data-public/lung-development-cancer-progression/MOUSE_LUNG_ADENOCARCINOMA_METASTASIS_ANNOTATED.h5
pip install -r requirements.txt
`
Then run the notebook with ` jupyter notebook NMED2019_Laughney_SCanalyses_edit.ipynb ` .
