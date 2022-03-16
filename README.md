miARma WebPage
This is a new repository created in Oct 2021 to store the source code and the guides from miARma-seq. The guides will be available soon in the wiki.

This repository contains the source code published in:

Andrés-León E, Rojas AM. miARma-Seq, a comprehensive pipeline for the simultaneous study and integration of miRNA and mRNA expression data. Methods. 2019 Jan 1;152:31-40. doi: 10.1016/j.ymeth.2018.09.002. Epub 2018 Sep 22. PMID: 30253202.
Andrés-León E, Núñez-Torres R, Rojas AM. miARma-Seq: a comprehensive tool for miRNA, mRNA and circRNA analysis. Sci Rep. 2016 May 11;6:25749. doi: 10.1038/srep25749. Erratum in: Sci Rep. 2018 Jan 08;8:46928. PMID: 27167008; PMCID: PMC4863143.
miARma
miARma is a fully customizable pipeline for NGS transcriptome analyses. Including gene/transcripts, miRNAs and circRNAs expression measurements. Created at Computational Biology and Bioinformatics Group (CbBio) Institute of Biomedicine of Seville. IBIS (Spain) Modified and Updated at Bioinformatics Unit at IPBLN-CSIC (Institue for Parasitology and Biomedicine Lopez-Neyra, CSIC). Granada (Spain). Copyright (c) 2019 IBIS & IPBLN. All rights reserved.

miARma 1.7.6 release (07/Oct/19)
The latest Bioconductor versions that use R3.5 and R.6 install the packages differently than the other versions. So miARma has been modified to take this into account.

miARma 1.7.5 release (22/Sep/18)
New utilities have been included and publisehd in a new scientific article. An example to integrate miRNA and mRNA data to infer potential regulation partners is included in a GitHub repository.

The possibility of integrating data from miRNAs and mRNAs
A statistical correlation (Pearson/Spearman) can be calculated to infer linked miRNA/mRNA expression profiles
miRNA/mRNA target prediction based on statstical correlated pairs
miARma 1.7.2 release (18/Dec/17)
Minor bugs fixed.

New Ensembl BiomaRt URL used
Order columns from ReadCount section without checking samples names
Fixed a bug in the TargetPrediction
miARma 1.7.1 release (21/Aug/17)
Minor bugs fixed eg.

No aligned reads in hisat2 paired end analysis added.
Added stuff:

Unaligned files are compressed
miRDeeparam added to include parameters to miRDeep execution
miARma 1.7.0 release (09/Aug/17)
Hisat v2.1.0 has been included as a mRNA aligner.
STAR v020201 has been included as a mRNA aligner.
1. Included in miARma
Quality Software
Fastqc v0.11.5
Trimming Softare
CutAdapt v1.9.1
Minion v15-065
Reaper v15-065
Aligners
Bowtie v1.1.2
Bowtie v2.2.8
TopHat v2.1.1
BWA v0.7.13
Hisat v2.1.0
STAR v020201
Entity Quantification####
feactureCounts v1.5.0-p1
Ciri v1.2
Ciri v2.0.1
miRDeep v2
Others
RNAfold v2.2.4
Samtools v1.3
2. Pre-requisites
miARma-Seq is a tool that provides an easy and common interface to various analysis software. It also intends to reduce to the minimum the number of dependencies. Nevertheless, some basic programs listed below must be correctly installed:

Perl v5.6.0 or higher.
Java JDK v.1.6. or higher.
R environment v.3.2 or higher.
Bioconductor v.1.3 or higher.
Compilers:
Apple:
Xcode
Linux:
Gcc
�make
How do I get set up?
[miARma can be installed using the following guide]
Guidelines/How to
[miRNAs guide]
[mRNAs guide]
[circRNAs guide]
Code Documentation
[Perldoc]
Who do I talk to?
eduardo.andres at csic.es
