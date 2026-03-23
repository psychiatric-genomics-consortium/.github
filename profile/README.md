![](PGC.png)

# The Psychiatric Genomics Consortium

## Our Mission 
The Psychiatric Genomics Consortium is one of the most innovative experiments in the history of psychiatry. We have unified much of the field to enable rapid progress in elucidating the genetic basis of psychiatric disorders. We have 800+ investigators from 36 countries and >400K subjects. 

## Software and Resources
The PGC has attracted a cadre of outstanding scientists whose careers center on our work. Many of those researchers have used our data to develop valuable tools for understanding psychiatric genomics, often with important applications in complex trait genetics more generally. We have gathered repositories for such software within our GitHub, and provide descriptions for each below:

TODO
### CC-GWAS 
#### Development lead: Wouter Peyrot

#### [Original GitHub](https://github.com/mkoromina/SAFFARI) 
#### [PGC repo version](https://github.com/psychiatric-genomics-consortium/SAFFARI)
#### [Paper](https://www.nature.com/articles/s41593-025-01998-z)

SAFFARI is a Snakemake pipeline that implements four different individual variant fine-mapping methods (SuSiE, FINEMAP, PolyFun+SuSiE, PolyFun+FINEMAP). It supports large-scale processing of multiple traits and loci using UK Biobank LD panels and user-specified annotations.
TODO

### GenomicSEM 
#### Development lead: Andrew Grotzinger, Michel Nivard
#### [Original GitHub](https://github.com/GenomicSEM/GenomicSEM) | [PGC repo version](https://github.com/psychiatric-genomics-consortium/GenomicSEM) | [Paper](https://pubmed.ncbi.nlm.nih.gov/30962613/)

GenomicSEM is an R-package for fitting user-defined structural equation models to genetic overlap inferred from GWAS summary statistics. Example models that can be run include those with latent factors statistically defined to index shared signal across multiple traits or multiple regression models that estimate partial genetic effects of correlated predictors. Extensions allow for estimating functional enrichment (Stratified Genomic SEM), effects of genetic variants (multivariate GWAS), or associations with imputed gene expression from TWAS (T-SEM) in the model. 

----

### PRS-CS
#### Development lead: Tian Ge
#### [Original GitHub](https://github.com/getian107/PRScs) | [PGC repo version](https://github.com/psychiatric-genomics-consortium/PRScs) | [Paper](https://www.nature.com/articles/s41467-019-09718-5)

PRS-CS is a Python-based command line tool that provides weights for polygenic risk scores through inferring posterior SNP effect sizes under continuous shrinkage (CS) priors using GWAS summary statistics and an external LD reference panel.

----

### PRS-CSx 
#### Development lead: Tian Ge
#### [Original GitHub](https://github.com/getian107/PRScsx) | [PGC repo version](https://github.com/psychiatric-genomics-consortium/PRScsx) | [Paper](https://pmc.ncbi.nlm.nih.gov/articles/PMC9117455/)

PRS-CSx extends PRS-CS to integrate GWAS summary statistics and external LD reference panels from multiple populations to improve cross-population polygenic prediction. 

----

### SAFFARI 
#### Development lead: Maria Koromina
#### [Original GitHub](https://github.com/mkoromina/SAFFARI) | [PGC repo version](https://github.com/psychiatric-genomics-consortium/SAFFARI) | [Paper](https://www.nature.com/articles/s41593-025-01998-z)

SAFFARI is a Snakemake pipeline that implements four different individual variant fine-mapping methods (SuSiE, FINEMAP, PolyFun+SuSiE, PolyFun+FINEMAP). It supports large-scale processing of multiple traits and loci using UK Biobank LD panels and user-specified annotations.

----

### Tractor 
#### Development lead: Elizabeth Atkinson
#### [Original GitHub](https://github.com/Atkinson-Lab/TractorWorkflow) | [PGC repo version](https://github.com/psychiatric-genomics-consortium/TractorWorkflow) | [Paper](https://pubmed.ncbi.nlm.nih.gov/33462486/) | [Preprint](https://www.biorxiv.org/content/10.1101/2025.09.02.673402) | [Tutorial](https://atkinson-lab.github.io/Tractor-tutorial/)

Tractor is a method for local-ancestry aware genome-wide association studies, facilitating variant discovery in admixed populations. A WorkFlow pipeline is available, allowing implementation of the approach without the need for advanced bioinformatic expertise.

----

### Tractor-Mix 
#### Development lead: Elizabeth Atkinson
#### [Original GitHub](https://github.com/Atkinson-Lab/Tractor-Mix) | [PGC repo version](https://github.com/psychiatric-genomics-consortium/Tractor-Mix) | [Preprint](https://www.medrxiv.org/content/10.1101/2025.05.27.25328444)

Tractor-Mix extends Tractor to a mixed-model implementation, allowing analyses to be conducted using data from related indivduals.

## Paper repositories

### PGC MDD3
#### The paper: ["Trans-ancestry genome-wide study of depression identifies 697 associations implicating cell types and pharmacotherapies"](https://pubmed.ncbi.nlm.nih.gov/39814019/)
[Public repo](https://github.com/psychiatric-genomics-consortium/mdd-wave3-meta)

----

### Genetic structure of depressive symptoms
#### The paper: ["Genome-wide meta-analysis of ascertainment and symptom structures of major depression in case-enriched and community cohorts"](https://doi.org/10.1017/S0033291724001880)
[Public repo](https://github.com/psychiatric-genomics-consortium/mdd-symptom-gwas)

## Contact
If you would like additional software to be added to this GitHub, or modifications to be made to this README, please contact [JoniColeman](https://github.com/JoniColeman)
