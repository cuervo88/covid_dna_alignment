# covid_dna_alignment
Code generated for rapid alignment show of any gene sequence from SARS-CoV-2



Main commands:

``` get_genes()``` Prints a list of genes

``` get_tree(gene)``` Makes a simple ascii phylogenetic tree of a specific SARS-CoV-2 gene with the most known mutant variants.

```get_seq_similarity(gene)``` Prints a number from 0 to 1 showing the conservation score of that gene sequence

```view_alignment(gene)``` Makes a plot of the aligned sequences to see how the alignment looks like.

For adding future variants it can be done just by modifying the file ```SARS_variant_examples.csv``` by adding the line of the new variant, and add the variant name and Pango Lineage name to the list inside ```covid_dna_alignment.ipynb``` (list_variants and list_lineage). Then, just run the command ```generate_gb_files()```

