Analysis Report 2: Your Title Here
================
Don Francisco
November 10, 2017

*Overall, a single-spaced page is about 500 words. So if the guidelines say half of a page, think about writing around 250 words. You can use the wordcountaddin in RStudio to track your progress.*

Introduction
============

Add about 1 page here. Must cite at least 5 peer reviewed articles.

Methods
=======

Sample origin and sequencing
----------------------------

Add about half a page here. In this section instead of first person (I/we), use Li et al. (Li *et al.*, 2015) and Seo et al. (Seo *et al.*, 2012), since you'll just be describing what they did, based on the methods in their paper(s). It's important to include this so the reader knows what the study design was for the data you will be presenting.

Computational
-------------

These are the methods that were used to process the sequencing data. Should probably be at least a half of a page. At a very minimum should include citations for biomartr, trimmomatic, and sailfish. Note that these three methods references don't count towards the five references you need to cite in the introduction.

Results
=======

In addition to a minimum of 4-5 figures/tables (and associated captions), you should include sufficient text in this section to describe what your findings were. Remember that in the results section you just describe what you found, but you don't interpret it - that happens in the discussion.

| genename |  mean\_count|
|:---------|------------:|
| EEF1A1   |    171057.69|
| SFTPB    |    116171.19|
| MIR6723  |     79496.49|
| FTL      |     67992.47|
| RNA28S5  |     66407.31|
| SFTPA2   |     62798.78|
| CD74     |     61554.19|
| FN1      |     55274.57|
| FTH1     |     46737.83|
| TPT1     |     45638.86|
| SFTPA1   |     43926.08|
| RNA18S5  |     41851.71|
| COL1A1   |     38104.70|
| ACTG1    |     37164.40|
| NEAT1    |     36768.17|

**Table 1**: The most highly expressed genes included are *SFTPB* and *EEF1A1*.

![](Analysis_Report_02_RNASeq_files/figure-markdown_github-ascii_identifiers/boxplot-of-highly-expressed-genes-by-smoking-status-1.png)

**Figure 1**: In this study, smoking status shows that overall, more males admitted to being current smokers or having smoked previously.

![](Analysis_Report_02_RNASeq_files/figure-markdown_github-ascii_identifiers/make-barplot-of-highly-expressed-genes-1.png)

**Figure 2**: From the 15 most highly expressed genes, males, on average, show a higher expression count than females do.

![](Analysis_Report_02_RNASeq_files/figure-markdown_github-ascii_identifiers/bar-plot-of-highest-expressed-genes-by-cancer-stage-1.png)

**Figure 3**: This figure compares the highest expression levels of these 15 genes at each cancer stage. The majority of the genes show highest expression levels at stage 2B cancer.

![](Analysis_Report_02_RNASeq_files/figure-markdown_github-ascii_identifiers/make-boxplot-of-highly-expressed-genes-by-gender-1.png)

**Figure 4**: Comparison of high expression levels by gender and cancer stage. Over every stage of cancer, expression levels in each gene are often slightly higher in males. Interestingly at stage 2B cancer, high expression levels are only seen in males.

![](Analysis_Report_02_RNASeq_files/figure-markdown_github-ascii_identifiers/boxplot-of-gender-and-cancer-on-random-genes-1.png)

**Figure 5**: A comparison of three random genes shows that male gene expression grows exponentially higher at later cancer stages.

Discussion
==========

Add around 1-2 pages interpreting your results and considering future directions one might take in analyzing these data.

Sources Cited
=============

Li,Y. *et al.* (2015) RNA-seq analysis of lung adenocarcinomas reveals different gene expression profiles between smoking and nonsmoking patients. *Tumor Biology*, **36**, 8993–9003.

Seo,J.-S. *et al.* (2012) The transcriptional landscape and mutational profile of lung adenocarcinoma. *Genome research*, **22**, 2109–2119.
