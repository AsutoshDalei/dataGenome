# Rainbow Trout Genotype-Based Gender Prediction

## Project Overview  
This project focuses on using genomic data to accurately predict the gender of rainbow trout (*Oncorhynchus mykiss*). Gender identification in fish is crucial for effective breeding and management practices, but traditional methods are invasive, time-consuming, and unreliable for juvenile fish. By leveraging machine learning and genomic data, this project aims to develop a robust and efficient model for identifying fish gender.

## Data Description  
- **Genomic Data:** The dataset comprises genotype information from rainbow trout. It includes 15 sex-related single nucleotide polymorphisms (SNPs) known to be linked with sex determination.  
- **Simulated and Real Data:** The model is trained and validated on both simulated datasets with varying genotyping error rates and real-world data from a rainbow trout breeding program.  
- **Data Coding:** Genotypes are encoded as 1 for heterozygotes (typically male) and 2 for homozygotes (typically female), with missing data marked as 'NaN'.

## Methodology  
The project employs several **supervised machine learning** techniques, which are known for their high accuracy and robustness to noisy data. Unlike traditional probabilistic methods, ML models does not rely on prior knowledge of specific marker expressions, making it well-suited for diverse and complex datasets.

### Key Features of the Methodology  
- **No Imputation Required:** The model handles missing data naturally without imputation.  
- **Cross-Validation:** Five-fold and two-fold cross-validation techniques ensure the reliability and generalizability of predictions.  
- **Hyperparameter Optimization:** Grid search and cross-validation are used to fine-tune model hyperparameters for optimal performance.  
- **Feature Importance Analysis:** SNP importance is assessed to identify the most predictive markers.

## Expected Outcomes  
- **High Accuracy:** The model aims to achieve high prediction accuracy on real-world datasets, making it suitable for practical use in breeding programs.  
- **Scalable and Adaptable:** The methodology can be extended to other fish species or similar genomic classification problems.

## Applications  
- Fish breeding programs for sex-based selection.  
- Automation of gender identification processes in aquaculture.  
- Research into genomic markers and their role in sex determination.  
