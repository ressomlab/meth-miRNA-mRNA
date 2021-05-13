# meth-miRNA-mRNA
This repository contains the datasets presented in the Frontiers in Genetics journal paper "Integrative analysis of DNA methylation and microRNA expression reveals mechanisms of disparity in hepatocellular carcinoma" by Rency S.Varghese, Megan Barefoot et al. that is submitted for review.

Preporcessed data from DNA methylation, miRNA-seq and mRNA-seq for HCC and adjacent normal tissues from 8 African American and 8 European American HCC patients.
The data has been preprocessed and non-normalized data is provided.
<br><br>
RNA-Seq_preprocessed_not normalized.csv -- matrix of RNA expression data.
<br><br>
miRNA-Seq_preprocessed_not normalized.csv -- matrix of miRNA expression data.
<br><br>
DNA_Methylation beta values_AA-stats.xlsx -- matrix of DNA methylation beta values after applying ANOVA model for AA group only. The DMRs and those CpGs significant (fdr < 0.05 and abs (beta difference) > 0.1 ) in the region are included, along with p-value and FDR values. 
<br><br>
DNA_Methylation beta values_EA-stats.xlsx -- matrix of DNA methylation beta values after applying ANOVA model for EA group only. The DMRs and those CpGs significant (fdr < 0.05 and abs (beta difference) > 0.1 ) in the region are included, along with p-value and FDR values. 
<br><br>
DNA_Methylation beta values_ALL-stats.xlsx -- matrix of DNA methylation beta values after applying ANOVA model for ALL (AA and EA combined). The DMRs and those CpGs significant (fdr < 0.05 and abs (beta difference) > 0.1 ) in the region are included, along with p-value and FDR values. 
