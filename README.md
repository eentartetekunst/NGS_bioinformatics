# NGS_bioinformatics

The directory contains:
1. HW1_quality_evaluation_FastQC_MultiQC.ipynb - MultiQC quality check of the aequencing data. The quality score of the samples is good (Phred score is above 27); Low level of duplication; GC content around 50%, but bad Per Base Sequence Content
The proportion of each base position for which each of the four normal DNA bases has been called.  Click a sample row to see a line plot for that dataset.  The report can be found at [MultiQC Report.pdf](https://github.com/eentartetekunst/NGS_bioinformatics/files/9946324/MultiQC.Report.pdf)

2. HW2_subread_pca.ipynb - mapping of files was performed using hisat2. The mapping score was moderate, about 90%, and it barely improved after transcript assembly and re-mapping with stringtie. The samples were visualised with PCA (genes were used as features). For some reason, C14.5 was closer to the brain  samples compared to cerebellum samples. 


3. Differential expression analysis was performed via EdgeR. 6 clusters were generated. In clusters 1,3 and 6 mean z-score increased with age, while in the other clusters an opposite situation is observed for both tissues. 
