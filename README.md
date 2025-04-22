# Population and evolutionary genomics of three Anthophora species



## Assembly and annotation scripts

Location on GitHub: folder Assembly and annotation

-----------------------------------------------------------------------------------------------------------------------------------------
# Data preparation

## SNP calling and filtering

Location on GitHub: folder SNP_calling

The script full_pipe_SNP_calling.sh was used to 1) trim raw sequence files, 2) map the sequences on the reference genome, and 3) call and hardfilter high-quality SNPs and indels.
The script fetch_independ_neutral.sh was used to create the independent and neutral datasets as discribed in Taliadoros et al. 2025:


----------------------------------------------------------------------------------------------------------------------------------------

# Data analyses

## PCA and Admixture
Location on GitHub: folder 'Clustering_analyses'

Use the R script PCA.R to reproduce PCA plots.
The script admixture_Dom.sh was used to convert the vcf file into a plink format and run the admixture analysis.
The script make_qmap_pong.sh was used to visualise admixture results with pong.


## Nucleotide diversity and Tajima's D
Location on GitHub: folder 'Summary_statistics_and_divergence'

Use the script Pi_Td_Fst_Dxy.sh to obtain estimates for Nucleotide diversity and Tajima's D. The tsd.Rmd script visualizes the results and runs the Kruskal-Wallis and Wilcoxon tests.


## Population divergence
Location on GitHub: folder 'Summary_statistics_and_divergence'

Use the script Pi_Td_Fst_Dxy.sh to obtain Fst and Dxy estimates.

## Alighnment and species divergence
Location on GitHub: folder Cactus

the script FastaVCFToCounts.py was used to convert the VCF file to a cf file. Then the run_PoMo.sh was used to run the analysis

## MSMC2
Location on GitHub: folder MSMC2

the script run_msmc2 was used to perform infer variation in historical Ne

## GONE
Location on GitHub: folder GONE

the script run_gone was used to perform infer variation in Ne over in the recent past

## Runs of IBS
Location on GitHub: folder IBS

the script ibs.sh was used to perform infer long runs of identity by state (equivalent to long runs of homozygosity).
