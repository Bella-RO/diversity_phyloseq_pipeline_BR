# diversity_phyloseq_pipeline_BR
Bioinformatics flow for the study of bacterial species diversity in bee microbiota (phyloseq object)
# Bioinformatics workflow for studying bacterial species diversity in the bee microbiota based on `phyloseq` objects

## Abstract
This repository compiles the bioinformatics workflow and associated scripts used to analyze the **bacterial diversity of the bee microbiota**.  
The study aims to characterize the structure and composition of microbial communities under different experimental treatments, using a **`phyloseq` object** as an integrative framework for taxonomic, phylogenetic, and abundance data.

The proposed workflow enables the assessment of richness, alpha and beta diversity, and statistical comparisons between experimental groups, facilitating the ecological and functional interpretation of results.
---
## Workflow summary
**Module: Ecological analysis of the community**  
1. **Richness and alpha diversity indices** (Shannon, Simpson)  
2. **Beta diversity** (Bray–Curtis, NMDS)  
3. **Relative abundance analysis** by taxonomic level  
4. **Comparisons between treatments** (ANOVA, Kruskal–Wallis, Dunn tests)  
---
## Included files
- `diversity_pipeline.R` — Script for alpha and beta diversity analyses based on the `phyloseq` object.  
- `abundance_pipeline.R` — Script for relative abundance based on the `phyloseq` object.  
---
## Author
**Bella Romero (BR)**  
The workflow and scripts were developed and adapted by Bella Romero (2025) as part of a study on bacterial diversity in the bee microbiota.  
Acknowledgment is given to colleagues for their contributions to specific bioinformatics modules.
---
## Suggested citation
> Romero, B. (2025). *Bioinformatics workflow for studying bacterial species diversity in the bee microbiota based on phyloseq objects.* GitHub: [https://github.com/bella-RO/diversity_phyloseq_pipeline_BR](https://github.com/bella-RO/diversity_phyloseq_pipeline_BR)
