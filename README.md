# **Machine Learning-Based Bioactivity Perdication of EGFR**

**Target Protein: Epidermal Growth Factor (*EGFR*)**.

The target protein in this study is Epidermal Growth Factor Receptor (EGFR), a transmembrane tyrosine kinase receptor that plays a critical role in regulating:
-Cell proliferation.
-Differentiation.
-Survival pathways.
Overexpression or mutation of EGFR is strongly associated with Non-Small Cell Lung Cancer (NSCLC), making it a well-established therapeutic target in oncology.
Inhibiting EGFR signaling can suppress uncontrolled tumor growth and reduce cancer progression. This project focuses on applying machine learning approaches to predict bioactivity of compounds targeting EGFR.
This work builds upon my contribution to a published review discussing therapeutic strategies targeting EGFR in cancer treatment.

# **Objective**

To build a robust regression model capable of predicting the bioactivity (**pIC50** values) of compounds targeting *EGFR*, supporting early-stage virtual screening and lead optimization in NSCLC research.

# **Workflow of the Machine Learning Model**
The following workflow describes the full pipeline used for building the regression-based predictive model:

## Part 1: 

Data Collection.

Search for EGFR target data.

Collect bioactivity dataset from public databases (e.g., ChEMBL).

Retrieve compounds with experimental activity values (IC50).

Generate initial bioactivity dataset.

## Part 2: 

Data Preprocessing.

onvert structures to SMILES notation.

Clean dataset (remove duplicates, invalid entries).

Standardize molecules.

Lipinski's Rules Predication

Perform Exploratory Data Analysis (EDA).

Save cleaned dataset as CSV.

## Part 3: Feature Engineering.

Calculate molecular descriptors using PaDEL-Descriptor.

Generate molecular fingerprints.

Export descriptor matrix as CSV file.




