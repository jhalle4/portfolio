# Bioinformatician

## Education
M.S. Bioinformatics - New York University, December 2024  
B.S. Biomedical Engineering - The Pennsylvania State University, May 2020  

## Projects  

### Machine Learning-Based Classification of IBD from Transcriptomic Data 

This project explores the use of machine learning to classify patients with Crohn’s Disease, Ulcerative Colitis, or as healthy controls using transcriptomic data and clinical features. Models including SVM, decision tree, random forest, adaboost, and xgboost were trained on data from 2,471 participants. Using differentially expressed genes and metadata such as age and biopsy site, models were evaluated on standard metrics. Adaboost achieved the highest overall accuracy (82%), while SVM, random forest, and adaboost had the best AUC scores. Results show promise for improving diagnostic accuracy, though further research with broader condition coverage is needed.

[Project Report](IBD_Classifier_Final_Report.pdf)   
[Project Code](IBD_Classifier_code.pdf)

### Raw Sequencing Data Processing and DEG Analysis   

In this project, I conducted RNA-seq data processing and differential gene expression (DGE) analysis to study the effects of NRDE2 gene knockdown in human breast cancer cells (MDA-MB-231). The raw sequencing data was processed using the nf-core/rna-seq pipeline for quality control and read trimming. Expression quantification was performed with Salmon, and statistical analysis was carried out in R using DESeq2. My work included filtering low-expression genes, applying FDR correction, interpreting log-fold changes to identify genes significantly affected by NRDE2 depletion, and extracting their biological relevance. This analysis provided insights into the transcriptomic consequences of NRDE2 silencing and demonstrates my skills in bioinformatics workflows and RNA-seq data interpretation.  

[Project Report](NGS_Final_Project_Report.pdf)  
[Project Code](NGS_Final_Project_code.pdf)  
[MultiQC Report](NGS_multiQC_Report.html)  
