# PANGEA_Pipeline v0.1

For phylodynamic analysis of pangea data from PANGEA database.

Contains Three pipelines including: 

Alignment:
    Extracting raw sequences and metadata with non empty metadata fields and sequence length above percentage threshold (Default: 70%)
    Match to the closest reference according to 268 pre-selected sequences representing majority of African HIV-1 sequences from Los Alamos Database
    Using the closest reference to annotate the raw sequences
    Retrieving gene regions gag env and pol
    Filter out sequence with low coverage (Default < 70% Sequence with Missing Bases)
    Trim regions based on edit file (Variable regions for ENV)
    Break down into smaller datasets for alignment against consensus (mafft)
    Concatenating into one large dataset
 
Augur Pipeline (Phylogenetics):
    ML using iqtree, GTR+G Substitution Model
    Treetime for timetree inferences
    Auspice visualization

Beast Pipeline (Beast Analysis):
    Calculation of pairwise distance matrix
    Cluster align using clustering algorithm
    Creating beast XML file using beastgen 
    Beast run using GPU threading
    Beast tree import to auspice visuals
