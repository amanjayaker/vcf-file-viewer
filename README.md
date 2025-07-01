#  VCF Polymorphic SNP Visualizer (Streamlit App)

This interactive Streamlit app allows exploration of VCF files for identifying polymorphic SNPs across samples.

## Features

- SNP window-based density heatmaps
- PCA and clustering (dendrograms)
- Outlier detection via Isolation Forest
- Sample similarity via cosine distance
- Homozygous ALT signature SNP identification

##  Run Locally

```bash
pip install -r requirements.txt
streamlit run app.py
