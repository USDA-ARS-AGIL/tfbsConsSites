# tfbsConsSites
--

#### Cattle Genome TFBS site prediction

This is the rehosting of previously published transcription factor binding sites (TFBS) identified in the Btau4.0 Cattle reference genome. A phylogenetic-footprinting approach, using [TFLOC](http://www.ncbi.nlm.nih.gov/pubmed/19329064), was used to identify candidate TFBS sites based on their similarity to canonical TFBS motifs. 

For detailed methods, and to cite this work, please refer to [this article](http://www.sciencedirect.com/science/article/pii/S1672022913000120). 

## File descriptions:

| File | Contents | 
| :--- | :--- |
cattle_bc_tfbs_btau4.bed.gz | All identified TFBS motifs identified in the reference genome above the significance threshold.
gene_table_tfbs_count.tab.gz | A list of TFBS motifs sorted by gene order
index.html | The previous website's HTML implementation
snp_tfbs_with_gene_intersection.xls | An excel table with sorted TFBS intersections with genes

## Text file column descriptions:

#### cattle_bc_tfbs_btau4.bed.gz

This file follows the Bed #9 format and can be used as a track on the UCSC genome browser.

1. Chromosome
2. Start
3. End
4. TFBS name (from JASPAR annotation)
5. TFLOC score (higher is better)
6. Strand orientation
7. Start
8. End
9. Color

#### gene_table_tfbs_count.tab.gz

1. TFBS name (from JASPAR annotation)
2. JASPAR ID
3. Gene intersection (Official Gene symbol)
4. Gene intersection (RefGene accession)
5. Gene intersection (MGC accession)
6. Number of TFBS detected upstream of gene