# Mutation Analysis

### Performing Analysis on VCFs post mutation calling

#### Post-processing
In this notebook, I perform post-processing on vcf files obtained as output from HalotypeCaller, BCFTools & Mutect2 pipeline. 

Post-processing steps can comprise of multiple steps including but not limited to filtering based on quality, depth, homozygous or heterzygous mutations, indels vs SNVs etc. 

In this notebook I also plot Venn diagrams showing exclusive and common mutation in the tumor and control cells. Then I filter for heterozygous and homozygous SNVs which are saved separately. 

Mutation spectra plotting is done for exclusive CTC, WBC and Common mutation's heterozygous and homozygous SNVs using 'SigProfilerMatrixGenerator' from AlexandrovLab here https://github.com/AlexandrovLab/SigProfilerMatrixGenerator.

Also included are total read depth support plots to understand the read depth distribution in different cohort's mutations.
