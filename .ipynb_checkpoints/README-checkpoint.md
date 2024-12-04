# DSC180A Quarter 1 Capstone

By Jason Hauk

## Project Purpose

Creating and testing a Polygenic Risk Score (PRS) built from publicly available datsets which estimates an individual’s genetic predisposition to have a trait based on a multitude of locations in the genome.

## How to Run

* To install the dependencies, run the following command from the root directory of the project: `pip install -r requirements.txt`
* Then run cells in PRS_Implementation.ipynb

## File Structure

```
├├── f
│
│
├── data
│  ├── EUR.1.test                            <- Contains all relevant components of genetic data for chromosome 1
│  │  ├── 1000G.EUR.1.bed                    <- Genotype information for chromosome 1 for EUR pop
│  │  ├── 1000G.EUR.1.bim                    <- SNP meta data for chromosome 1 for EUR pop
│  │  ├── 1000G.EUR.1.fam                    <- Ancestral data for chromosome 1 for EUR pop
│  ├── EUR.10.test                           <- Contains all relevant components of genetic data for chromosome 10
│  │  ├── 1000G.EUR.10.bed                   <- Genotype information for chromosome 10 for EUR pop
│  │  ├── 1000G.EUR.10.bim                   <- SNP meta data for chromosome 10 for EUR pop
│  │  ├── 1000G.EUR.10.fam                   <- Ancestral data for chromosome 10 for EUR pop
│  ├── EUR.11.test                           <- Contains all relevant components of genetic data for chromosome 11
│  │  ├── 1000G.EUR.11.bed                   <- Genotype information for chromosome 11 for EUR pop
│  │  ├── 1000G.EUR.11.bim                   <- SNP meta data for chromosome 11 for EUR pop
│  │  ├── 1000G.EUR.11.fam                   <- Ancestral data for chromosome 11 for EUR pop
│  ├── EUR.12.test                           <- Contains all relevant components of genetic data for chromosome 12
│  │  ├── 1000G.EUR.12.bed                   <- Genotype information for chromosome 12 for EUR pop
│  │  ├── 1000G.EUR.12.bim                   <- SNP meta data for chromosome 12 for EUR pop
│  │  ├── 1000G.EUR.12.fam                   <- Ancestral data for chromosome 12 for EUR pop
│  ├── EUR.13.test                           <- Contains all relevant components of genetic data for chromosome 13
│  │  ├── 1000G.EUR.13.bed                   <- Genotype information for chromosome 13 for EUR pop
│  │  ├── 1000G.EUR.13.bim                   <- SNP meta data for chromosome 13 for EUR pop
│  │  ├── 1000G.EUR.13.fam                   <- Ancestral data for chromosome 13 for EUR pop
│  ├── EUR.14.test                           <- Contains all relevant components of genetic data for chromosome 14
│  │  ├── 1000G.EUR.14.bed                   <- Genotype information for chromosome 14 for EUR pop
│  │  ├── 1000G.EUR.14.bim                   <- SNP meta data for chromosome 14 for EUR pop
│  │  ├── 1000G.EUR.14.fam                   <- Ancestral data for chromosome 14 for EUR pop
│  ├── EUR.22.test                           <- Contains all relevant components of genetic data for chromosome 22
│  │  ├── 1000G.EUR.22.bed                   <- Genotype information for chromosome 22 for EUR pop
│  │  ├── 1000G.EUR.22.bim                   <- SNP meta data for chromosome 22 for EUR pop
│  │  ├── 1000G.EUR.22.fam                   <- Ancestral data for chromosome 22 for EUR pop
│  ├── GD462.GeneQuantRPKM.50FN.samplename.resk10.txt.gz   <- Gene expression data for observed population
│  ├── gene_annot.txt.gz                     <- Annotations for to provide additional information about genes
│  └── genome_Tiffany_AmariutaBartell.vcf    <- Mentors genome for validating other phenotype predictions
│
├── PRS_Implementation.ipynb                 <- This notebook provides a step by step look at how to perform PRS
│
├── Report                                   <- Contains the files related to my Project 1 Report
│  ├── MUST FILL                             <- MUSTFILL
│
├── README.md                                <- README
│
└── requirements.txt                         <- Details the package requirements
```

## Summary

Not sure yet