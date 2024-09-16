# Acute Myeloid Leukemia Heatmap Analysis

## Overview

This project analyzes RNA-seq data from acute myeloid leukemia (AML) samples using heatmaps and clustering techniques. The analysis focuses on identifying patterns in gene expression across different AML models and treatments.

## Software Requirements

To run this project, you will need:

- R (version 4.0+)
- RStudio IDE
- Various R packages (listed below)

## Last Updated

This project was last updated on October 2021.

## Goals

The primary goals of this project are:

1. To visualize gene expression patterns across AML samples using heatmaps
2. To identify clusters of similar samples based on gene expression
3. To annotate the heatmap with sample-specific information
4. To explore the effects of different mutations and treatments on gene expression profiles

## Files Location

The main files for this project are located in the following directories:

- Source code: Main R script (not shown in the provided code snippet)
- Data: Located in the "data" folder
- Plots: Generated heatmaps and other visualizations stored in the "plots" folder
- Results: Intermediate results and processed data stored in the "results" folder

## How to Run the Project

1. Clone the repository or download the zip file
2. Ensure you have R and RStudio installed
3. Install the necessary R packages:
   ```r
   install.packages(c("pheatmap", "readr", "dplyr", "magrittr", "sessioninfo"))
   ```
4. Navigate to the project directory in RStudio
5. Run the main R script (name not provided in the code snippet)

## Usage Instructions

The main steps in running this project are:

1. Set up the analysis folders
2. Load and preprocess the data
3. Perform clustering and create the heatmap
4. Annotate the heatmap with sample information
5. Generate and save the final heatmap visualization

## Additional Notes

- The project uses data from the Shih et al., 2017 study, available on refine.bio
- The analysis focuses on 19 AML samples obtained from AML model mice
- Gene selection is based on variance, selecting genes in the upper quartile
- Sample annotations are based on mutation status (TET2, IDH2, WT) and treatment

## License

[Insert license information here]

## Acknowledgments

This project was adapted from a refine.bio examples notebook and is part of the CCDL for ALSF initiative. Special thanks to Candace Savonen for adapting this repository.

Citations:
[1] https://usethis.r-lib.org/reference/use_readme_rmd.html
[2] https://cran.r-project.org/web/packages/projects/readme/README.html
[3] https://stackoverflow.com/questions/56358347/how-to-generate-readme-md-from-readme-rmd-for-r-package
[4] https://alexd106.github.io/intro2R/project_setup.html
[5] https://www.reddit.com/r/Rlanguage/comments/1dqqgv0/r_markdown_files_within_an_r_project/
[6] https://github.com/jtleek/rpackages/blob/master/README.md
[7] https://r-pkgs.org/other-markdown.html
[8] https://search.r-project.org/CRAN/refmans/usethis/html/use_readme_rmd.html
[9] https://www.reddit.com/r/learnprogramming/comments/vxfku6/how_to_write_a_readme/
[10] https://www.mygreatlearning.com/blog/readme-file/
