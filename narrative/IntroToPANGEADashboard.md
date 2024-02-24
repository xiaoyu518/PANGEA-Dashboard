---
title: Phylogenetic Analysis of Pangea 2 HIV data
authors: "Xiaoyu Yu"
authorLinks: "xiaoyu.yu@ed.ac.uk"
affiliations: "PANGEA 2, University of Edinburgh"
date: "27 November 2023"
dataset: "http://localhost:4000/pol/20210524?d=map&c=partner"
abstract: "This report shows the HIV genomic Data taken from different Sub-Saharan African countries coloured by 7 different collaborate partners. The dataset contains a collaboration of PANGEA and Los Alamos HIV sequences. In depth phylodynamic analyses have been done on pol, gag and env regions with interactive display on desktop browsers."
---

# [Executive Summary](http://localhost:4000/pol/20210524)

```auspiceMainDisplayMarkdown
## Executive summary

<p>&nbsp;</p>

Using _PANGEA_ and Los Alamos Database (_LANL_), we extracted HIV whole genome sequences to examined genetic diversity to infer date of common ancestor and rate of spread utilising phylogenetic analytical tools.

* We have extracted 15912 pol, gag and env sequences with high coverage and genome sequence length covering >90% of consensus alignment sequence based on all _PANGEA_ and _LANL_ samples used within the analysis.
* Time span of samples range from 1983 to May 2021 with _LANL_ sequences (1983 - 2016) used as mainly background sequences for the phylogenetic analysis of the _PANGEA_ (2004 - 2021).
* The vast majority of PANGEA sequences are from _Botswana, Kenya, South Africa, Uganda, Tanzania and Zambia_. Additional sequences from LANL are from _Angola, Benin, Cameroon, Central African Republic, Cote d'Ivoire, Democratic Republic of the Congo, Ethiopia, Gabon, Gambia, Ghana, Guinea Bissau, Malawi, Nigeria, Rwanda, Senegal and Somalia_.
* 12 whole genome subtypes are found within the dataset (A, A1, A2, B, C, D, F1, F2, G, H, J, K) with low number but wide variety of recombinant subtypes.

Follow up phylodynamic analysis was done using BEAST discrete trait and skygrid coalescent estimations on effective population for each individual partner and trait transitions between partners.

* Comparison of gag, pol and env skygrid estimations alongside sampling date and incidence rate for the outlining country containing the partner. 
* Source and Sink ratio estimations for each individual partner from the date 1989 onwards.
* Transmission event count for each individual partner from the date 1989 onwards.
* Transition event count between Uganda partner and outside Uganda as case study.
* Import intensity plot for Uganda and outside Uganda partner as case study.

```

# [PANGEA HIV Project](http://localhost:4000/pol/20210524)

### Further Reading:

* General information on PANGEA on [PANGEA](https://www.pangea-hiv.org/)
* Organization and Contacts on: 
    * [International Clinical Research Center (ICRC) Partners](http://depts.washington.edu/uwicrc/?q=content/about-icrc)
    * [African Health Research Institute (AHRI)](https://www.ahri.org)
    * [Botswana-Harvard AIDS Institute Partnership (BHP)](https://bhp.org.bw/)
    * [The MRC/UVRI and LSHTM Uganda Research Unit](https://www.mrcuganda.org/)
    * [The Rakai Health Sciences Program](https://www.rhsp.org)
    * [HIV Prevention Trials Network (HPTN) PopART Phylogenetics](https://www.hptn.org/research/studies/hptn071)
    * [Los Alamos HIV database](https://www.hiv.lanl.gov/content/index)
* Bayesian Evolutionary Analysis Sampling Trees: [BEAST](https://beast.community/)
    * [Skygrid Coalescent](https://academic.oup.com/mbe/article/30/3/713/1041171)
    * [BSSVS discrete Traits](https://journals.plos.org/ploscompbiol/article?id=10.1371/journal.pcbi.1000520)
* Quick Vocabulary:
    * [Coalescent Theory](https://www.sciencedirect.com/science/article/pii/0304414982900114?via%3Dihub)
    * [Sources and Sinks](https://www.pangea-hiv.org/research)
    * [Effective population size](https://www.nature.com/articles/nrg2526)

```auspiceMainDisplayMarkdown

#### PANGEA
PANGEA stands for "Phylogenetics And Networks for Generalised Epidemics in Africa". The overarching goal of the PANGEA consortium is to identify individual and population level factors that drive the epidemic using HIV-1 phylogenetic data, analyse the dynamics of the epidemic, and translate these findings into information that can be used to more effectively target interventions. Currently PANGEA has senquenced more than 33000 sequences with many partners in Africa, Europe and the US. PANGEA has been funded in two phases by the Bill & Melinda Gates Foundation.

<p>&nbsp;</p>

#### HIV
HIV stands for human immunodeficiency virus. HIV is a retrovirus that infects cells of the human immune system (mainly CD4-positive T-cells and macrophages—key components of the cellular immune system) and destroys or impairs their function. Infection with this virus results in the progressive depletion of the immune system, leading to immunodeficiency.

The immune system is considered deficient when it can no longer fulfil its role of fighting off infection and diseases. People with immunodeficiency are much more vulnerable to a wide range of infections and cancers, most of which are rare among people without immunodeficiency. Diseases associated with severe immunodeficiency are known as opportunistic infections because they take advantage of a weakened immune system.

Source: [UNAIDS](https://www.unaids.org/en/frequently-asked-questions-about-hiv-and-aids)

<p>&nbsp;</p>

#### Genomes
The genetic sequence encoding everything the virus/organism needs to function and reproduce, stored as a DNA or RNA molecule. A whole genome sequence involves uncovering the order of bases in a complete genome of an organism while a partial genome is a section of the whole genome of interest normally a protein sequence(s). In our case, the pol, gag and env gene sequence are used as these are often used for phylogenetic studies and subtyping as these core genes representing important regions such as encoding the structural proteins involved in viral particle formation (gag); encoding the envelope protein (env); encoding the enzymes for replication (protease, RT, RNase H, integrase) (pol). 

<p>&nbsp;</p>

#### Quick Vocabulary

* **Skygrid**: Bayesian nonparametric model that estimates the effective population size over time, directly from a sample of multilocus molecular sequence data. 
* **Source**: Partner in a population that disproportionately pass on infections 
* **Sink**: Partner in a population that disproportionately receives infections
* **Import**: Infection transimitted by an individual from one partner from another partner
* **Export**: Infection passed by an individual from one partner onto another partner
* **Effective Population**: The effective size of a population, Ne, determines the rate of change in the composition of a population caused by genetic drift, which is the random sampling of genetic variants in a finite population. It translates census sizes of a real population into the size of an idealized population showing the same rate of loss of genetic diversity as the real population under study

<p>&nbsp;</p>

### PANGEA Related Publications
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

# [Phylogenetic Analysis](http://localhost:4000/pol/20210524)

### Further Reading:

* [Auspice: An Open-source Interactive Tool for Visualising Phylogenomic Data](https://docs.nextstrain.org/projects/auspice/en/stable/)
* [Augur: A bioinformatics toolkit for phylogenetic analysis](https://docs.nextstrain.org/projects/augur/en/stable/index.html)
* [Reading a Phylogenetic Tree: The Meaning of Monophyletic Groups](https://www.nature.com/scitable/topicpage/reading-a-phylogenetic-tree-the-meaning-of-41956/)

```auspiceMainDisplayMarkdown
### Interpreting Phylogenetic Trees

<p>&nbsp;</p>

#### Transmission trees vs phylogenetic trees
Pathogens spread through rapid replication in one host followed by transmission to another host.
An epidemic can only take off when one infection results in more than one subsequent infection on average.

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

<p>&nbsp;</p>

#### Reading a Phylogenetic Tree

Below, we see an illustration with a phylogenetic tree on the left, where mutations are shown as colored circles. On the right are the corresponding sequences, also with mutations shown as colored circles.
We can see that sequences that share the same mutations group together. When sequences appear linked by a flat vertical line, like A and B, this means there are no differences between them – their sequences are identical.

When a sequence sits on a long line on its own, like C or E, this means it has unique mutations not found in other sequences.
A and B also have unique mutations (the green circle) not shared by the other sequences, but they are identical to each other.

<div>
  <img alt="cartoon of phylogenetic tree and corresponding alignment, with samples labelled A-E" width="500" src="http://data.nextstrain.org/toy_alignment_tree.png"/>
</div>

Source: [Genomic analysis of nCoV spread. Situation report 2020-01-23](https://nextstrain.org/narratives/ncov/sit-rep/2020-01-23?n=4)

```

# [Phylogenetic analysis](http://localhost:4000/pol/20210524?d=tree)

Here we present a phylogeny of 15833 pol samples of HIV from the PANGEA/LANL dataset.
The analysis was performed as follows:

<br>

#### Alignment
* Extracting raw sequences and metadata with non-empty metadata fields and sequence length > 70%
* Match to the closest reference according to 268 pre-selected sequences representing majority of African HIV-1 subtypes
* Using the closest reference to annotate the raw sequences
* Retrieving gene regions gag, env and pol
* Filter out sequence with low coverage of > 10% gaps and Ns
* Local alignment to consensus sequence built based on the whole dataset of individual regions of gag pol and env. Trimming of regions not existing in the consensus sequence.

#### Phylogenetic Tree
* Maximum Likelihood phylogenetic tree built using [iqtree](http://www.iqtree.org/) with GTR free rate Substitution Model
* Time Tree refinement done using [Treetime](https://treetime.readthedocs.io/en/latest/) with fixed clock rate estimated using 268 reference sequences. Outlier sequences which do not fit this fixed estimated clock rate are removed from the tree.
* Ancestral reconstruction done using [augur ancestral](https://treetime.readthedocs.io/en/latest/tutorials/ancestral.html) for representation at each node the differences in nucleotide between tips under that node.
* Discrete trait (_country, partner_) analysis done using [augur traits](https://treetime.readthedocs.io/en/latest/tutorials/mugration.html) for estimation of transition between nodes and tips.
* Final phylogenetic tree exported to Auspice visualisation as displayed on the right with colours representing different countries within the analysis and the x-axis representing the date of which the sequences were sampled

#### Other genome regions
* [gag phylogenetic tree](http://pangea2-hiv.org/gag/20210525)
* [env phylogenetic tree](http://pangea2-hiv.org/env/20210525)

# [Phylogenetic Tree Coloured by partners](http://localhost:4000/pol/20210524?d=tree&c=partner)

To date, PANGEA includes sequences from six different collaborators:

* Rakai partner in Uganda
* MRC partner in Uganda
* Partner partners in Kenya, Uganda, Tanzania, Botswana and South Africa
* AHRI partner in South Africa
* BCCP partner in Botswana
* PopART partner in Zambia

LANL sequences from across sub-Saharan Africa are used as background sequences.


# [Phylogenetic Map of countries within the study](http://localhost:4000/pol/20210524?d=map)

Geographical map representing the countries sampled within the dataset. Circle sizes are representative of the number of sequences from a given country.


# [Map View by partner](http://localhost:4000/pol/20210524?d=map&c=partner)

Circles sizes are representative of the number of sequences from a given partner. Partners based in the same country are shown as part of a country-specific pie chart.

# [Map and Tree View of partners filtered by country](http://localhost:4000/pol/20210524?c=partner&f_country=Uganda&p=grid)

Only Uganda sequences are shown coloured by partner in the Phylogenetic Tree. Hovering over nodes shows the number of descendant tips and the nucleotide mutations shared by them. Hovering over the tips shows the defining nucleotide mutations of that sequences. Other information such as divergence rate (Divergence is measured as the number of changes per base, in this case its 1/2805 = 0.00035), sample date and partner are displayed in the hover box. For more detailed annotation for each tip, use the "_explore the data yourself_" option and click on the tip of interest, and a box displaying all tip annotation will be displayed.

Corresponding map is displayed on the right with zoomed-in version for clearer display of the piechart.

# [Filtering by Tips and Tip Annotations](http://localhost:4000/pol/20210524?d=tree&s=Botswana-98)

Inidividual sequences can be filtered or searched in the Filter Data text box. Tips can be clicked upon for more information regarding the tip of interest.

# [Phylogenetic Tree Coloured by whole Genome Subtype](http://localhost:4000/pol/20210524?d=tree&c=subtype)

Sequence subtypes are inferenced when whole genomes are sequenced and assembled to a reference sequence. Major Subtypes according to [HIV nomenclature](https://www.researchgate.net/publication/215733471_HIV-1_Nomenclature_Proposal) include  A, A1, A2, B, C, D, F1, F2, G, H, J, K with all recombinants named other for clearer coloured representation within the phylogenetic tree. Detailed recombinant subtypes can be viewed using the filtering tab under "_whole genome subtype other_" for more information regarding their recombinant subtypes. This can be done by clicking on the top right corner "_explore the data yourself_".

# [Phylogenetic Tree Colour by Pol Subtype](http://localhost:4000/pol/20210524?d=tree&c=pol_major_subtype)

For a accurate representation of the subtype within the phylogenetic tree, due to the tree under representation being built based on the pol regions only, the pol subtype is represented here instead of the whole genome subtype. Subtypes were inferenced using the [RIP](https://www.hiv.lanl.gov/content/sequence/RIP/RIP.html) tool on the Los Alamos Website. The phylogenetic tree displays the spread of different subtypes in defined clusters with few odd potential recombinants displaying different colours (e.g. Large cluster of C in purple with a strip of A1 in dark blue within the middle). 

# [Phylogenetic Tree Colour by Pol Minor Subtype](http://localhost:4000/pol/20210524?d=tree&c=pol_minor_subtype)

Pol sequences with potential recombination are coloured by pol minor subtype whereby sequences with more than one subtype is displayed here.Sequences with a pure single subtype are greyed out. Using the above example of three A1 major subtype from the previous phylogenetic tree display being clustered within C, here the minor subtype is C and hence a potential A1C recombinant and therefore the reason for potential placement within the C cluster.

# [Map View by Pol Subtypes](http://localhost:4000/pol/20210524?d=map&c=pol_major_subtype)

Here is a map view of all pol major subtypes per country. Sample size comparison per location based on the size of circle. Individual subtypes based on same location shown in piechart on the African Continental Map.

# [Phylogenetic Tree at Slice of Time](http://localhost:4000/pol/20210524?d=tree&c=partner&dmax=2014-12-30&dmin=2012-01-01&p=full)

We can also filter the sequences based on a slice of time of different traits. Here we took a slice of time between 2012 and 2014 and all samples from individual partners between this time are displayed within the Phylogenetic Tree. By exploring the tree yourself using "_explore the data yourself_" option, you can also identify the number of filtered sequences as well as know the origin/subtype of the sequences during in this time period.

# [Exploring clock signal](http://localhost:4000/pol/20210524?d=tree&l=clock&p=full)

Different tree layouts are possible and this one shows the temporal divergence (y-axis) vs. inferred substitutions (x-axis) to see the presence of a constant clock signal. A molecular clock is defined as an estimated constant rate of molecular evolution among species. In this case, it would be the number site substitutions in the pol genome per year. This clock signal can be represented by a logistic regression line shown in black with the rate estimate being the slope of this line display at the top of the graph. This constant clock rate can represent the number of substitutions a sequence can undergo per site per year.

# [Phylogenetic Tree in Radial Layout](http://localhost:4000/pol/20210524?d=tree&c=pol_major_subtype&l=radial)

Another phylogenetic tree layout, the Radial format. Different tree formats can be changed in Auspice and can be used and extracted for external presentation.


# [Skygrid coalescent model estimations of effective population size between 1981-2020 for PANGEA and LANL dataset](http://localhost:4000/pol/20210524)

Estimation of the effective population size of the whole [PANGEA](https://www.pangea-hiv.org/) and [LANL](https://www.hiv.lanl.gov/content/index) dataset based on the skygrid coalescent model. The red line indicates the mean skygrid estimations in log scale of the pol phylogenetic tree within the timeframe indicated by the x-axis. The light pink surrounding the red line indicates the upper and lower confidence interval of the estimation. Similarly, gag and env are shown in orange and blue respectively. The light purple carpet plot on the bottom indicate the time of sampling and the purple line indicate the average incidence rate of all ages per 1000 population between 1990 and 2020 in the PANGEA dataset (_South Africa, Bptswana, Zambia, Kenya, Uganda_) with the percentage indicated by the y-axis on the right. Iframe is interactive and gag, pol and env mean skygrid estimates are shown by hovering mouse over the year of interest. Plot can be downloaded in different formats (SVG and PNG) by clicking on the top right three dots button for a drop down menu.

Although the topology for gag, pol and env [phylogenetic trees](https://www.pangea-hiv.org/visualisations) differ greatly, the skygrid estimations shares a similar shape and trend and overlaps well after 1988 within each other's confidence intervals. This may be due to old recombination events causing issues estimating the correct topology and in turn influence the correct estimation of effective population size from genetic diversity. However, based on the resulting skygrid estimations, the effective population estimates for recent times (overlaps of the three gene regions) give good indication and representation of the whole population trend within the dataset. This result is shared and shown for all individual partners within this narrative which can be seen in this [link](https://xiaoyu518.github.io/). 

The correlation between the incidence curve and the skygrid estimation is also very high showing initial increase and gradual decrease  to recent years. The decreasing trend in the estimations have shown that the PANGEA data is also showing effective measures reducing incidence in recent years.

```auspiceMainDisplayMarkdown

<iframe width="1010" height="550" frameBorder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://xiaoyu518.github.io/PANGEA_Skygrid.html"></iframe>

Incidence rate data source: https://aidsinfo.unaids.org/

```

# [Skygrid coalescent model estimations of effective population size between 1981-2020 for Uganda partners](http://localhost:4000/pol/20210524)

Estimation of the effective popluation size of all Uganda partners ([Uganda Rakai](https://www.rhsp.org), [Partner Uganda](http://depts.washington.edu/uwicrc/?q=content/about-icrc), [MRC Uganda](https://www.mrcuganda.org)) based on the skygrid coalescent model. The different coloured line indicate the mean skygrid estimations of different partners in Uganda in log scale indicated by the x-axis. The errorband surrounding the line indicates the upper and lower confidence interval of the estimation. Hovering over the graph allows comparison of skygrid estimations at each time points. Sampling time carpet plots are shown in the bottom right corner with the same colour code. Purple line indicate the incidence rate per 1000 population for all ages in Uganda indicated in percentage by the right y-axis. Colour code of each individual partner name are indicated by the legend on the top right corner.

The three Uganda partners show a similar trend peaking at various time points around 1998 and followed by a decrease to recent years compared to the incidence rate curve. The different decreasing trend between partners and incidence rate show groups in the population and their population dynamic compared to the background Uganda population. Interesting trends such as the Rakai's re-insurgence from 2016 or the bigger decrease in effective population of Partner partner compared to the other two Ugandan partners may be interesting to look at in detail.

```auspiceMainDisplayMarkdown

<iframe width="1050" height="550" frameBorder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://xiaoyu518.github.io/Uganda_Skygrid.html"></iframe>

Incidence rate data source: https://aidsinfo.unaids.org/

```

# [Source Sink Ratio estimates and import and export events for individual partners from 1989](http://localhost:4000/pol/20210524)

Source and Sink: An epidemic can be described by a model of connected sources, sinks, and hubs. Sources are groups in a population that disproportionately pass on infections, sinks are groups that disproportionately receive infections, and hubs are both sources and sinks. Population groups can be defined by age, gender, riskiness of sexual behaviour, geography, occupation, cultural preferences and norms, migrational behaviour, or other characteristics and combinations thereof. Identifying these groups allows prevention to be tailored.

Through the analysis of the skygrids of gag, pol and env for each individual partner, the overlap of these three plots have shown high accuracy of the phylogenetic tree in representing the genetic diversity from the year 2000 onwards. This is also a representation although the topology of the three gene region phylogenetic tree differ, the estimation for this time period remain robust. Hence there is high confidence there is reduced recombination when assessing transmission events for this time period between partners. Although the cutoff of 2000 onwards is more stringent in reducing recombination effect on phylogenetic tree, the number of transition events between the partners is limited. Hence as a tradeoff of stringency of control of recombination and assessing transmission events between partners, the cutoff of 1989 for both figure 1 and 2 is proposed. Transition events are taken by tree traversal and counting the number of node to tip trait change from the date 1989 onwards.

Potential **sources** are coloured in light blue with blue text while **sinks** are coloured in dark blue with red text for the time period of 1989 - 2020 (Figure 1). Popart Copperbelt and Southern are potential hubs with equal import and export events. The longer the bar, the partner is more likely to be either a source or sink. As an example, the Rakai partner is a potential sink with only import events (Figure 2) and could be a potential target for requiring more attention for prevention measures. Similarly, vice versa, Partner Uganda is a major exporter and a potential source. Import and export transition events for individual partners are tallied in Figure 2.

```auspiceMainDisplayMarkdown

<iframe width="880" height="490" frameBorder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://xiaoyu518.github.io/pol_ssRatio_1989.html"></iframe>
<br/>
Figure 1

<p>&nbsp;</p>

<iframe width="1300" height="370" frameBorder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://xiaoyu518.github.io/pol_ssEvents_1989.html"></iframe>
<br/>
Figure 2

```

# [Import and export events for Uganda partners from 1989](http://localhost:4000/pol/20210524)

Import and export directionality between three Uganda partners (__Uganda Rakai, MRC Uganda and Partner Uganda__) and partners outside Uganda are displayed within the coloured bar plot. On the x-axis, the exporting partner and on the y-axis the number of transition events. The legends shows the importing partner and its corresponding colour. 

Through this bar plot, we can see that Partner Uganda is a major exporter (source) while Uganda Rakai is a major importer (sink). There are mainly internal transition events between Ugandan partners with a few imports from outside Uganda but only 3 export out of Uganda. 

```auspiceMainDisplayMarkdown

<iframe width="770" height="350" frameBorder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://xiaoyu518.github.io/pol_Uganda_Cohort_Transition.html"></iframe>

```

# [Import intensity plot for Uganda partners from 1989](http://localhost:4000/pol/20210524)

Import intensity plot is used to analyse the import transition event effect on the partner through the analysis of the skygrid plot and the import timing into that partner. Import timing is estimated as the midpoint date between the node and the tip having the transition event between two different partners. Directionality of the transition events are shown by different shapes coded by the legend on the right side of the plot.

Skygrid plots are shown for all three Uganda partners (pol) alongside incidence rate for Uganda in purple. Based on the different import events into the three Ugandan partner, the increases in effective population size estimated by the skygrid can be partially explained by the imports from other partners. For example, Uganda Rakai, the slight increase in 2006 to 2008 can be associated with the imports from Partner partner (upside down triangle) and the re-insurgence from 2016 is associated with the grouped imports from MRC Uganda and Outside Uganda (circle and crosses). Similarly, the mountain like shape for MRC Uganda between dates 2002 and 2006 can be associated with the imports from Partners and outside Uganda partners (square and kite). Therefore, although overall the incidence rate is dropping, the effective population of individual partner such as Rakai are still high due to imports from other partners. 


```auspiceMainDisplayMarkdown

<iframe width="1100" height="560" frameBorder="0" scrolling="no" marginheight="0" marginwidth="0" src="https://xiaoyu518.github.io/pol_Uganda_Import_Intensity.html"></iframe>

Incidence rate data source: https://aidsinfo.unaids.org/

```
