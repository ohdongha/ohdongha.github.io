---
layout: default_modified
---

# Tools

Each link leads to the GitHub repository for the tool.

___

## [PiP](https://github.com/dinnenylab/BrassicaceaeGRN){:target="_blank"}
- An attempt to identify functions and gene sets (e.g. Gene Ontology terms) that underwent lineage(s)-specific modifications in gene expression/regulation among multiple species, by performing Phylogenetically-informed Profiling (PiP) of gene sets.  Check the [re-recorded PAG2022 talk](https://www.youtube.com/watch?v=zR9b0oKNfiM){:target="_blank"} for details.

- The matrice of presence and absence of positive corrleation between all pairs of species are superimposed to the species tree, for all gene sets. Variance of correlations are then ranked to find out the most significant modifications.

<details markdown=1><summary markdown="span"> Publication </summary>
- Y Sun<sup>\*</sup>, <u>D-H Oh</u><sup>\*</sup>, L Duan, P Ramachandran, A Bartlett, K-N Tran, G Wang, M Dassanayake, JR Dinneny (2022), **Divergence in a stress regulatory network underlies differential growth control.** _Nat Plants_ [doi:doi.org/10.1038/s41477-022-01139-5](https://doi.org/10.1038/s41477-022-01139-5){:target="_blank"}
(<sup>\*</sup>equal contribution)
</details><br>

___

## [OrthNet](https://github.com/ohdongha/OrthNet){:target="_blank"}
- An attempt to identify ortholog groups based on synteny/co-linearity and encode the evolutionary history of each ortholog group as the topology of Ortholog Network (OrthNet), among multiple closely related genomes. 

- OrthNet can (1) improve the resolution of solely sequence-based orthology inferences (e.g. OrthoFinder); (2) serve as a platform to organize and compare various -seq data for multiple species; (3) identify lineage(s)-specific events that modify ortholog copy numbers and synteny, such as duplication, transposition, deletion, and combinations of them; and more.

<details markdown=1><summary markdown="span"> Publication </summary>
- <u>D-H Oh</u> and M Dassanayake (2019), **Landscape of gene transposition-duplication within the Brassicaceae family.** _DNA Res_ 26:21-36 [doi:10.1093/dnares/dsy035](https://doi.org/10.1093/dnares/dsy035){:target="_blank"}
</details><br>

___

## [Genome toolbox](https://github.com/ohdongha/Genome-Toolbox){:target="_blank"}
- Python scripts for exploring and fixing genome assembly (.fa) and annotation (.gtf).

- Useful if you want to (1) remove chunks in the middle of sequences when there is a gene model annotation (.gtf); (2) for all gene models in a .gtf, rename `transcript_id`, `gene_id`, and `gene_name` fields; (3) cluster gene models from the same locus (i.e. isoforms) and select, for example, those coding for longest ORFs as "primary" gene models; (4) extract sequences for genomic regions (e.g. promoters); (5) find all sequence elements (defined as regex) in a genome; and more.
  
___
Always click the large [Dong-Ha Oh](index.md) to go back to main index
