# TLO_redundancy_manuscript_2026
R scripts for the manuscript titled "Paralogs of the Candida albicans TLO gene family form interconnected functional networks with incomplete redundancy" 
      Emily Simonton a,b, Nayeli Cangelosi c, Mikki Zhou c, Philip S. Hendricks b,d, Andrew L. Woodruff b, Nathaniel Sharp c, Matthew Z. Anderson b,c,d,e


      a Microbiology Doctoral Training Program, University of Wisconsin - Madison, Madison, WI, USA.
      b Department of Microbiology, The Ohio State University, Columbus, OH, USA.
      c Laboratory of Genetics, University of Wisconsin - Madison, Madison, WI, USA.
      d Center for Genomic Science Innovation, University of Wisconsin - Madison, Madison, WI, USA.
      e Department of Microbial Infection and Immunity, The Ohio State University, Columbus, OH, USA.

      * correspondence: mzanderson@wisc.edu

doi: https://doi.org/10.64898/2026.06.29.735307

# Stats calculations are in the following files:
      Tamhane-Dunnett's 
      epistasis_calculation
      linear_model_stats
      determine_data_variance

# Base R script for constructing the main figure panels can be found in the following files:
# Fig1 
      C -> growth_data_combined_figures
# Fig2 
      B -> growth_data_combined_figures
# Fig3 
      B -> liq_fila_stacked_barchart
      D -> growth_analysis+figures
      F -> biofilm_mass_barchart
# Fig4 
      B -> growth_analysis+figures
      C -> surv_KM_curve
      D -> surv_AUC_barchart
# Fig6 
      A -> gene_expression_heatmap
      B -> DEG_stacked_barchart
      C -> DEG_dotplot
      D -> GO_enrichment_lolipop_plot
# Fig7 
      A -> growth_data_combined_figures
      B -> growth_analysis+figures
      C -> surv_AUC_barchart
      D -> growth_data_combined_figures 
      E -> growth_analysis+figures
      F -> surv_AUC_barchart
      H -> DEG_stacked_barchart
      I -> gene_expression_heatmap
# Fig8 
      A -> chord_diagram
      B -> Trait_ME_heatmap

# The R scripts for constructing the supplementary figures can be found in the following files:

# FigS2
      -> growth_analysis+figures
# FigS3
      -> growth_analysis+figures
# FigS4
      B -> growth_analysis+figures
      C -> growth_analysis+figures
# FigS5
      B -> growth_analysis+figures
      C -> growth_analysis+figures 
# FigS6
      volcano plots -> DEG_volcano_plots
      dendrogram -> WGCNA (cor_matrix)
# FigS7
      -> WGCNA (cor_mat, p_mat, pheatmap)
# FigS8
      A -> calculate_TPM_from_RNAseq
      B -> growth_analysis+figures
      
