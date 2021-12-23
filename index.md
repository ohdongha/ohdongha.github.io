---
layout: default_modified
---
Research assistant professor working with [Dassanayake lab.@LSU](https://www.lsugenomics.org/). I study plant comparative genomics, especially for those found in "extreme" environments a.k.a. [extremophytes](https://extremeplants.org/what-is-an-extremophyte/).

## Research
- Comparative genomics of [_Schrenkiella parvula_](https://extremeplants.org/species/schrenkiella-parvula/?ms=halophytes) and [_Eutrema salsugineum_](https://extremeplants.org/species/eutrema-salsugineum/?ms=halophytes), extreme stress-adapted relatives of _Arabidopsis_ and Brassicaceae crops (e.g. Camelina, canola, and other Brassica crops)
- Comparative genomics of [invasive and native _Phragmites australis_ (common reed) in North America](https://nas.er.usgs.gov/queries/greatlakes/FactSheet.aspx?Species_ID=2937)
- Comparative genomics of seagrass [_Halophila stipulacea_](https://www.gidon-winters.com/research) and its freshwater relative [_Vallisneria americana_](https://plants.ifas.ufl.edu/plant-directory/vallisneria-americana/)
- Developing tools to systemetically detect lineage(s)-specific modifications in gene copy numbers and gene regulatory networks (GRNs)

Details under construction ...

## Tools
#### [OrthNet](https://github.com/ohdongha/OrthNet)
- An attempt to identify ortholog groups based on synteny/co-linearity and encode evolutionary histories of each ortholog group as the topology of Ortholog Networks (OrthNet), among multiple closely related genomes. 
- Can improve the resolution of solely sequence-based orthology inferences (e.g. OrthoFinder), serve as a platform to organize and compare various -seq data for multiple species, and identify lineage(s)-specific events that modify ortholog copy numbers and synteny, such as duplication, transposition, deletion, and combinations of them.
 
#### [Genome toolbox](https://github.com/ohdongha/Genome-Toolbox)
- Python scripts for exploring and fixing genome assembly (.fa) and annotation (.gtf).
- Useful if you want to remove chunks in the middle of sequences when there is a gene model annotation (.gtf), cluster gene models from the same locus (i.e. isoforms) and select, for example, those coding for longest ORFs as "primary" gene models, find all sequence elements (defined as regex) in a genome, etc.
  
#### PiP (under construction)
- An attempt to identify functions and gene sets (e.g. Gene Ontology terms) that underwent lineage(s)-specific modifications in gene expression/regulation among multiple species, by performing Phylogenetically-informed Profiling (PiP) of gene sets. 
- The matrice of presence and absence of positive corrleation between all pairs of species are superimposed to the species tree, for all gene sets. Variance of correlations are then ranked to find out the most significant modifications. 

Each link leads to the GitHub repository for the tool.

## [Publications](publications.md)

## [Grants](grants.md)
