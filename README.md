# A Transcriptomic Atlas of Mouse Neocortical Layers

In the mammalian cortex, neurons and glia form a patterned structure across six layers whose complex cytoarchitectonic arrangement is likely to contribute to cognition.  This dataset contains transcriptomes from layers 1-6b of different areas (primary and secondary) of the adult (postnatal day 56) mouse somatosensory cortex. A total of 5,835 protein-coding genes and 66 noncoding RNA loci are differentially expressed ("patterned") across the layers. Layers 2-6b are each associated with specific functional and disease annotations that provide insights into their biological roles. This dataset extends currently available resources by providing quantitative expression levels, by being genome-wide, by including novel loci, and by identifying candidate alternatively spliced transcripts that are differentially expressed across layers. 

A search interface for this dataset is available at http://genserv.anat.ox.ac.uk/layers

Reference:

"A transcriptomic atlas of mouse neocortical layers", TG Belgard et al. *Neuron*, **25:605-616** (2011).

This dataset contains the following files and links:


| | |
|-|-|
|Documentation about cell types and imprinting|types_and_imprinting.pdf|
|Raw sequence reads|rawreads_fastqs.tar.gz (link: note this file is 46.4GB)|
|Layer enrichment probabilities(Ensembl genes)|ens_genes_probs.xlsx (link to spreadsheet)|
|Layer enrichment probabilities(Ensembl transcripts)|ens_trans_probs.xlsx (link to spreadsheet)|
|Layer enrichment probabilities(*de novo* cufflinks-built genes)|cuff_genes_probs.xlsx (link to spreadsheet)|
|Layer enrichment probabilities(*de novo* cufflinks-built transcripts)|cuff_trans_probs.xlsx (link to spreadsheet)|
|FPKMs for the above four datasets |fpkms.zip (link to zip file)|
|*de novo* gene models|denovo_gene_models.zip (link to zipped GTF format data)|
|LincRNA gene models|lincrna_models.zip (link to GTF format data)|
|Functional enrichments for sets of genes predicted in layers|significant_in_layers.zip|
|Functional differences between patterned and unpatterned genes|significant_patt_vs_unpatt.zip|
 

# Dorsal (dc2) and lateral (lc) cortex replications

All of these are links.

| | |
|-|-|
|Raw read FASTQ files|dc2_fastqs.tar.gz(25 GB), lc_fastqs.tar.gz(17 Gb)|
|BAM files with accompanying indexes|dc2.(A-F).bam, dc2.(A-F).bam.bai, lc.(A-F).bam, lc.(A-F).bam.bai|
|BigWig files for viewing in Ensembl browser|dc2.(A-F).bw, lc.(A-F).bw|
|FPKM values of genes and transcripts with confidence intervals|dc2_fpkms.tar.gz, lc_fpkms.tar.gz|
|Layer enrichment predicted probabilities|dc2_probs.zip. lc_probs.zip|
|Functional terms with contributing genes and *p*-values|dc2_functional.zip, lc_functional.zip|
|Genes sorted by similarity in predicted laminar patterning|dc2_lc_compare.tsv|


# Other links for this dataset

* [Interactive query webpage](http://genserv.anat.ox.ac.uk/layers)
* [Gene Expression Omnibus page for this dataset](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE27243)
* [UCSC Genome Browser showing normalised coverage of all reads](http://genome.ucsc.edu/cgi-bin/hgTracks?hgS_doOtherUser=submit&hgS_otherUserName=Grantbelgard&hgS_otherUserSessionName=mouse_layers_all)
* [UCSC Genome Browser showing uniquely mapping reads](http://genome.ucsc.edu/cgi-bin/hgTracks?hgS_doOtherUser=submit&hgS_otherUserName=Grantbelgard&hgS_otherUserSessionName=mouse_layers_unique)

This page adapted from http://wwwfgu.anat.ox.ac.uk/~grantb/mouse_layers/

<a href="https://doi.org/10.5281/zenodo.3465802"><img src="https://zenodo.org/badge/DOI/10.5281/zenodo.3465802.svg" alt="DOI"></a>

