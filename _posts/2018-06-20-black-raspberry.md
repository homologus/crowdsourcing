---
title: Black Raspberry Genome Paper
date: 2018-06-20
description: 
categories:
  - RNAseq
  - Rubus
image: /images/photos/photo3.jpg
author_staff_member: Nithish
---

## Overview

This paper outlines the experiment of sequencing the genome and the RNA of a black raspberry. When considering the steps our own experiment will take, it is important to examine past related experiments and take into account their processes and decisions.

<!--more-->

This paper, by VanBuren et. al, covers the RNA sequencing of a kin of salmonberry, the black raspberry. Black raspberry, or Rubus occidentalis, shares the same genus as salmonberry, or Rubus spectabilis. There haven’t been many papers published on sequencing of species of the Rubus genus, especially not their RNA, and so this is an important paper to examine for our potential experiment.

## Procedure

In this experiment, the RNA of the black raspberry was extracted from several parts of its plant: leaves, stems, canes, green fruit, red fruit and ripe fruit. The RNA was also extracted from both healthy roots and those treated with disease (specifically, the fungus Verticillium dahliae), in order to study black raspberry’s immune response and potential for human health. 

The extraction of the black raspberry’s RNA consisted of the following steps: 
First, the part of the black raspberry was frozen in liquid nitrogen. It was then taken out and grounded by a mixer mill (Mixer Mill MM 301) and suspended in a RNA reagent solution (PureLink Plant RNA Reagent) to extract the RNA. The RNA was then precipitated from the solution using 2-propanol. The extracted RNA was suspended in another RNA reagent solution (RNAsecure reagent) in order to extract it completely.

The extracted RNA was then sequenced using Illumina HiSeq2000, and analyzed using various libraries and models in order to understand its gene properties.

## Technology

After our team receives the sequencing of the RNA sample, it is critical to understand how to analyze the sequencing readings once they return. VanBuren and his team utilized a variety of libraries to assemble and annotate the readings, which may be helpful to examine.

Once the black raspberry RNA sequencing returned, the readings were trimmed down using Trimmomatic (V0.32). The genes were predicted using a program called MAST, or Motif Alignment and Scanning Tool (v.4.10.0). Trinity was then used to assemble the RNA readings into a complete RNA. 

In order to compare and analyze the assembled readings, the following programs were used:
A program called MAKER (v2.28) was used to compare the assembled readings to reference gene models. Annotating of the protein-encoding sequences – predicting the proteins encoded for by certain sequences of the assembled RNA – was done using the program InterProScan (5-RC6) and NCBI BLASTP. Our team has experience in using BLASTP, although using InterProScan along with it might provide for better accuracy. 

These models used by VanBuren and his team are just a sample of potential programs available to assemble, annotate and analyze RNA sequences. However, his team’s use of a spectrum of potential programs allows our team to examine their uses and potential benefits.

## Accuracy and Error Prevention

As noted in its procedure, VanBuren’s team took a few measures in order to ensure the accuracy of the black raspberry RNA sequencing and analysis. For example, before assembling the RNA sequences, each sequence’s individual RNA integrity was measured using the program Bioanalyzer. The team also took other steps in order to eliminate any potentially erroneous readings. 

The following discards were made by VanBuren and his team to ensure accuracy:
A sequence with a Bioanalyzer integrity number less than or equal to 6 was removed. For clusters of protein-encoding genes that were at least 95% similar, only the longest sequence was kept. Genes predicted to encode proteins with less than 33 amino acids were discarded. Only sequences with an error value from BLASTP less than or equal to 10-5 were kept. Protein sequences with MAKER AED of 1 and no functional annotation from InterProScan or BLASTP were removed. 

These steps were taken by VanBuren and his team in order to optimize their experimental results. If our team were to use any of the listed technologies or resources, it is worth considering following the same steps in order to prevent experimental errors.

## References

Lastly, just like our team, the black raspberry research team also followed the examples of past experiments, which it noted in its paper. The following papers could potential benefit our team when we consider which steps to follow, which other sequences are possible to compare the salmonberry reads to, or simply how a genome assembly research paper is organized.

Past genome reads used by VanBuren et al.:
Apple (Velasco et al, 2010), Peach (Verde et al, 2013), Pear (Wu et al, 2011; Chagne et al, 2014), Strawberry (Shulaev et al, 2011), Chinese plum (Zhang et al, 2012).

Protein sequences used by VanBuren et al. when annotating black raspberry readings:
Arabidopsis (Swarbreck et al, 2008), Brachypodium (Vogel, 2010), Rice (Project IRGS, 2005), Poplar (Tuskan, 2006), Sorghum (Paterson, 2009), Maize (Schnable, 2009).

## Conclusion

In conclusion, VanBuren et al. successfully sequenced a black raspberry RNA as well as its genome. 

It proved its close relationship to the woodland strawberry (Fragaria vesca) using the sequencing technologies noted above. It also managed to identify “290 very recent small-scale gene duplicates enriched for sugar metabolism, fruit development, and anthocyanin related genes” through comparing the history of black raspberries, as well as the locations from which the genes were extracted. Lastly, the team investigated black raspberry’s fruit development and disease response from sequencing the RNA from the corresponding parts of the plant.

Following the black raspberry research team’s example, our team might be able to also successfully sequence and analyze a salmonberry’s RNA. The technologies VanBuren’s team used, as well as the process by which and locations from which the RNA was extracted are worth considering for our own experiment. 


