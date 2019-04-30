# Awesome Genome Browsers

This repo is for keeping track of genome browsers and genomic visualization tools. The initial list is taken from [twitter replies](https://twitter.com/David_McGaughey/status/1122878399159119872), Google-ing, and my memory.

I'd love pull requests!

## Reactive Genome Browsers (web)
Tool | Manuscript | Comments
---  | ---- | ----
[igv.js](https://github.com/igvteam/igv.js/) | - | JavaScript based tools from the IGV team. Super easy to get started. A bit barebones in functionality for track picking and plotting. Actively developed (as of April 2019)
[jbrowse](https://jbrowse.org) | [Genome Biology](https://www.ncbi.nlm.nih.gov/pubmed/27072794) | JavaScript / HTML5 tool. Actively developed (as of April 2019). They also have a Electron desktop tool. Good looking docs, tons of features. 
[higlass](http://higlass.io) | [Genome Biology](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-018-1486-1) | D3.js based 2D (Hi-C) and 1D genome browser. Can handle hundreds of tracks. Actively developed (as of April 2019). Docker app for deployment. 
[GIVE](https://www.givengine.org) | [Genome Biology](https://genomebiology.biomedcentral.com/articles/10.1186/s13059-018-1465-6) | 1D browser with some "2D" (Hi-C) data functionality. Docker install option. 

## Reactive Genome Browsers (desktop)
Tool | Manuscript | Comments
--- | ---- | ----
[epiviz](https://epiviz.github.io) | [Nature Methods](https://www.ncbi.nlm.nih.gov/entrez/eutils/elink.fcgi?dbfrom=pubmed&retmode=ref&cmd=prlinks&id=25086505) | R / bioconductor tool. From quick reading of docs, I don't see how this can be deployed on a personal server. Last update late 2018. 
[IGV](https://software.broadinstitute.org/software/igv/) | [Briefings in Bioinformatics](https://academic.oup.com/bib/article/14/2/178/208453/Integrative-Genomics-Viewer-IGV-high-performance?searchresult=1) | The benchmark for desktop tools. 

## Genome Visualization 
Tool | Manuscript | Comments
--- | ---- | ----
[ggbio](https://bioconductor.org/packages/release/bioc/html/ggbio.html) |  [Genome Biology](https://genomebiology.biomedcentral.com/articles/10.1186/gb-2012-13-8-r77) | R / bioconductor tool. *gg* for *gg*plot grammar. 
[Gviz](http://bioconductor.org/packages/release/bioc/html/Gviz.html) | [Statistical Genomics](https://link.springer.com/protocol/10.1007%2F978-1-4939-3578-9_16) | R / bioconductor tool. Handles many data types. Good docs. 
[karyoploteR](https://bioconductor.org/packages/release/bioc/html/karyoploteR.html) | [Bioinformatics](https://academic.oup.com/bioinformatics/article/33/19/3088/3857734) |  R / Bioconductor tool. As name suggests, most examples are genome-wide with karyoplots / ideograms with some overlaid data. 

## Discussions
[2018 Maria Nattestad](https://medium.com/@Marianattestad/one-genome-browser-to-rule-them-all-cc41e2daccd7)

[2013 A brief introduction to web-based genome browsers (Wang et al.)](https://academic.oup.com/bib/article/14/2/131/208726)
