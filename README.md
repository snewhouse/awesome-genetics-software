# awesome-genetics-software
A list of cool software for genetic analysis and the like.

*currenty in no particluar order. Please contribute.You can add to it, reorganise it..but don't delete it*

# Content
1. [GWAS](#gwas)
2. [Heritability Estimation](#heritability-estimation)
3. [Polygenic Risk Score](#polygenic-risk-score)
4. [Population Stratification](#population-stratification)

# GWAS

- **PLINK2** [https://www.cog-genomics.org/plink/2.0/](https://www.cog-genomics.org/plink/2.0/)

- **imputePrepSanger** [https://github.com/eauforest/imputePrepSanger](https://github.com/eauforest/imputePrepSanger): This pipeline takes plink genotype files, and adjusts the strand, the positions, the reference alleles, performs quality control steps and output a vcf file that satisfies the requirement for submission to the Sanger Imputation Service (https://imputation.sanger.ac.uk/) for imputation using the Haplotype Reference Consortium reference panel.

- **bgenie** [https://jmarchini.org/bgenie](https://jmarchini.org/bgenie/): A program for efficient GWAS for multiple continuous traits and PHEWAS with many features designed and optimized for large scale analysis.  

# Heritability Estimation

- **GCTA** [http://cnsgenomics.com/software/gcta/](http://cnsgenomics.com/software/gcta/): GCTA (Genome-wide Complex Trait Analysis) was originally designed to estimate the proportion of phenotypic variance explained by genome- or chromosome-wide SNPs for complex traits (the GREML method), and has subsequently extended for many other analyses to better understand the genetic architecture of complex traits

- **LDSC** [https://github.com/bulik/ldsc](https://github.com/bulik/ldsc): ldsc is a command line tool for estimating heritability and genetic correlation from GWAS summary statistics. ldsc also computes LD Scores.

# Polygenic Risk Score

- **PRSice** [https://github.com/choishingwan/PRSice](https://github.com/choishingwan/PRSice): PRSice (pronounced 'precise') is a software package for calculating, applying, evaluating and plotting the results of polygenic risk scores (PRS). PRSice can run at high-resolution to provide the best-fit PRS as well as provide results calculated at broad P-value thresholds, illustrating results corresponding to either, can thin SNPs according to linkage disequilibrium and P-value ("clumping"), and can be applied across multiple traits in a single run.

- **PRS-on-Spark (PRSoS)** [https://github.com/MeaneyLab/PRSoS](https://github.com/MeaneyLab/PRSoS): PRS-on-Spark (PRSoS) generates polygenic risk scores (PRS) for large genotype data, including imputed genotype posterior probabilites. PRSos performs faster than PRSice v1.25 for large number of SNPs (~17 million) and by including imputated posterior probabilities and strand-ambiguous SNPs it modestly increases the proportion of variance explained by a PRS for major depressive disorder ([Chen et al., 2018](https://bmcbioinformatics.biomedcentral.com/articles/10.1186/s12859-018-2289-9)). It can use multiple cores to increase processing efficiency (i.e., reduce processing time). PRSoS is compatible with Linux, Mac OS, and Windows. It runs using Apache Spark and Python.

- **lassosum** [https://github.com/tshmak/lassosum](https://github.com/tshmak/lassosum): lassosum is a method for computing LASSO estimates of a linear regression problem given summary statistics from GWAS and Genome-wide meta-analyses, accounting for Linkage Disequilibrium (LD), via a reference panel. The reference panel is assumed to be in PLINK format. Summary statistics are expected to be loaded into memory as a data.frame/data.table.

- **LDpred** [https://github.com/bvilhjal/ldpred](https://github.com/bvilhjal/ldpred): LDpred is a Python based software package that adjusts GWAS summary statistics for the effects of linkage disequilibrium (LD). The details of the method is described in Vilhjalmsson et al. (AJHG 2015) [http://www.cell.com/ajhg/abstract/S0002-9297(15)00365-1]

# Population Stratification

- **FlashPCA2** [https://github.com/gabraham/flashpca](https://github.com/gabraham/flashpca): FlashPCA performs fast principal component analysis (PCA) of single nucleotide polymorphism (SNP) data, similar to smartpca from EIGENSOFT (http://www.hsph.harvard.edu/alkes-price/software/) and shellfish (https://github.com/dandavison/shellfish). FlashPCA is based on the https://github.com/yixuan/spectra/ library.

- **ADMIXTURE** [https://www.genetics.ucla.edu/software/admixture/](https://www.genetics.ucla.edu/software/admixture/): ADMIXTURE is a software tool for maximum likelihood estimation of individual ancestries from multilocus SNP genotype datasets. It uses the same statistical model as STRUCTURE but calculates estimates much more rapidly using a fast numerical optimization algorithm. 

- **EIGENSOFT** [https://github.com/DReichLab/EIG](https://github.com/DReichLab/EIG): The EIGENSOFT package implements methods from the following 2 papers: Patterson et al. 2006 PLoS Genet 2:e190 (population structure), Price et al. 2006 Nat Genet 38:904-9 (EIGENSTRAT stratification correction)

*****

