---
title: "Lauffenburger Lab - Code"
layout: textlay
excerpt: "Lauffenburger Lab -- Code."
sitemap: false
permalink: /code/
---


# Code

---

## [Large-scale knowledge-EMBedded Artificial Signaling-networks (LEMBAS)](https://github.com/Lauffenburger-Lab/LEMBAS)

<img src="{{ site.url }}{{ site.baseurl }}/images/codepic/lembas.jpg" style="width: 400px"> 

Mammalian cells adapt their functional state in response to external signals in form of ligands that bind receptors on the cell-surface. Mechanistically, this involves signal-processing through a complex network of molecular interactions that govern transcription factor activity patterns. Computer simulations of the information flow through this network could help predict cellular responses in health and disease. Here we develop a recurrent neural network framework constrained by prior knowledge of the signaling network with ligand-concentrations as input and transcription factor -activity as output. Applied to synthetic data, it predicts unseen test-data (Pearson correlation r=0.98) and the effects of gene knockouts (r=0.8). We stimulate macrophages with 59 different ligands, with and without addition of lipopolysaccharide, and collect transcriptomics data. The framework predicts this data under cross-validation (r=0.8) and knockout simulations suggest a role for RIPK1 in modulating the lipopolysaccharide response. This work demonstrates the feasibility of genome-scale simulations of intracellular signaling.

---

## [COVID-19 Breastmilk Antibody Transfer Analysis](https://github.com/Lauffenburger-Lab/COVID19-Breastmilk-Antibody-Transfer)

<img src="{{ site.url }}{{ site.baseurl }}/images/codepic/ab_bm.jpg" style="width: 300px">

Antibody transfer via breastmilk represents an evolutionary strategy to boost immunity in early life. Although SARS-CoV-2-specific antibodies have been observed in the breastmilk, the functional quality of these antibodies remains unclear. Here, we applied systems serology to characterize SARS-CoV-2-specific antibodies in maternal serum and breastmilk to compare the functional characteristics of antibodies in these fluids. Distinct SARS-CoV-2-specific antibody responses were observed in serum and breastmilk of lactating individuals previously infected with SARS-CoV-2, with a dominant transfer of IgA and IgM into breastmilk. Although IgG were present in breastmilk, they were functionally attenuated. We observed a preferential transfer of antibodies capable of eliciting neutrophil phagocytosis and neutralization compared to other functions, pointing to selective transfer of certain functional antibodies to breastmilk. These data highlighted the preferential transfer of SARS-CoV-2-specific IgA and IgM to breastmilk, accompanied by select IgG subpopulations, positioned to create a non-pathologic, but protective barrier against COVID-19 disease.


<!--
## [PsychCore Genomics Pipeline](https://github.com/sanderslab/psychcore-compute-platform)


<img src="{{ site.url }}{{ site.baseurl }}/images/codepic/WGS_Pipeline_Image.png" style="width: 300px"> 

This containerized pipeline was developed for high-throughput parallel processing on the Amazon Web Services cloud platform. It was deployed to process whole-genome sequencing data from FASTQ to VCF for analysis of the human prefrontal cortex across development.

- <a href="https://github.com/sanderslab/psychcore-compute-platform"><i class='fab fa-github'></i> Source</a>
- <a href="https://www.biorxiv.org/content/10.1101/585430v1"><i class='fa fa-book'></i> Paper</a>

---

## [MagellanMapper](https://github.com/sanderslab/magellanmapper)


<img src="{{ site.url }}{{ site.baseurl }}/images/codepic/magellanmapper.png" style="width: 300px"> 

MagellanMapper is a graphical imaging informatics suite and pipeline for 3D reconstruction and automated analysis of and whole specimens and atlases. Its design philosophy is to make the raw 3D images as accessible as possible, simplify annotation from nuclei to atlases, and scale from the laptop or desktop to the cloud in cross-platform environments.

- <a href="https://github.com/sanderslab/magellanmapper"><i class='fab fa-github'></i> Source</a>
- <a href="https://elifesciences.org/articles/61408"><i class='fa fa-book'></i> Paper</a>
- <a href="https://currentprotocols.onlinelibrary.wiley.com/doi/abs/10.1002/cpns.104"><i class='fa fa-book'></i> Protocol</a>

---

## [wgsPowerTest](https://github.com/stephansanders/wgsPowerTest)


<img src="{{ site.url }}{{ site.baseurl }}/images/codepic/wgspower.png" style="width: 300px"> 

This R package runs power calculations for the discovery of variants in whole genome sequencing data.

- <a href="https://github.com/stephansanders/wgsPowerTest"><i class='fab fa-github'></i> Source</a>
- <a href="https://www.ncbi.nlm.nih.gov/pubmed/29184211"><i class='fa fa-book'></i> Paper</a>

---

## [SCN2A Variant Browser](https://public.tableau.com/profile/ucsf.psychiatry.bioinformatics.core#!/vizhome/SCN2AVariantViz6_0/Dashboard1)

<img src="{{ site.url }}{{ site.baseurl }}/images/codepic/scn2aviz.png" style="width: 300px"> 

The database SCN2A variants.

- <a href="https://public.tableau.com/profile/ucsf.psychiatry.bioinformatics.core#!/vizhome/SCN2AVariantViz6_0/Dashboard1"><i class='fa fa-link'></i> Link</a>
- <a href="https://www.ncbi.nlm.nih.gov/pubmed/28256214"><i class='fa fa-book'></i> Paper</a>

---


## [CNVision](https://sourceforge.net/projects/cnvision/)


<img src="{{ site.url }}{{ site.baseurl }}/images/codepic/cnvision.png" style="width: 300px"> 

CNVision is designed for detecting and scoring Copy Number Variants (CNVs) from Illumina SNP genotyping data. It runs in a UNIX environment and works with all Illumina chips (from 300k to latest Omni). CNVs are predicted using PennCNV, QuantiSNPv2.3, and GNOSIS (an in-built algorithm). The predicted CNVs are merged, joined (if appropriate), and scored based on the per SNP variability in the raw genotyping data. CNVision can also identify de novo CNVs in family-based data using the per SNP variability algorithm. Comparison with 1000 Genomes, the Genome Structural Variation Consortium, and replicate Illumina data demonstrates the efficacy of the CNV scoring method in both inherited and de novo CNVs.
​
CNVision was written to analyze data for the Simons Simplex Collection autism data. A full description of methods are given in the following paper which can be used to reference ([Sanders et al. (2015)](https://www.ncbi.nlm.nih.gov/pubmed/26402605))

- <a href="https://sourceforge.net/projects/cnvision/"><i class='fa fa-link'></i> Source</a>
- <a href="https://www.ncbi.nlm.nih.gov/pubmed/26402605"><i class='fa fa-book'></i> Paper</a>


---


## [Identity check](http://genomic-identity.wikidot.com/)
​
​Managing large genomic datasets requires accurate estimation of sample identity. This script rapidly identifies all BAM files and Illumina SNP genotyping FinalReports on a cluster, generates a SNP barcode from each one, and uses BLAT to identify duplicates and/or matches. It is run off aligned, indexed BAM files directly (hg18 or hg19) and FinalReports directly (hg18 or hg19). Cross platform (BAM to FinalReport) and cross genome build (hg18 to hg19) is handled automatically.

- <a href="http://genomic-identity.wikidot.com/"><i class='fa fa-link'></i> Source</a>
- <a href="http://genomic-identity.wikidot.com/usage"><i class='fa fa-book'></i> Manual</a>

---

## [UNIX treasure hunt tutorial]()
​
​<img src="{{ site.url }}{{ site.baseurl }}/images/codepic/th.png" style="width: 200px"> 
​

This perl script will install a series of directories and clues that teaches basic UNIX command line skills including `cd`, `ls`, `grep`, `less`, `head`, `tail`, and `nano`. Run the perl script from the command line on a UNIX based machine (e.g. Mac or Linux) using the command: `perl treasureHunt_v2.pl`. Then use `ls` to find the first clue. A PDF of command line commands is also available to download.

- <a href="https://www.dropbox.com/s/4pnobo1vk1sqvjb/treasureHunt_v2.pl?dl=0"><i class='fa fa-link'></i> Source</a>
- <a href="https://www.dropbox.com/s/xw5c1ra4td9k966/Unix_basics.pdf?dl=0"><i class='fa fa-book'></i> Manual</a>

---
-->

