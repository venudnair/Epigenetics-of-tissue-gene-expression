README.md

Integrative analysis of transcriptome and epigenome across rat tissues and in response to exercise training

Differential gene expression, chromatin accessibility, and methylation pipelines and codes for PLIER analysis used in the study.

Manuscript on BioRxiv:

MoTrPAC website: https://motrpac.org

MoTrPAC Study Group manuscript: https://www.biorxiv.org/content/10.1101/2022.09.21.508770v2

MoTrPAC data and pipelines: 
https://motrpac-data.org/
https://motrpac.github.io/MotrpacRatTraining6mo/
https://motrpac.github.io/MotrpacRatTraining6moData/
https://github.com/MoTrPAC/motrpac-rna-seq-pipeline 
https://github.com/MoTrPAC/motrpac-atac-seq-pipeline 
https://github.com/MoTrPAC/motrpac rrbs-pipeline


Codes used in the study

Tissue_DEGs_dds_dataset.R : Differential gene expression analysis across tissues using Deseq2

EET_DEGs.R : Analysis of exercise regulated genes across tissues

EET_DEGs_8tissues_dds_dataset.R : Differential expression analysis of exercise regulated genes across tissues

Tissue_DMRs.R : Differential methylation analysis using RnBeads 

Tissue_DARs_counted.R : Differential chromatin accessibility analysis using DiffBind

PLIER.R : 


Data used in the study are deposited in Zenodo (https://zenodo.org/deposit/7199920#)

Type                    			    Assay   Tissue	  	    Object					                Size (MiB)	

  Differential_analysis_results 		ATAC	  SKM_vs_BAT	  ATAC_counted_SKM_BAT.RData              680	

Differential_analysis_results	  	ATAC	  SKM_vs_Heart	  ATAC_counted_SKM_Heart.RData			     1100	

Differential_analysis_results 		ATAC	  SKM_vs_Hippoc	  ATAC_counted_SKM_Hippoc.RData		        739	

Differential_analysis_results 		ATAC	  SKM_vs_Kidney	  ATAC_counted_SKM_Kidney.RData		        717	

Differential_analysis_results 		ATAC	  SKM_vs_Liver  	ATAC_counted_SKM_Liver.RData			      739	

Differential_analysis_results 		ATAC	  SKM_vs_Lung	    ATAC_counted_SKM_Lung.RData  		        711

Differential_analysis_results 		ATAC	  SKM_vs_WAT	    ATAC_counted_SKM_WAT.RData			        712	

Differential_analysis_results		  RNA	    SKM_vs_7tissues     RNA_SKM_vs_7tissues.RData           1.5	

Differential_analysis_results		  RNA	    1tissue_vs_7tissues RNA_ERGs_8tissues.RData             0.42

Differential_analysis_results 		RRBS	  SKM_vs_BAT	    rnbSet_SKM_vs_BAT_unnormalized.zip* 	  207

Differential_analysis_results		  RRBS	  SKM_vs_Heart	  rnbSet_SKM_vs_Heart_unnormalized.zip*	  198

Differential_analysis_results 		RRBS	  SKM_vs_Hippoc	  rnbSet_SKM_vs_Hippoc_unnormalized.zip* 	198

Differential_analysis_results 		RRBS	  SKM_vs_Kidney	  rnbSet_SKM_vs_Kidney_unnormalized.zip*	198	

Differential_analysis_results 		RRBS	  SKM_vs_Liver	  rnbSet_SKM_vs_Liver_unnormalized.zip* 	198

Differential_analysis_results 		RRBS	  SKM_vs_Lung	    rnbSet_SKM_vs_Lung_unnormalized.zip* 	  202

Differential_analysis_results 		RRBS	  SKM_vs_WAT	    rnbSet_SKM_vs_WAT_unnormalized.zip*  	  200	

* Do not unzip the files. Load the .zip folder to RnBeads for analysis

