Code relating to the generation of a gluconobacter pangenome, and species assignment of a novel strain
Author: Jacob Hudson

Steps
- Setup github
- Download genomes from genbank
- Setup Nextflow
- Rotate geneoms with DNAapler
- Re-annotate with bakta
- Identify appropriate outgroup
- Build pangenome with orthofinder
- Calculate pairwise ANI values
- Calculate pairwise dDDH values
- Make core genome phylogeny
- Run antiSMASH
- Run Bigslice (etc) to cluster secondary metabolite groups

Some other potential ideas
- identify other DNA features
-- prophages
-- plasmids
-- antiphage systems
-- transposons
- identify virulence factors
- predict antibiotic resistance



