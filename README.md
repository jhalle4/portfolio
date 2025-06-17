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

### Investigating Peanut Allergy Sensitization Through Predicted Protein Protein Interactions 

In this project, I used the Topsy-Turvy protein-protein interaction algorithm to predict interactions between peanut allergens and human immune proteins. The analysis screened over a million protein pairs and identified 356 high-confidence interactions. Motif discovery (via MEME), gene ontology enrichment, and Reactome pathway analysis were used to characterize these interactions. Key findings included the allergen Ara h 3’s broad binding potential and links to PD-1 signaling and CD209, suggesting possible mechanisms for severe allergic reactions and initial peanut sensitization.

[Project Report](Proteomics_Final_Project_report.pdf)

### Identifying Single Nucleotide Polymorphisms Associated with Hypertension risk

In this project, I developed a pipeline to automatically curate and preprocess genetic and clinical data from open-source repositories. This involved web scraping, file parsing across multiple formats, and handling corrupted or incomplete datasets. From nearly 400 files, relevant genetic features were extracted and used to train an XGBoost classifier. Hyperparameters were optimized, and the model was evaluated using Monte Carlo cross-validation with 1,000 iterations. The average model achieved 72% accuracy, consistently outperforming random prediction. ROC analysis demonstrated the model’s robustness across classification thresholds, and feature importance analysis provided insight into the variables most associated with hypertension. This methodology could be scaled to larger datasets incorporating lifestyle and demographic features for broader clinical relevance.  

[Project Notebook](Capstone_Final_draft.ipynb)

### Comparative Genomic Analysis of SARS and COVID-19 Using dN/dS Ratios  

In this project, I analyzed evolutionary pressures on viral genomes by calculating dN/dS ratios between SARS and COVID-19 protein-coding genes. Using R packages such as biomartr and orthologr, I retrieved coding sequences from NCBI RefSeq and performed pairwise alignments to identify orthologous genes. The dN/dS ratio, representing the rate of non-synonymous to synonymous mutations, was used to assess signs of positive or purifying selection. This analysis offers insights into how viral proteins have evolved and highlights targets under selective pressure, which could guide vaccine development and preparedness for future outbreaks.

[Project Report](Viral_evolutionary_predictions_report.pdf)



