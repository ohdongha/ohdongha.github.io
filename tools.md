---
layout: default_modified
---

# Tools

Each link leads to the GitHub repository for the tool.

## [OrthNet](https://github.com/ohdongha/OrthNet)
- An attempt to identify ortholog groups based on synteny/co-linearity and encode the evolutionary history of each ortholog group as the topology of Ortholog Network (OrthNet), among multiple closely related genomes. 
- OrthNet can (1) improve the resolution of solely sequence-based orthology inferences (e.g. OrthoFinder); (2) serve as a platform to organize and compare various -seq data for multiple species; (3) identify lineage(s)-specific events that modify ortholog copy numbers and synteny, such as duplication, transposition, deletion, and combinations of them; and more.
 
## [Genome toolbox](https://github.com/ohdongha/Genome-Toolbox)
- Python scripts for exploring and fixing genome assembly (.fa) and annotation (.gtf).
- Useful if you want to (1) remove chunks in the middle of sequences when there is a gene model annotation (.gtf); (2) for all gene models in a .gtf, rename `transcript_id`, `gene_id`, and `gene_name` fields; (3) cluster gene models from the same locus (i.e. isoforms) and select, for example, those coding for longest ORFs as "primary" gene models; (4) extract sequences for genomic regions (e.g. promoters); (5) find all sequence elements (defined as regex) in a genome; and more.
  
## PiP (under construction)
- An attempt to identify functions and gene sets (e.g. Gene Ontology terms) that underwent lineage(s)-specific modifications in gene expression/regulation among multiple species, by performing Phylogenetically-informed Profiling (PiP) of gene sets. 
- The matrice of presence and absence of positive corrleation between all pairs of species are superimposed to the species tree, for all gene sets. Variance of correlations are then ranked to find out the most significant modifications.
 
___
Always click the large [Dong-Ha Oh](index.md) to go back to main index
