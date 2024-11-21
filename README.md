# R

## Connecting Rstudio to github

[Configure Ghuthub for Rstudio](https://gist.github.com/Z3tt/3dab3535007acf108391649766409421)

[https://happygitwithr.com/](a%20complete%20walkthrough%20on%20starting%20a%20git%20version%20controlled%20Rstudio%20project)

## Survival analysis

A useful introduction to the survival package:

<http://www.sthda.com/english/wiki/cox-proportional-hazards-model> (<http://www.sthda.com/english/wiki/survival-analysis-basics>)

## Biomart

An Ensembl based database that contains cross references, and annotation information on multiple organisms. [Vignette on Ensembl annotation](https://bioconductor.org/packages/release/bioc/vignettes/biomaRt/inst/doc/accessing_ensembl.html)

# Markdown tips and tricks

### Posit tips and tricks

A great summary on how to make your Markdown documents more user friendly and easier to follow by the Posit team:

[Rstudio basics](https://posit.co/blog/r-markdown-tips-tricks-1-rstudio-ide/)

[Cleaning your code](https://posit.co/blog/r-markdown-tips-tricks-2-cleaning-up-your-code/)

[Time savers](https://posit.co/blog/r-markdown-tips-and-tricks-3-time-savers/)

[Looks better works better](https://posit.co/blog/r-markdown-tips-tricks-4-looks-better-works-better/)

## Collapsible section

```         
<details>

<summary>Exciting code</summary>

</details>
```

## YAML header for the notebooks I use

<details>

<summary>Show header</summary>

```         
title: "HLA II promiscuity"
author: "Gergely Koppány"
date: "`r Sys.Date()`"
output: 
  html_notebook: 
    code_folding: hide
    collapsed: yes
    fig_caption: yes
    fig_height: 4
    fig_width: 5
    smooth_scroll: yes
    theme: sandstone
    toc: yes
    toc_depth: 5
    toc_float: yes
    number_sections: true
```

</details>

## Additional details on markdown rendering

<https://bookdown.org/yihui/rmarkdown-cookbook/parameterized-reports.html#parameterized-reports>

# Bioinformatics

## Nextflow: a pipeline for complete bioinformatic data processes

Nextflow offers multiple well documented and reproducible data analysis pipelines which should be considered, if reproducibility and convenience is important. [Nextflow's RNAseq pipeline](https://nf-co.re/rnaseq/3.16.0/)

## Salmon

Salmon analyses RNAseq data, and can determine, the strandedness, and other experimental parameters of the data, it it is unknown.

[Salmon to determine strandedness](https://salmon.readthedocs.io/en/latest/salmon.html#what-s-this-libtype), [https://salmon.readthedocs.io/en/latest/index.html](Salmon%20documentation)

## RSEM

RSEM is a transcript quantification tool, that can determine the transcript isoform, and gene counts from a BAM filke aligned to the transcriptome. [RSEM Documentation](https://www.encodeproject.org/documents/0c78ea4b-9392-421b-a6f3-6c858b6002aa/@@download/attachment/RSEM_Documentation.pdf)

## featureCounts

Another RNAseq quantification tool, that can quantify gene counts from a genome aligned BAM file. Is part of the Subread software package. [Documentation](https://subread.sourceforge.net/SubreadUsersGuide.pdf)

# Bash scripting

[Bash scripting cheat sheet](https://devhints.io/bash)

# Regex

[Regex Cheat Sheet](https://images.datacamp.com/image/upload/v1665049611/Marketing/Blog/Regular_Expressions_Cheat_Sheet.pdf)
