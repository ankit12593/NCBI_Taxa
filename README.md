# NCBI_Taxa
Updated NCBI taxonomy for taxonomic classification

NCBI Taxonomy Version: June 2024

===Data Summary===

Total number of 16S rRNA sequences: 27136 (file: 16S_rRNA_Seqs.rar)\
Seqs from kingdom Bacteria: 25996\
Seqs from kingdom Archea: 1140\
Taxa Level Count\
Kingdom: 2\
Phylum: 52\
Class: 127\
Order: 293\
Family: 774\
Genus: 4173\
Species: 20367


===MapSeq Command-line===\
One can utilize the Mapseq tool to assign taxonomies to query sequences\
#Link to mapseq tool\
https://github.com/jfmrod/mapseq

#Download Mapseq files and run on your query sequences
```
./mapseq querySeqs.fasta 16S_rRNA_Seqs.fasta customTaxa_NCBI_24.tax > output.mseq --outfmt simple
```

Taxa ID mapped to lineages in file all_lineages.txt

File NCBI_updatedTaxa.xlsx contains\
Sheet1: 16S rRNA sequence IDs mapped to taxa IDs (NCBI)\
Sheet2: Lineages for 27136 sequences\
Sheet3: Archea lineages for 1140 sequences
