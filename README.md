# __Differential Gene Expression Analysis of Bulk RNA-Seq Data__
## 📌 Project Overview

This project focuses on differential gene expression (DGE) analysis using bulk RNA-sequencing data to identify genes that are significantly upregulated or downregulated between two biological conditions.
The dataset used in this study consists of astrocytes isolated from mice, comparing:
Control (normal immune status)
CCR2-altered / disease-associated condition
Astrocytes play a crucial role in neuroinflammation and immune signaling in the brain. Understanding changes in their gene expression helps in studying neurological disorders and immune-related mechanisms.

## 🎯 Objectives

Perform quality control and preprocessing of RNA-seq count data
Normalize gene expression values
Identify differentially expressed genes (DEGs)
Visualize results using statistical and graphical methods
Interpret biologically meaningful gene expression changes

## 🧬 Methodology

The analysis was carried out in R using standard RNA-seq analysis workflows.

Key steps include:

Data Import & Preprocessing
Raw count matrix loading
Sample grouping and metadata handling
Normalization
Library size normalization to remove technical bias
Differential Expression Analysis
Statistical testing to identify significant DEGs
Adjustment for multiple testing (FDR / adjusted p-values)
Visualization
MA plots
Volcano plots
Heatmaps of significant genes

## 🛠 Tools & Technologies Used

R Programming Language
Bioconductor packages (e.g., DESeq2 / edgeR)
R Markdown for reproducible analysis
ggplot2 for data visualization

## 📊 Results

Identified genes showing significant expression differences between control and CCR2-altered astrocytes
Highlighted potential genes involved in immune signaling and neuroinflammatory pathways
Visual summaries provide intuitive interpretation of results

## 📁 Repository Structure
├── R_final_assignment_2_grp_11.Rmd   # Main analysis file
├── README.md                        # Project documentation
├── data/                            # Input count data (if provided)
├── results/                         # Plots and output tables

## 🚀 How to Run the Project

Clone the repository:

git clone https://github.com/your-username/your-repo-name.git
Open R_final_assignment_2_grp_11.Rmd in RStudio
Install required packages (if not already installed)


## 📌 Learning Outcomes

Hands-on experience with bulk RNA-seq data analysis
Understanding of gene expression statistics
Practical exposure to biological data interpretation
Reproducible research using R Markdown

## 🔬 Future Scope

Pathway enrichment analysis (GO / KEGG)
Integration with single-cell RNA-seq data
Application of machine learning for gene classification

## 👤 Author

Dwaipayan M
B.Tech Biotechnology
Interested in Bioinformatics, Genomics, and Translational Research
