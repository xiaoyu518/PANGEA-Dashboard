---
title: Phylogenetic Analysis of Pangea-II-HIV data
authors: "Xiaoyu Yu"
authorLinks: "https://www.pangea-hiv.org/"
affiliations: "PANGEA-II, University of Edinburgh"
date: "27 May 2021"
dataset: "http://localhost:4000/pol/20210512?d=map&c=cohort"
abstract: "This report shows the HIV genomic Data taken from different Sub-Saharan African Countries coloured by different Cohorts. Dataset contains a collaboration of PANGEA, Popart and Los Alamos HIV sequences. In depth phylogenetic analysis have been done on pol gag and env regions with interactive display on desktop browsers."
---

# [Executive Summary](http://localhost:4000/pol/20210512)

```auspiceMainDisplayMarkdown
## Executive summary

Using _PANGEA_, _PopART_ and Los Alamos Database (_LANL_), we extracted HIV whole genome sequences to examined genetic diversity to infer date of common ancestor and rate of spread utilising phylogenetic analytical tools.

* We have extracted 10995 pol sequences with high coverage and genome sequence length covering >90% of consensus alignment sequence generated based on all _PANGEA_, _Popart_ and _LANL_ samples used within the analysis.

* Time Span of samples range from 1983 to May 2019 with _LANL_ sequences (1983 - 2016) used as mainly background sequences for the phylogenetic analysis of the _PANGEA_ (2003 - 2019) and _PopART_ Project (2014 - 2018).

* 21 Countries are within the Analysis including: _Angola, Benin, Botswana, Congo, Central African Republic, Cote d'Ivoire, Cameroon, Ethiopia, Gabon, Ghana, Guinea Bissau, Kenya, Malawi, Nigeria, Rwanda, Senegal, Somalia, Tanzania, Uganda, South Africa, Zambia_.

* In total 17 Cohorts are split between 3 datasets with 5 _PopART_ Cohorts (_Central, Copperbelt, Southern, HCF, PC_), _LANL_ including all los alamos sequences and 11 _PANGEA_ cohorts (_MRC Uganda, MRC Tanzania, MRC Rwanda, Uganda Rakai, Partners Uganda, Partners Kenya, Partners South Africa, Partners Botswana, Partners Tanzania, Botswana, AHRI South Africa_).

* 12 Whole genome subtypes are found within the dataset (A, A1, A2, B, C, D, F1, F2, G, H, J, K) with low number but wide variety of recombinant subtypes.
```

# [PANGEA HIV Project](http://localhost:4000/pol/20210512)

### Further Reading:

* General information on PANGEA on [PANGEA](https://www.pangea-hiv.org/)
* Organization and Contacts on: 
    * [International Clinical Research Center (ICRC) Partners](http://depts.washington.edu/uwicrc/?q=content/about-icrc)
    * [African Health Research Institute (AHRI)](https://www.ahri.org)
    * [Botswana-Harvard AIDS Institute Partnership (BHP)](https://bhp.org.bw/)
    * [The MRC/UVRI and LSHTM Uganda Research Unit](https://www.mrcuganda.org/)
    * [The Rakai Health Sciences Program](https://www.rhsp.org)
    * [HIV Prevention Trials Network (HPTN) PopART](https://www.hptn.org/research/studies/hptn071)
    * [Los Alamos HIV database](https://www.hiv.lanl.gov/content/index)

```auspiceMainDisplayMarkdown

## PANGEA
PANGEA stands for "Phylogenetics And Networks for Generalised Epidemics in Africa". The overarching goal of the PANGEA consortium is to identify individual and population level factors that drive the epidemic using HIV-1 phylogenetic data, analyse the dynamics of the epidemic, and translate these findings into information that can be used to more effectively target interventions. PANGEA consists of many partners in Africa, Europe and the US. PANGEA has been funded in two phases by the Bill & Melinda Gates Foundation.

<br>

## HIV
HIV stands for human immunodeficiency virus. HIV is a retrovirus that infects cells of the human immune system (mainly CD4-positive T-cells and macrophages—key components of the cellular immune system) and destroys or impairs their function. Infection with this virus results in the progressive depletion of the immune system, leading to immunodeficiency.

The immune system is considered deficient when it can no longer fulfil its role of fighting off infection and diseases. People with immunodeficiency are much more vulnerable to a wide range of infections and cancers, most of which are rare among people without immunodeficiency. Diseases associated with severe immunodeficiency are known as opportunistic infections because they take advantage of a weakened immune system.

Source: [UNAIDS](https://www.unaids.org/en/frequently-asked-questions-about-hiv-and-aids)

<br>

## PANGEA Related Publications
* [Universal amplification, next-generation sequencing, and assembly of HIV-1 genomes](https://jcm.asm.org/content/50/12/3838)
* [PANGEA-HIV: phylogenetics for generalised epidemics in Africa](https://www.sciencedirect.com/science/article/pii/S1473309915700368?via%3Dihub)
* [Using nearly full-genome HIV sequence data improves phylogeny reconstruction in a simulated epidemic](https://www.nature.com/articles/srep39489)
* [Phylogenetic Tools for Generalized HIV-1 Epidemics: Findings from the PANGEA-HIV Methods Comparison](https://academic.oup.com/mbe/article/34/1/185/2670195)
* [HIV-1 full-genome phylogenetics of generalized epidemics in sub-Saharan Africa: impact of missing nucleotide characters in next-generation sequences](https://www.liebertpub.com/doi/10.1089/aid.2017.0061)
* [PHYLOSCANNER: Inferring Transmission from Within- and Between-Host Pathogen Genetic Diversity](https://academic.oup.com/mbe/article/35/3/719/4653772)
* [Easy and accurate reconstruction of whole HIV genomes from short-read sequence data with shiver](https://academic.oup.com/ve/article/4/1/vey007/4999822)
* [Ethical considerations in global HIV phylogenetic research](https://www.clinicalkey.com/#!/content/playContent/1-s2.0-S2352301818301346?returnurl=https:%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS2352301818301346%3Fshowall%3Dtrue&referrer=)
* [A comprehensive genomics solution for HIV surveillance and clinical monitoring in a global health setting](https://jcm.asm.org/content/58/10/e00382-20)
* [Phylogeography of HIV-1 suggests that Ugandan fishing communities are a sink for, not a source of, virus from general populations](https://www.nature.com/articles/s41598-018-37458-x)
* [Inferring HIV-1 transmission networks and sources of epidemic spread in Africa with deep-sequence phylogenetic analysis](https://www.nature.com/articles/s41467-019-09139-4)
* [PANGEA-HIV 2: Phylogenetics And Networks for Generalised Epidemics in Africa](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6629166/)
* [Quantifying HIV transmission flow between high-prevalence hotspots and surrounding communities: a population-based study in Rakai, Uganda](https://www.clinicalkey.com/#!/content/playContent/1-s2.0-S2352301819303789?returnurl=https:%2F%2Flinkinghub.elsevier.com%2Fretrieve%2Fpii%2FS2352301819303789%3Fshowall%3Dtrue&referrer=)
```

# [Phylogenetic Analysis](http://localhost:4000/pol/20210512)

### Further Reading:

* [Auspice: An Open-source Interactive Tool for Visualising Phylogenomic Data](https://docs.nextstrain.org/projects/auspice/en/stable/)
* [Augur: A bioinformatics toolkit for phylogenetic analysis](https://docs.nextstrain.org/projects/augur/en/stable/index.html)
* [Reading a Phylogenetic Tree: The Meaning of Monophyletic Groups](https://www.nature.com/scitable/topicpage/reading-a-phylogenetic-tree-the-meaning-of-41956/)

```auspiceMainDisplayMarkdown
## Interpreting Phylogenetic Trees

#### Transmission trees vs phylogenetic trees

Pathogens spread through rapid replication in one host followed by transmission to another host.
An epidemic can only take off when one infection results in more than one subsequent infections.

As the pathogen replicates and spreads, its genome needs to be replicated many times and random mutations (copying mistakes)  will accumulate in the genome.
Such random mutations can help to track the spread of the pathogen and learn about its transmission routes and dynamics.

<div>
  <img alt="cartoon showing how transmission tree and phylogenetic tree relate" width="500" src="https://neherlab.org/talk_images/infection_tree_combined.png"/>
</div>

The illustration above shows a sketch of a transmission tree with a subset of cases that were sampled (blue).
In practice, the transmission tree is unknown and typically only rough estimates of case counts are available.
Genome sequences allow us to infer parts of the transmission tree.
In this example, three mutations (little diamonds) are indicated on the tree.
Sequences that have the same mutations are more closely related, so these mutations allow us to group samples into clusters of closely related viruses that belong to the same transmission chains.

#### Reading a Phylogenetic Tree

Below, we see an illustration with a phylogenetic tree on the left, where mutations are shown as colored circles. On the right are the corresponding sequences, also with mutations shown as colored circles.
We can see that sequences that share the same mutations group together.
When sequences appear linked by a flat vertical line, like A and B, this means there are no differences between them – their sequences are identical.

When a sequence sits on a long line on its own, like C or E, this means it has unique mutations not found in other sequences. The longer the line, the more mutations.
A and B also have unique mutations (the green circle) not shared by the other sequences, but they are identical to each other.

<div>
  <img alt="cartoon of phylogenetic tree and corresponding alignment, with samples labelled A-E" width="500" src="http://data.nextstrain.org/toy_alignment_tree.png"/>
</div>

Source: [Genomic analysis of nCoV spread. Situation report 2020-01-23](https://nextstrain.org/narratives/ncov/sit-rep/2020-01-23?n=4)

```

# [Phylogenetic analysis](http://localhost:4000/pol/20210512?d=tree)

Here we present a phylogeny of 10995 samples of HIV from the PANGEA/PopART/LANL dataset.
Information on how the analysis was performed is as follows:

<br>

#### Alignment
* Extracting raw sequences and metadata with non empty metadata fields and sequence length > 70%
* Match to the closest reference according to 268 pre-selected sequences representing majority of African HIV-1 subtypes
* Using the closest reference to annotate the raw sequences
* Retrieving gene regions gag env and pol
* Filter out sequence with low coverage of > 10% gaps and Ns
* Local alignment to consensus sequence built based on the whole dataset of individual regions of gag pol and env. Trimming of regions not existing in the consensus sequence.

#### Phylogenetic Tree
* Maximum Likelihood phylogenetic tree built using [iqtree](http://www.iqtree.org/) with GTR free rate Substitution Model
* Time Tree refinement done using [Treetime](https://treetime.readthedocs.io/en/latest/) with fixed clock rate estimated using 268 reference sequences.
* Ancestral reconstruction done using [augur ancestral](https://treetime.readthedocs.io/en/latest/tutorials/ancestral.html) for representation at each node the differences in nucleotide between tips under that node.
* Discrete trait (_country, cohort_) analysis done using [augur traits](https://treetime.readthedocs.io/en/latest/tutorials/mugration.html) for estimation of transition between nodes and tips.
* Final phylogenetic tree exported to Auspice visualisation as displayed on the right with colours representing different countries within the analysis and the x-axis representing the date of which the sequences were sampled

# [Phylogenetic Map of Countries within the study](http://localhost:4000/pol/20210512?d=map)

Geographical map representing the countries sampled within the dataset. The size of the circle represent the sample size taken from the specific country.

# [Phylogenetic Tree Coloured by Cohorts](http://localhost:4000/pol/20210512?d=tree&c=cohort)

Pangea include five studies from different collaborators:
* MRC cohort in _Uganda, Tanzania and Rwanda_
* Partners cohort in _South Africa, Botswana, Tanzania, Kenya and Uganda_
* AHRI cohort in _South Africa_
* _Botswana_ cohort
* Rakai cohort in _Uganda_

Popart study include 5 major cohorts:
* _Central_
* _Copperbelt_
* _Southern_
* _PC_ 
* _HCF_

Los Alamos (_LANL_) sequences are taken as background sequences from across sub-saharan Africa.

# [Map View by Cohort](http://localhost:4000/pol/20210512?d=map&c=cohort)

Sample size comparison per location based on the size of circle. Individual cohort based on same location shown in piechart on the African Continental Map.

# [Map and Tree View of Cohorts filtered by Country](http://localhost:4000/pol/20210512?c=cohort&f_country=Uganda&p=grid)

Phylogenetic tree filtered by Uganda with Cohort Specific View. Only Uganda Sequences are shown coloured by Cohort in the Phylogenetic Tree. Hovering over nodes shows the number of descendant tips and the nucleotide mutations shared by them. Hovering over the tips shows the defining nucleotide mutations of that sequences. Other information such as divergence rate (Divergence is measured as the number of changes per base, in this case its 1/2805 = 0.00035), sample date and cohort are displayed in the hover box. For more detailed annotation for each tip, use the "_explore the data yourself_" option and click on the tip of interest and a box displaying all tip annotation will be displayed.

Corresponding map is displayed on the right with zoomed in version for clearer display of piechart.

# [Filtering by Tips and Tip Annotations](http://localhost:4000/pol/20210512?d=tree&s=BFY01BP7-01)

Inidividual sequences can be filtered or searched in the Filter Data text box. Tips can be clicked upon for more information regarding the tip of interest.

# [Phylogenetic Tree Coloured by Whole Genome Subtype](http://localhost:4000/pol/20210512?d=tree&c=subtype)

Sequence subtypes are inferenced when whole genomes are sequenced and assembled to a reference sequence. Major Subtypes according to HIV nomenclature include  A, A1, A2, B, C, D, F1, F2, G, H, J, K with all recombinants named other for clearer coloured representation within the phylogenetic tree. Detailed recombinant subtypes can be viewed using the filtering tab under "_whole genome subtype other_" for more information regarding their recombinant subtypes. This can be done by clicking on the top right corner "_explore the data yourself_".

# [Phylogenetic Tree Colour by Pol Subtype](http://localhost:4000/pol/20210512?d=tree&c=pol_major_subtype)

For a accurate representation of the subtype within the phylogenetic tree, due to the tree under representation being built based on the pol regions only, the pol subtype is represented here instead of the whole genome subtype. Subtypes were inferenced using the [RIP](https://www.hiv.lanl.gov/content/sequence/RIP/RIP.html) tool on the Los Alamos Website. The phylogenetic tree displays the spread of different subtypes in defined clusters with few odd potential recombinants displaying different colours (e.g. Large cluster of C in purple with a strip of A1 in dark blue within the middle). 

# [Phylogenetic Tree Colour by Pol Minor Subtype](http://localhost:4000/pol/20210512?d=tree&c=pol_minor_subtype)

Pol sequences with potential recombination are coloured by pol minor subtype whereby sequences with more than one subtype is displayed here.Sequences with a pure single subtype are greyed out. Using the above example of three A1 major subtype from the previous phylogenetic tree display being clustered within C, here the minor subtype is C and hence a potential A1C recombinant and therefore the reason for potential placement within the C cluster.

# [Map View by Pol Subtypes](http://localhost:4000/pol/20210512?d=map&c=pol_major_subtype)

Here is a map view of all pol major subtypes per country. Sample size comparison per location based on the size of circle. Individual subtypes based on same location shown in piechart on the African Continental Map.

# [Phylogenetic Tree at Slice of Time](http://localhost:4000/pol/20210512?d=tree&c=cohort&dmax=2014-12-30&dmin=2012-01-01&p=full)

We can also filter the sequences based on a slice of time of different traits. Here we took a slice of time between 2012 and 2014 and all samples from individual cohorts between this time are displayed within the Phylogenetic Tree. By exploring the tree yourself using "_explore the data yourself_" option, you can also identify the number of filtered sequences as well as download the selected filtered metadata.

# [Exploring clock signal](http://localhost:4000/pol/20210512?d=tree&l=clock&p=full)

Different tree layouts are possible and this one shows the temporal divergence (y-axis) vs. inferred substitutions (x-axis) to see the presence of a constant clock signal. This clock signal can be represented by a logistic regression line shown in black with the rate estimate being the slope of this line display at the top of the graph. This constant clock rate can represent the number of substitutions a sequence can undergo per site per year.

# [Phylogenetic Tree in Radial Layout](http://localhost:4000/pol/20210512?d=tree&c=pol_major_subtype&l=radial)

Another phylogenetic tree layout, the Radial format. Different tree formats can be changed in Auspice and can be used and extracted for external presentation.

