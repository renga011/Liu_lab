---
title: "April 11"
author: "Kaushik Renganaath"
date: "11 April, 2025"  # Dynamic date formatting
output: 
  workflowr::wflow_html:
    toc: true               # Table of contents
    toc_float: true         # Floating TOC
    toc_depth: 3            # Depth of TOC headings
    code_folding: hide      # Hide code by default
    fig_width: 10           # Default figure width
    fig_height: 6           # Default figure height
    fig_retina: 2           # For better resolution in HTML
    theme: flatly           # Bootstrap theme
    highlight: pygments     # Syntax highlighting
    keep_md: true           # Keep intermediate markdown
    df_print: paged         # Better data frame printing
knit: workflowr::wflow_knit # Explicit knit function

workflowr:
  seed: 2024                # For reproducibility
  root: "."                 # Project root
  analysis_dir: "analysis/" # Where your Rmd files live
  docs_dir: "docs/"         # Where HTML outputs go
  cache_dir: "cache/"       # For cached chunks
---

<p>
<button type="button" class="btn btn-default btn-workflowr btn-workflowr-report"
  data-toggle="collapse" data-target="#workflowr-report">
  <span class="glyphicon glyphicon-list" aria-hidden="true"></span>
  workflowr
  <span class="glyphicon glyphicon-ok text-success" aria-hidden="true"></span>
</button>
</p>

<div id="workflowr-report" class="collapse">
<ul class="nav nav-tabs">
  <li class="active"><a data-toggle="tab" href="#summary">Summary</a></li>
  <li><a data-toggle="tab" href="#checks">
  Checks <span class="glyphicon glyphicon-ok text-success" aria-hidden="true"></span>
  </a></li>
  <li><a data-toggle="tab" href="#versions">Past versions</a></li>
</ul>

<div class="tab-content">
<div id="summary" class="tab-pane fade in active">
  <p><strong>Last updated:</strong> 2025-04-11</p>
  <p><strong>Checks:</strong>
  <span class="glyphicon glyphicon-ok text-success" aria-hidden="true"></span>
  7
  <span class="glyphicon glyphicon-exclamation-sign text-danger" aria-hidden="true"></span>
  0
  </p>
  <p><strong>Knit directory:</strong>
  <code>my_project_notes/</code>
  <span class="glyphicon glyphicon-question-sign" aria-hidden="true"
  title="This is the local directory in which the code in this file was executed.">
  </span>
  </p>
  <p>
  This reproducible <a href="https://rmarkdown.rstudio.com">R Markdown</a>
  analysis was created with <a
  href="https://github.com/workflowr/workflowr">workflowr</a> (version
  1.7.1). The <em>Checks</em> tab describes the
  reproducibility checks that were applied when the results were created.
  The <em>Past versions</em> tab lists the development history.
  </p>
<hr>
</div>
<div id="checks" class="tab-pane fade">
  <div class="panel-group" id="workflowr-checks">
  <div class="panel panel-default">
<div class="panel-heading">
<p class="panel-title">
<a data-toggle="collapse" data-parent="#workflowr-checks" href="#strongRMarkdownfilestronguptodate">
  <span class="glyphicon glyphicon-ok text-success" aria-hidden="true"></span>
  <strong>R Markdown file:</strong> up-to-date
</a>
</p>
</div>
<div id="strongRMarkdownfilestronguptodate" class="panel-collapse collapse">
<div class="panel-body">
  
Great! Since the R Markdown file has been committed to the Git repository, you
know the exact version of the code that produced these results.

</div>
</div>
</div>
<div class="panel panel-default">
<div class="panel-heading">
<p class="panel-title">
<a data-toggle="collapse" data-parent="#workflowr-checks" href="#strongEnvironmentstrongempty">
  <span class="glyphicon glyphicon-ok text-success" aria-hidden="true"></span>
  <strong>Environment:</strong> empty
</a>
</p>
</div>
<div id="strongEnvironmentstrongempty" class="panel-collapse collapse">
<div class="panel-body">
  
Great job! The global environment was empty. Objects defined in the global
environment can affect the analysis in your R Markdown file in unknown ways.
For reproduciblity it's best to always run the code in an empty environment.

</div>
</div>
</div>
<div class="panel panel-default">
<div class="panel-heading">
<p class="panel-title">
<a data-toggle="collapse" data-parent="#workflowr-checks" href="#strongSeedstrongcodesetseed2024code">
  <span class="glyphicon glyphicon-ok text-success" aria-hidden="true"></span>
  <strong>Seed:</strong> <code>set.seed(2024)</code>
</a>
</p>
</div>
<div id="strongSeedstrongcodesetseed2024code" class="panel-collapse collapse">
<div class="panel-body">
  
The command <code>set.seed(2024)</code> was run prior to running the code in the R Markdown file.
Setting a seed ensures that any results that rely on randomness, e.g.
subsampling or permutations, are reproducible.

</div>
</div>
</div>
<div class="panel panel-default">
<div class="panel-heading">
<p class="panel-title">
<a data-toggle="collapse" data-parent="#workflowr-checks" href="#strongSessioninformationstrongrecorded">
  <span class="glyphicon glyphicon-ok text-success" aria-hidden="true"></span>
  <strong>Session information:</strong> recorded
</a>
</p>
</div>
<div id="strongSessioninformationstrongrecorded" class="panel-collapse collapse">
<div class="panel-body">
  
Great job! Recording the operating system, R version, and package versions is
critical for reproducibility.

</div>
</div>
</div>
<div class="panel panel-default">
<div class="panel-heading">
<p class="panel-title">
<a data-toggle="collapse" data-parent="#workflowr-checks" href="#strongCachestrongnone">
  <span class="glyphicon glyphicon-ok text-success" aria-hidden="true"></span>
  <strong>Cache:</strong> none
</a>
</p>
</div>
<div id="strongCachestrongnone" class="panel-collapse collapse">
<div class="panel-body">
  
Nice! There were no cached chunks for this analysis, so you can be confident
that you successfully produced the results during this run.

</div>
</div>
</div>
<div class="panel panel-default">
<div class="panel-heading">
<p class="panel-title">
<a data-toggle="collapse" data-parent="#workflowr-checks" href="#strongFilepathsstrongrelative">
  <span class="glyphicon glyphicon-ok text-success" aria-hidden="true"></span>
  <strong>File paths:</strong> relative
</a>
</p>
</div>
<div id="strongFilepathsstrongrelative" class="panel-collapse collapse">
<div class="panel-body">
  
Great job! Using relative paths to the files within your workflowr project
makes it easier to run your code on other machines.

</div>
</div>
</div>
<div class="panel panel-default">
<div class="panel-heading">
<p class="panel-title">
<a data-toggle="collapse" data-parent="#workflowr-checks" href="#strongRepositoryversionstrongahrefhttpsgithubcomrenga011workingnotesliulabtree5f3181956368ab8bf6118dfce4b8dd0012d99403targetblank5f31819a">
  <span class="glyphicon glyphicon-ok text-success" aria-hidden="true"></span>
  <strong>Repository version:</strong> <a href="https://github.com/renga011/working_notes_liu_lab/tree/5f3181956368ab8bf6118dfce4b8dd0012d99403" target="_blank">5f31819</a>
</a>
</p>
</div>
<div id="strongRepositoryversionstrongahrefhttpsgithubcomrenga011workingnotesliulabtree5f3181956368ab8bf6118dfce4b8dd0012d99403targetblank5f31819a" class="panel-collapse collapse">
<div class="panel-body">
  
<p>
Great! You are using Git for version control. Tracking code development and
connecting the code version to the results is critical for reproducibility.
</p>

<p>
The results in this page were generated with repository version <a href="https://github.com/renga011/working_notes_liu_lab/tree/5f3181956368ab8bf6118dfce4b8dd0012d99403" target="_blank">5f31819</a>.
See the <em>Past versions</em> tab to see a history of the changes made to the
R Markdown and HTML files.
</p>

<p>
Note that you need to be careful to ensure that all relevant files for the
analysis have been committed to Git prior to generating the results (you can
use <code>wflow_publish</code> or <code>wflow_git_commit</code>). workflowr only
checks the R Markdown file, but you know if there are other scripts or data
files that it depends on. Below is the status of the Git repository when the
results were generated:
</p>

<pre><code>
Ignored files:
	Ignored:    .DS_Store
	Ignored:    analysis/.DS_Store
	Ignored:    analysis/Gene_based_COTA/
	Ignored:    analysis/SNP_based_COTA/.DS_Store

Untracked files:
	Untracked:  analysis/2024-04-10_snp_summary.md

</code></pre>

<p>
Note that any generated files, e.g. HTML, png, CSS, etc., are not included in
this status report because it is ok for generated content to have uncommitted
changes.
</p>

</div>
</div>
</div>
</div>
<hr>
</div>
<div id="versions" class="tab-pane fade">
  
<p>
These are the previous versions of the repository in which changes were made
to the R Markdown (<code>analysis/2024-04-10_snp_summary.Rmd</code>) and HTML (<code>docs/2024-04-10_snp_summary.html</code>)
files. If you've configured a remote Git repository (see
<code>?wflow_git_remote</code>), click on the hyperlinks in the table below to
view the files as they were in that past version.
</p>
<div class="table-responsive">
<table class="table table-condensed table-hover">
<thead>
<tr>
<th>File</th>
<th>Version</th>
<th>Author</th>
<th>Date</th>
<th>Message</th>
</tr>
</thead>
<tbody>
<tr>
<td>html</td>
<td><a href="https://rawcdn.githack.com/renga011/working_notes_liu_lab/b646a9ea6a65d28c62539ff64339cf8f78b7d99a/docs/2024-04-10_snp_summary.html" target="_blank">b646a9e</a></td>
<td>renga011</td>
<td>2025-04-11</td>
<td>Build site.</td>
</tr>
<tr>
<td>Rmd</td>
<td><a href="https://github.com/renga011/working_notes_liu_lab/blob/e432b0ce9e58e816d90546533f383b45dacd09f9/analysis/2024-04-10_snp_summary.Rmd" target="_blank">e432b0c</a></td>
<td>renga011</td>
<td>2025-04-11</td>
<td>wflow_publish(&quot;analysis/2024-04-10_snp_summary.Rmd&quot;)</td>
</tr>
</tbody>
</table>
</div>

<hr>
</div>
</div>
</div>






## COTA results with Lee et al. (2023)

Using:

-   **Cruchaga trans pQTL** (renamed genes)

-   **WES burden test** scores from Lee et al.

> **some statistics of the WES data from Lee et al.**
>
> -   Size of study cohort (ADSP 17k): 6519 cases (total 13371 with controls)
>
> -   Burden scores were computed for genes using different sets of variant types. Number of genes for each of these variant categories are as follows
>
>     -   plof_ds (putative loss of function - deleterious strict) - 15306
>
>         > WE USE THESE GENES FOR COTA AS THESE ARE HIGH CONFIDENCE, HIGH IMPACT
>
>     -   plof - 11771
>
>     -   disruptive_missense - 10776
>
>     -   missense - 18170
>
>     -   synonymous - 18100

### Result summary

-   **\# proteins tested in trans pQTL**: 6983

-   **\# proteins common with WES data (using only pLOF_ds)**: 5530

-   **\# significant pairs detected**: *0*

-   No detected significant pairs from COTA passed the FDR threshold of *q \< 0.1*, despite the sample size being \~6.5k cases (total \~13k with controls).

### Validity of WES P-values

We checked the distribution of WES-derived *p*-values:

> **Insert QQ plot and histogram here**

<img src="figure/2024-04-10_snp_summary.Rmd/unnamed-chunk-1-1.png" style="display: block; margin: auto;" />

  <p>
  <button type="button" class="btn btn-default btn-xs btn-workflowr btn-workflowr-fig"
  data-toggle="collapse" data-target="#fig-unnamed-chunk-1-1">
  Past versions of unnamed-chunk-1-1.png
  </button>
  </p>

  <div id="fig-unnamed-chunk-1-1" class="collapse">
  <div class="table-responsive">
  <table class="table table-condensed table-hover">
  <thead>
  <tr>
  <th>Version</th>
  <th>Author</th>
  <th>Date</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><a href="https://github.com/renga011/working_notes_liu_lab/blob/b646a9ea6a65d28c62539ff64339cf8f78b7d99a/docs/figure/2024-04-10_snp_summary.Rmd/unnamed-chunk-1-1.png" target="_blank">b646a9e</a></td>
  <td>renga011</td>
  <td>2025-04-11</td>
  </tr>
  </tbody>
  </table>
  </div>
  </div>
  

-   The qq-plot shows a small kink away from the null in between, which maybe due to this being p values pooled across ancestries, a smaller effective sample size (lesser carriers), or combination of both.

-   \~ This is only 6k samples and pooled across ancestries. Maybe therefore, there is no much power in the COTA

### What next?

-   Transition to Holstege et al. study data: Sample size \~16k cases (Total size with controls \~32.5k), and its all mostly Non hispanic white

------------------------------------------------------------------------

## COTA Results with Holstege data

### Validity of WES p values

<img src="figure/2024-04-10_snp_summary.Rmd/unnamed-chunk-2-1.png" style="display: block; margin: auto;" />

  <p>
  <button type="button" class="btn btn-default btn-xs btn-workflowr btn-workflowr-fig"
  data-toggle="collapse" data-target="#fig-unnamed-chunk-2-1">
  Past versions of unnamed-chunk-2-1.png
  </button>
  </p>

  <div id="fig-unnamed-chunk-2-1" class="collapse">
  <div class="table-responsive">
  <table class="table table-condensed table-hover">
  <thead>
  <tr>
  <th>Version</th>
  <th>Author</th>
  <th>Date</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><a href="https://github.com/renga011/working_notes_liu_lab/blob/b646a9ea6a65d28c62539ff64339cf8f78b7d99a/docs/figure/2024-04-10_snp_summary.Rmd/unnamed-chunk-2-1.png" target="_blank">b646a9e</a></td>
  <td>renga011</td>
  <td>2025-04-11</td>
  </tr>
  </tbody>
  </table>
  </div>
  </div>
  

### COTA run - notes

> Gene tagging with multiple aptamers
>
> The trans pQTL data from Cruchaga has multiple aptamers tagging the same gene/protein.
>
> -   Correlation between aptamers tagging same protein in Cruchaga et al.: **0.79**
>
> To preserve this signal:
>
> -   When gene IDs are duplicated, we rename them as `GENE_1`, `GENE_2`, etc.
>
> -   If even one aptamer shows significance, it’s worth examining as it may provide clues on the mechanism (eg: If aptamer specific to N-terminus is significantly mediating but that targetted to C-terminus isn't).
>
> So we apply this renaming consistently across:
>
> -   `pQTL_trans: p value matrix for the trans eQTLs`
>
> -   `WES_pvals: p values corresponding to Holstege rare variant burden scores`
>
> -   `ref.table.keep: annotations for every gene on its start, end, chromosome, gene name, gene type (protein_coding/lncRNA)`
>
> -   `pQTL_cis: cis pQTLs detected by Cruchaga et al. (2023). Taken from their Supplementary tables`

Using:

-   **Cruchaga trans pQTL** (renamed genes)

-   **WES burden test** scores from Holstege et al.

> **some statistics of the WES data Holstege et al.**
>
> -   Size of study cohort (mixed cohort - see Supplementary table 1 of paper) : 6519 cases (total 13371 with controls)
>
> Burden scores were computed for genes using different sets of variant types. Number of genes for each of these variant categories are as follows
>
> -   LOF and REVEL score \>= 25 - 15306
>
>     > WE USE THESE GENES FOR COTA as most genes are included in the data for this category
>
> -   LOF and REVEL score \>= 50 - 11771
>
> -   LOF and REVEL score \>= 75 - 10776

### Result Summary:

-   **\# proteins tested in trans pQTL**: 6983

-   **\# proteins common with WES data**: 4855

-   **\# genes in the WES data with significant burden test score (p \< 1e-6): 4**

-   **\# significant pairs detected (q \< 0.1): 210**

-   **Core genes: 7**

-   **Peripheral genes: 18**

-   Gene-dense regions are more informative than individual gene counts.

> genomic regions with hits: 4

### Network Diagram

<img src="figure/2024-04-10_snp_summary.Rmd/unnamed-chunk-3-1.png" width="100%" style="display: block; margin: auto;" />

  <p>
  <button type="button" class="btn btn-default btn-xs btn-workflowr btn-workflowr-fig"
  data-toggle="collapse" data-target="#fig-unnamed-chunk-3-1">
  Past versions of unnamed-chunk-3-1.png
  </button>
  </p>

  <div id="fig-unnamed-chunk-3-1" class="collapse">
  <div class="table-responsive">
  <table class="table table-condensed table-hover">
  <thead>
  <tr>
  <th>Version</th>
  <th>Author</th>
  <th>Date</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><a href="https://github.com/renga011/working_notes_liu_lab/blob/b646a9ea6a65d28c62539ff64339cf8f78b7d99a/docs/figure/2024-04-10_snp_summary.Rmd/unnamed-chunk-3-1.png" target="_blank">b646a9e</a></td>
  <td>renga011</td>
  <td>2025-04-11</td>
  </tr>
  </tbody>
  </table>
  </div>
  </div>
  

### Pathway Enrichment

> Perform GO/KEGG/Reactome enrichment.

-   No significant enrichments for core genes. Mostly due to their only being 7.

-   The following core genes were also burden test significant:

-   Performing on peripheral genes:

<img src="figure/2024-04-10_snp_summary.Rmd/unnamed-chunk-4-1.png" width="100%" style="display: block; margin: auto;" />

  <p>
  <button type="button" class="btn btn-default btn-xs btn-workflowr btn-workflowr-fig"
  data-toggle="collapse" data-target="#fig-unnamed-chunk-4-1">
  Past versions of unnamed-chunk-4-1.png
  </button>
  </p>

  <div id="fig-unnamed-chunk-4-1" class="collapse">
  <div class="table-responsive">
  <table class="table table-condensed table-hover">
  <thead>
  <tr>
  <th>Version</th>
  <th>Author</th>
  <th>Date</th>
  </tr>
  </thead>
  <tbody>
  <tr>
  <td><a href="https://github.com/renga011/working_notes_liu_lab/blob/b646a9ea6a65d28c62539ff64339cf8f78b7d99a/docs/figure/2024-04-10_snp_summary.Rmd/unnamed-chunk-4-1.png" target="_blank">b646a9e</a></td>
  <td>renga011</td>
  <td>2025-04-11</td>
  </tr>
  </tbody>
  </table>
  </div>
  </div>
  

-   Enrichment seen in **peripheral immune signaling pathways**

-   Likely driven by **HLA region**, which is very gene dense. The SNP based COTA assigns the SNP to the nearest genes with a cis pQTL. In such a gene dense region as HLA, you get multiple such assignments, and these will lead to enrichment in the immune signaling pathways, given all of them are of similar function. Hence, the GO/KEGG/Reactome enrichment is not so informative.

### What next?

-   Too little enrichments being seen. Have to amp up the power of the WES datasets. Search for a larger set or do meta-analysis over multiple WES sets maybe?!
-   Many of the obvious genes known to be associated with AD aren't enriched in COTA. See what's up with them? What is their trans p value and WES p values. Make a table for these genes.

<br>
<p>
<button type="button" class="btn btn-default btn-workflowr btn-workflowr-sessioninfo"
  data-toggle="collapse" data-target="#workflowr-sessioninfo"
  style = "display: block;">
  <span class="glyphicon glyphicon-wrench" aria-hidden="true"></span>
  Session information
</button>
</p>

<div id="workflowr-sessioninfo" class="collapse">

``` r
sessionInfo()
```

```
R version 4.4.1 (2024-06-14)
Platform: aarch64-apple-darwin20
Running under: macOS Ventura 13.5

Matrix products: default
BLAS:   /Library/Frameworks/R.framework/Versions/4.4-arm64/Resources/lib/libRblas.0.dylib 
LAPACK: /Library/Frameworks/R.framework/Versions/4.4-arm64/Resources/lib/libRlapack.dylib;  LAPACK version 3.12.0

locale:
[1] en_US.UTF-8/en_US.UTF-8/en_US.UTF-8/C/en_US.UTF-8/en_US.UTF-8

time zone: America/Chicago
tzcode source: internal

attached base packages:
[1] stats     graphics  grDevices utils     datasets  methods   base     

other attached packages:
[1] igraph_2.1.4    dplyr_1.1.4     magrittr_2.0.3  gridExtra_2.3  
[5] ggplot2_3.5.1   workflowr_1.7.1

loaded via a namespace (and not attached):
 [1] sass_0.4.9        generics_0.1.3    stringi_1.8.7     hms_1.1.3        
 [5] digest_0.6.37     evaluate_1.0.3    grid_4.4.1        fastmap_1.2.0    
 [9] rprojroot_2.0.4   jsonlite_2.0.0    processx_3.8.6    whisker_0.4.1    
[13] ps_1.9.0          promises_1.3.2    httr_1.4.7        scales_1.3.0     
[17] jquerylib_0.1.4   cli_3.6.4         rlang_1.1.5       crayon_1.5.3     
[21] bit64_4.6.0-1     munsell_0.5.1     withr_3.0.2       cachem_1.1.0     
[25] yaml_2.3.10       parallel_4.4.1    tools_4.4.1       tzdb_0.5.0       
[29] colorspace_2.1-1  httpuv_1.6.15     vctrs_0.6.5       R6_2.6.1         
[33] lifecycle_1.0.4   git2r_0.36.2      stringr_1.5.1     bit_4.6.0        
[37] fs_1.6.5          vroom_1.6.5       pkgconfig_2.0.3   callr_3.7.6      
[41] pillar_1.10.1     bslib_0.9.0       later_1.4.1       gtable_0.3.6     
[45] glue_1.8.0        Rcpp_1.0.14       xfun_0.51         tibble_3.2.1     
[49] tidyselect_1.2.1  rstudioapi_0.17.1 knitr_1.50        farver_2.1.2     
[53] htmltools_0.5.8.1 rmarkdown_2.29    labeling_0.4.3    readr_2.1.5      
[57] compiler_4.4.1    getPass_0.2-4    
```
</div>
