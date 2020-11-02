# PANGEA Pipeline v0.1

For phylodynamic analysis of pangea data from PANGEA project.

Alignment Pipeline:

    Extracting raw sequences and metadata with non empty metadata fields and sequence length above percentage threshold (Default: 70%)
    Match to the closest reference according to 268 pre-selected sequences representing majority of African HIV-1 sequences from Los Alamos Database
    Using the closest reference to annotate the raw sequences
    Retrieving gene regions gag env and pol with span (Span = Number of Known Bases, Default: 1000), coverage (Span/Length of Region, Default: 0.9) and max stop codon options (Default: 4)
    Break down into smaller datasets for alignment against consensus (All insertions are removed based on consensus, Consensus built upon alignment of all sequences currently used in PANGEA alignment (11309 sequences). Variable loop is removed for ENV region within consensus)
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
