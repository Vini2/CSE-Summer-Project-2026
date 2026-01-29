# Flinders CSE Summer Project 2026
Code repo for Bianca's CSE Summer project

## Plan

Pick  a microvirus of interest from our IBD phages and characterise the genome as follows.

### Step 1. Compare the genome to known viruses from the *Microviridae* family. 

Download the genomes from the [ICTV record for *Microviridae*](https://ictv.global/taxonomy/taxondetails?taxnode_id=202403855&taxon_name=Microviridae) which will direct you to the relevant NCBI records.

Build a phylogenetic tree of all the genomes using [Mashtree](https://github.com/lskatz/mashtree) and visualise it using [iTOL](https://itol.embl.de/).

### Step 2. Annotate the genome.

Use [Pharokka](https://github.com/gbouras13/pharokka), [Phold](https://github.com/gbouras13/phold) and [Phynteny](https://github.com/susiegriggo/Phynteny_transformer) to annotate the genome. Make sure to run them in the given order. 

Then, pick a few closely related microviruses that have already been characterised and visualise their annotations with those of our genome using [Clinker](https://github.com/gamcil/clinker) plots.

### Step 3. Compare the abundance of the genome in UC, CD and HHC sample.

Check how the abundance values of the genome in each of the UC, CD and HHC samples differ.
