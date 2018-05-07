This repository contains all the batch files used in the analysis of the soil microbiome from Gordon Square Gardens, Regent’s Park, Euston Square Gardens and Finsbury Park. The principle objective of this project was to determine how the physico-chemical properties and nutrient levels of the soil in the different sampling sites affects the variation of microbial communities observed. All bioinformatic analyses were carried out on Cirrus, the high performance computer cluster based at the University of Edinburgh. 

Raw sequence processing 
1. Joining of paired end reads - (joining_paired_ends)
2. Splitting libraries - (splitting_libraries) 
3. Counting operational taxonomic units (OTUs) - (counting_OTU_sequences) 
4. Summarise BIOM table - (BIOM_summarise_table) 
5. Core diversity analysis - (core_diversity_analysis) 
6. Conversion of PCoA plots into 2d plots - (2D_plots_weighted) 

Statistical analysis
1. Summarise taxa tables (summarise_taxa)
2. Analysis of statistical significance sample groupings - (compare_categories) 
  - This was carried out for pH, nitrogen, phosphorus and potassium across samples. 
3. Comparison of OTU frequencies across sample groups - (group_significance) 
  - This was carried out for pH, nitrogen, phosphsorus and potassium across identified phyla. 
