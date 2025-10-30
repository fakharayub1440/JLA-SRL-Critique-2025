# JLA-SRL-Critique-2025
Data and code for the JLA paper "Predictive Markers or Causal Levers? A Methodological Critique of Self-Regulated Learning Proxies in Log Data."
# Replication Data for: "Predictive Markers or Causal Levers? A Methodological Critique of Self-Regulated Learning Proxies in Log Data"

This repository contains the complete dataset, analysis code, and supplementary materials for our paper submitted to the Journal of Learning Analytics (JLA). The goal of this repository is to ensure full transparency and allow for the complete reproduction of all findings, figures, and tables presented in the manuscript.

## Repository Structure

-   `/data/`: Contains the three disjoint parquet files used for the analysis.
    -   `d1_efa_discovery.parquet`: The discovery set (50% of students), used for exploratory factor analysis.
    -   `d2_cfa_confirmation.parquet`: The confirmation set (25% of students), used for confirmatory analyses and model diagnostics.
    -   `d3_holdout_final.parquet`: The final holdout set (25% of students), used only for the final, out-of-sample estimation of predictive effects.
-   `main_analysis.ipynb`: A Jupyter Notebook containing all Python code required to run the analysis from start to finish. This notebook will reproduce all key figures and tables from the paper.
-   `requirements.txt`: A list of all necessary Python libraries to create the correct environment for running the analysis.
-   `/figures/`: This folder contains the final, high-resolution versions of all figures presented in the paper.

## How to Reproduce the Results

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/[Your-GitHub-Username]/JLA-SRL-Critique-2025.git
    cd JLA-SRL-Critique-2025
    ```

2.  **Set up the Environment:**
    It is recommended to use a virtual environment. Install all required packages using:
    ```bash
    pip install -r requirements.txt
    ```

3.  **Run the Analysis:**
    Open the `main_analysis.ipynb` notebook in a Jupyter environment (like Jupyter Lab or Google Colab) and run the cells sequentially. The notebook is structured to follow the two-phase pipeline described in the paper:
    -   **Phase 1:** Psychometric Validation
    -   **Phase 2:** Predictive Analysis

## Data Availability

The data used in this study is a pre-processed subset of the publicly available ASSISTments 2012-2013 "skill builder" dataset. The pre-processing steps are detailed in the Jupyter Notebook.

## Citation

If you use this code or data in your own research, please cite our paper:

> 
