This repository provides the data and annotated R scripts necessary to reproduce the analyses presented in the paper:

**Mammal defaunation leads to biotic homogenization of plant communities in tropical rainforests**

Luiz Guilherme dos Santos Ribas, Nacho Villar, Valesca Zipparro, Sérgio Nazareth, Yuri Souza, Carlos Rodrigo Brocardo, Gabriela Schmaedecke, Luana Hortenci, Rafael Souza Cruz Alves, Mauro Galetti.

The repository includes:

📂 Excel spreadsheets with raw community data (one workbook per site; each workbook contains multiple sheets corresponding to sampling timepoints):

Cardoso_T0_T156.xlsx (CAR)

Carlos_Botelho_T0_T108.xlsx (CBO)

Itamambuca_T0_T156.xlsx (ITA)

Vargem_Grande_T0_T156.xlsx (VG)

📄 Detailed R Markdown (.Rmd) and HTML (.html) files that guide users through the process of reproducing the analyses for each site and the cross-site synthesis:

Four site-level scripts (CAR, CBO, ITA, VG) that include methods for:

Importing multi-sheet Excel data (timepoints)

Preparing community matrices and applying transformations used in the analyses

Calculating alpha diversity (e.g., richness, Shannon, inverse Simpson)

Calculating beta diversity / compositional dissimilarity through time

Fitting time × treatment statistical models (including mixed-effects models where applicable)

Producing the main plots used to summarize temporal trajectories by treatment

One cross-site meta-analysis script that includes methods for:

Compiling the model effect estimates from all four sites

Extracting the Time × Treatment (Defaunation) interaction term

Performing pairwise contrasts among sites

Generating combined comparison figures summarizing cross-site differences

Each file contains step-by-step code and comments so users can reproduce results and adapt the workflow to similar long-term defaunation experiments in tropical forests.

⚠️ Note: The scripts are set to save results to the user’s Desktop on Windows. If you are using macOS or Linux, you’ll need to adjust the desktop_path accordingly.

**The purpose of this repository is to promote reproducibility and provide a learning resource for ecologists interested in how mammal defaunation influences taxonomic diversity and biotic homogenization over time.**

We recommend downloading the .Rmd and .html files for optimal visualization and for an easier, guided reproduction of the full workflow.
