# BioInformaticsProject
BioInformatics Project - analyzing clusters in Plasmids and Chromosomes of Bacteria.
The Goal : finding discriminative (non-collinear) gene clusters.
Gene Cluster Discovery and Comparative Analysis
Project Summary
This project aims to design and implement an efficient algorithm to discover conserved gene clusters in bacterial genomes, focusing on both plasmid and chromosomal datasets. The project is divided into two main parts: gene cluster discovery and comparative analysis of gene clusters between different genome sets.

Goals
Gene Cluster Discovery:

Develop an efficient algorithm to identify gene clusters in bacterial genomes.
Analyze the conservation of gene clusters across multiple genomes.
Sort gene clusters by their abundance.
Provide detailed characterization profiles for each discovered gene cluster.
Comparative Analysis:

Clean and prepare genome data to include only genomes with plasmids.
Propose and implement a novel approach to compare gene cluster profiles.
Identify gene clusters with significantly different profiles between plasmid and chromosomal datasets.
Data
The project utilizes the following datasets:

COG-spelled genomes: Each genome is segmented into segments containing one or more operons.
Taxa information: Includes phylum and environmental descriptions of bacterial hosts.
COG info table: Provides detailed information about each COG.
Implementation Steps
Part One: Gene Cluster Discovery
Algorithm Design:

Design an efficient algorithm to find gene clusters of length d that are conserved in at least q genomes.
Sort the discovered gene clusters by their abundance.
Program Implementation:

Implement the algorithm in Python using a Jupyter notebook.
Document the code thoroughly within the notebook.
Provide a high-level description of the algorithm in the report.
Characterization Profile:

Develop a subroutine to compute and print a descriptive profile for each gene cluster.
Include the rank, pattern information, gene orders, and distribution statistics in the profile.
Run the Program:

Extract gene clusters of cardinality ranging from d=2 to d=4 using q=5.
Report the four most abundant gene clusters for each cardinality value, including their descriptive profiles.
Documentation:

Submit the documented code, output files, and a detailed report explaining the algorithm's efficiency and correctness.
Part Two: Comparative Analysis
Data Preparation:

Clean the bacterial genomes file to include only genomes with at least one plasmid.
Comparative Profile Analysis:

Propose a novel approach to compare gene cluster profiles and produce a distinctiveness score.
Implement the comparative analysis approach within a program or pipeline.
Implementation of Comparative Analysis:

Develop a program to find gene clusters that differ significantly in their profiles between two genome sets (plasmid vs. chromosomal).
Document the code and provide a high-level description of the method in the report.
Experimentation and Results:

Run benchmarks with different values of d, q1, and q2.
Identify and report a gene cluster that distinguishes plasmid genomes from chromosomal genomes.
Justify the parameter selection and hypothesize a biological explanation for the findings based on existing literature.
