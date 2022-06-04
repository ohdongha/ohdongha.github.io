---
layout: default_modified
---

# Random questions

___
### 2022 Jun.

- What are example stories of using multiple whole genome alignment (mWGA) or graph genomes in a research?

- What are example stories of using ortholog group/pair information in a research, especially out of the plant kingdom? See [potentially relavent readings](relevant_3.md).

- What will be the best way (i.e. data type, structure, UI, etc.) to deliver ortholog group/pair information to researchers?  What do we want to use ortholog information for?  

___
### 2022 May

- Many tools for inference of ortholog groups (and other applications) prefer or require a set of one 'primary' or representative gene model (=isoform) per each protein-coding gene locus, as input, to make the computation, and the interpretation of results, easier or feasible. 

	- What will be the best way to choose a 'primary' gene model? Among isoforms, people often choose the one gives the longest ORF - is this the practice in all domains?

	- How often will the choice of isoforms affect the ortholog pair/group?  Can we calculate the effect of each isoform to the ortholog network structure (e.g. no change, changes in only certain neighboring orthologs, or changes also in ortholog groups)?

	- Eventually, can there be an ortholog pair/group inference that does not require 'primary' gene models, or even benefit from isoforms?

- What currently available ortholog group inference tools are "scalable," i.e. do not require running entire process again when a new genome added and the new addition does not change the existing ortholog grouping?

___
### 2022 Feb.

- How much are _trans_-acting enhancers responsible for regulating widely conserved functions (e.g. essential and house-keeping)? In a species with a recent expansion of TEs (and a larger genome size), will such enhancer regions still conserved in sequences but regulating from a longer distance? See [potentially relevant readings](relevant_2.md).

___
### 2022 Jan.

- What are the better measures of conservation or modification in gene regulation between sets of ortholog pairs, that account for complex expression datasets such as time-series or tissue/cell type-specific expression? See [potentially relevant readings](relevant_1.md).

- How to identify significant (e.g. adaptive) GRN modifications from background divergence derived from genetic drift.

- How to identify significant (e.g. adaptive) GRN modifications in recent polyploids (e.g. _Camelina sativa_) compared to their diploid relatives. Or is it even doable/useful?

- How to compare GRNs among multiple species effectively without relying on "reciprocal 1-vs-1 best-hit" ortholog pairs, including all lineage(s)-specific duplicates?

- A reference genome can be a chimera of haplotypes and whatnot, if the source is not only heterozygous but also heterogeneous (e.g. ecological samples). Would it be more useful as a reference to allow "wobble" nucleotides (then how about SVs ...)?

- How would the (epi-)genome of a Tolkienian elf (e.g. Legolas) be different from human? [#ElvenGenomics](https://twitter.com/inspirace/status/1467178107018915846?s=20){:target="_blank"}

___
Always click the large [Dong-Ha Oh](index.md) to go back to main index
