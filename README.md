# scRNAseq analysis of CAS cohort samples

Analysis from the following paper:

Read JF, Serralha M, Armitage JD, Iqbal MM, Cruickshank MN, Saxena A, Strickland DH, Waithman J, Holt PG, Bosco A. Single cell transcriptomics reveals cell type specific features of developmentally regulated responses to lipopolysaccharide between birth and 5 years. Front Immunol. 2023 Oct 17;14:1275937. doi: 10.3389/fimmu.2023.1275937.

Data generated from 10x scRNAseq of matched Cord blood mononuclears cells (CBMC) and 5 year peripheral blood (PBMC) that recieved in vitro stimulation with lipopolysaccharide (LPS), Poly(I:C), or left unstimulated.

This repository includes the raw counts data (post cellranger) which are also available from the Gene Expression omnibus (GSE232186), available at https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE232186

The purpose of this repo is to demonstrate the main QC and analysis steps used for the project and included in the publication. The QC steps are wrapped in a single function which is applied to the raw counts data for each sample. The samples are then integrated and annotated, and example analysis is shown for differential expression analysis, pathways analysis, pseudotime trajectory analysis, and cell-cell communication analysis.

Note: This project was initated several years ago and as such several steps are outdated or sub-optimal since, and should be updated to more recent versions where possible.
