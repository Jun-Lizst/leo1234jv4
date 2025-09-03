---
title: "Genomics and Sequencing"
date: 2022-08-21T10:43:59+08:00
categories:
- category
- subcategory
tags:
- RNA-seq
- scRNAseq
- NGS
keywords:
- tech
comments:       false
showMeta:       false
showActions:    false
thumbnailImage: /img/genomics_NGSx1.png
thumbnailImagePosition: left
#thumbnailImage: //example.com/image.jpg
---

# RNA-Seq

> 

#### KITS FOR RNA EXTRACTION
Takara: Smart-Seq


#### SEQUENCING PLATFORM
[illumina](https://www.illumina.com/);
[Huada Gene](https://www.genomics.cn/sequecplatform.html)



#### ANALYSIS SOFTWARES

**QC**:
  - [fastqc](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/): FastQC aims to provide a simple way to do some quality control checks on raw sequence data coming from high throughput sequencing pipelines. It provides a modular set of analyses which you can use to give a quick impression of whether your data has any problems of which you should be aware before doing any further analysis.
  - [multiqc](https://multiqc.info/): MultiQC searches a given directory for analysis logs and compiles a HTML report. It's a general use tool, perfect for summarising the output from numerous bioinformatics tools.
  - [fastp](https://github.com/OpenGene/fastp): an ultra-fast all-in-one FASTQ preprocessor



**Reads Mapping**:
  - [HISAT2](http://daehwankimlab.github.io/hisat2/): graph-based alignment of next generation sequencing reads to a population of genomes. ([Manual](http://daehwankimlab.github.io/hisat2/manual/))
  - [STAR](https://github.com/alexdobin/STAR): The STAR software package maps large sets of high-throughput sequencing reads to a reference genome with high levels of accuracy and speed. ([Manual](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EWzT0NuF1ANJsMKXYwCwuNYBIRXeIC-AcJ-hx6XSar7Ebw?e=j0P6Rs))\
  - [TopHat](http://ccb.jhu.edu/software/tophat/index.shtml): TopHat is a fast splice junction mapper for RNA-Seq reads. It aligns RNA-Seq reads to mammalian-sized genomes using the ultra high-throughput short read aligner Bowtie, and then analyzes the mapping results to identify splice junctions between exons. ([Manual](http://ccb.jhu.edu/software/tophat/manual.shtml))



Samtools:


**Gene Counting**\
FeatureCounts;
HTseq-Count:


**Difference Analysis**\
R packages: DESeq2; edgeR;


**Single-Cell RNAseq**\
R packages: [Seurat](https://satijalab.org/seurat/)



**Gene Symbol Converter**:\
https://david.ncifcrf.gov/content.jsp?file=conversion.html
https://www.syngoportal.org/convert.html





**Enrichment analysis tools**\
http://www.pantherdb.org/


**Genome resource**
- [UCSC Genome Browser](http://genome.ucsc.edu/):The UCSC Genome Browser is an online and downloadable genome browser hosted by the University of California, Santa Cruz (UCSC). It is an interactive website offering access to genome sequence data from a variety of vertebrate and invertebrate species and major model organisms, integrated with a large collection of aligned annotations.
- [NCBI Mouse Resources](https://www.ncbi.nlm.nih.gov/genome?term=mus%20musculus):


**Gene name search**
- [MGI](http://www.informatics.jax.org/): MGI is the international database resource for the laboratory mouse, providing integrated genetic, genomic, and biological data to facilitate the study of human health and disease.
- [Uniprot](https://www.uniprot.org/): UniProt is the world's leading high-quality, comprehensive and freely accessible resource of protein sequence and functional information.
- [HUGO](https://www.genenames.org/): HUGO Gene Nomenclature Committee, The HGNC is a resource for approved human gene nomenclature containing ~42000 gene symbols and names and 1300+ gene families and sets.



**Brain Atlas from Allen Institute for Brain Science(AIBS)**\
http://celltypes.brain-map.org/rnaseq/mouse/cortex-and-hippocampus


**Single Cell Sequencing Platforms**
- **High-throughput**
  - 10X genomics [[Introduction video]()]
    - Chromium Single Cell 3' Reagent Kits User Guide (v3.1 Chemistry) [User Manual](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/ETHl5W_dmbtHqUrrZr-L7BMB5eSuW_qiZce1ZNfYYKS7_w?e=lJ42Z2)]
  - ICELL8 cx Single-Cell System [[Introduction video](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/EYT8Rtj2eX1Cs5cW4cfnjKUBWJ7BqMcDQ4TZ7_mwDa5tuw?e=F3lfyc) | [User Manual](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/ERTyEi1mUSlBsm1jGzs0LmgBxlxYpDfvC3V9gP-Ej66SpA?e=9qTuTe)]
- **Manual**
  - SMART-Seq v4 Ultra Low Input RNA Kit for Sequencing (Takara Cat# 634894) [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EQZou07bFiJAoNWvSKIMrLUB0zvJmkjlfLBhIv7Rnl3qXw?e=4FbLKD)]


**Transcriptome database of different Brain cell types**
1. https://www.brainrnaseq.org/, Started at [Ben A. Barre lab](), maintained by [Ye Zhang lab](http://www.yezhanglab.org/yezhang).


**Brain single-cell genomics Browsers**
1. Dropviz: http://dropviz.org/

2. Mousebrain (Both adolescent and development): http://mousebrain.org/

3. VascularSingleCell: http://betsholtzlab.org/VascularSingleCells/database.html

4. [Fly Cell Atlas](https://flycellatlas.org/): The Fly Cell Atlas brings together Drosophila researchers interested in single-cell genomics, transcriptomics, and epigenomics, to build comprehensive cell atlases during different developmental stages and disease models.



**Ref papers**:

1. Sahraeian, Sayed Mohammad Ebrahim, et al. "Gaining comprehensive biological insight into the transcriptome by performing a broad-spectrum RNA-seq analysis." Nature communications 8.1 (2017): [Link](https://www.nature.com/articles/s41467-017-00050-4)
2. 


#### Ref labs
1. **Single cell genomics**: 
- [Satija lab, NYU](https://satijalab.org/)
  - Choosing a single cell technology. [[PDF Slides](https://www.dropbox.com/s/wl6sgqxb5rt44sq/SatijaLab_ChoosingTech.pdf?dl=1)]
  
2. **Functional genomics**:
- Wensheng Wei lab, PKU


- Xiaole Shiery Liu, Harvard



3. **Spatial Transcriptomics**: 
- [Rongfan lab, Yale](https://www.eng.yale.edu/fanlab/Responsive_Fan_lab/index.html)
- [Fei Chen lab, Broad institute](https://www.insitubiology.org/)
- [Evan Macosko lab, Broad institute](https://macoskolab.com/)

4. **Transcriptomics of brain cell types**: 
- **Ben A. Barre (1954-2017)**, Stanford University School of Medicine\
    Pioneer of glia biology
    [A Tribute to Ben Barres]()
    - Cahoy, J. D. et al. A Transcriptome Database for Astrocytes, Neurons, and Oligodendrocytes: A New Resource for Understanding Brain Development and Function. Journal of Neuroscience 28, 264–278 (2008). [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EdtWpOFux75DtCYSoiM3UuUBr-4OU0A1XKl1UBCtVFcWKA?e=o9ZFRu) | [PMID: 18171944](https://pubmed.ncbi.nlm.nih.gov/18171944/) | [DOI Link](https://doi.org/10.1523/jneurosci.4178-07.2008)]
    - Zhang, Y. et al. An RNA-sequencing transcriptome and splicing database of glia, neurons, and vascular cells of the cerebral cortex. J Neurosci 34, 11929–47 (2014). [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EQ2ehPMHw3BOseT3pHzv-I0BB0suZlevjEsiVV2y-4dfpg?e=oPm4gO) | [PMID: 25186741](https://pubmed.ncbi.nlm.nih.gov/25186741/) | [DOI Link](https://doi.org/10.1523/jneurosci.1860-14.2014)]
  



---
#### Online conferences
1. **NYU single cell genomics, 2018**
    - [New Advances in Single-Cell Genomics (2018)](https://satijalab.org/scgd18/) [[Watch video](https://youtu.be/X4RBshgH1x0)]
    - Single Cell Genomics: Recent Advances and Future Directions [[PDF Slides](https://www.dropbox.com/s/2g1gj7q04696d01/scgd_2018_satija.pdf?dl=0)], Rahul Satija, NYGC/NYU 

2. **NYU single cell genomics, 2019**
    - [New Advances in Single-Cell and Spatial Genomics (2019)](https://satijalab.org/scgd19/) [[Watch video](https://youtu.be/UNlcBTknDZ8)]
    - [Mapping the brain with MERFISH](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/EbWme5Hh81BKpICBuyT4d4sBmPm_QoONccpQi2v_M9jy8Q?e=lzXz6u), Jeffery R. Moffitt, Harvard Medical School
    - [Reconstruction of developmental trajectories during zebrafish embryogenesis](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/EdeugURNrcFGuN2mcnKaeWkBJFj2d6BkULUKJM6jpe-cRA?e=fX40R0), Jeff Farrell, Harvard University


3. **NYU single cell genomics, 2020**
    - [New Advances in Single-Cell and Spatial Genomics (2020)](https://satijalab.org/scgd20/) [[Watch video](https://www.youtube.com/watch?v=UNlcBTknDZ8)]
    
4. **NYU single cell genomics, 2021**
    - [New Advances in Single-Cell and Spatial Genomics (2021)](https://satijalab.org/scgd21/) [[Watch video](https://www.youtube.com/watch?v=uFRe-UMUlMQ)]
    
5. **NYU single cell genomics, 2022**
    - [New Advances in Single-Cell and Spatial Genomics (2022)](https://satijalab.org/scgd22/) [[Watch video](https://www.youtube.com/watch?v=gJRS3KTlgdY&t=1s)]

6. **NYU single cell genomics, 2023**
    - [New Advances in Single-Cell and Spatial Genomics (2023)](https://satijalab.org/scgd23/) [[Watch video](https://www.youtube.com/watch?v=Dnnh6Jo-KRo)]
    
7. **NYU single cell genomics, 2024**
    - [New Advances in Single-Cell and Spatial Genomics (2024)](https://satijalab.org/scgd24/) [[Watch video](https://youtu.be/ahzRYaS3Hlo)]
    
8. **NYU single cell genomics, 2025**
    - [New Advances in Single-Cell and Spatial Genomics (2025)](https://satijalab.org/scgd25/) [[Watch video](https://youtu.be/ahzRYaS3Hlo)]
![nobelxqhemox](/img/SingleCellGenomicsDay2025_flyer.png)







---
## Nobel laureates
![nobelxqhemox](/img/nobel_prize.jpg)
---


3. **Walter Gilbert(1932-)**, Harvard University, Biological Laboratories, Cambridge, MA, USA\
The Nobel Prize in Chemistry 1980\
**DNA Sequencing and Gene Structure**
[[iBiology interview]() | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/ESLasGpogvVMvh4lDoG907IB81_uZWP46kxzSYNsvLox8A?e=pWUlZs) | [Source](https://www.nobelprize.org/prizes/chemistry/1980/gilbert/biographical/)]

2. **Frederick Sanger(1918-2013)**, Cambridge University, Great Britain\
The Nobel Prize in Chemistry 1980\
**Determination of Nucleotide Sequences in DNA**
[[Public talk](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/ESLmFc2bPj1NiQLr8MynjR8ByJViMi7kZA4tovrSNIpedg?e=4Bclbz) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EZMCejlGVNNGkWrDQA9Ex4sBUyUIoGYRkafoFt2BA7T3SQ?e=Js9jO3) |  [Source](https://www.nobelprize.org/prizes/chemistry/1980/sanger/facts/)]

1. **Frederick Sanger(1918-2013)**, University of Cambridge, Cambridge, United Kingdom\
The Nobel Prize in Chemistry 1958\
**The Chemistry of Insulin**
[[Read the Lecture](https://www.nobelprize.org/uploads/2018/06/sanger-lecture.pdf) | [Source](https://www.nobelprize.org/prizes/chemistry/1958/sanger/facts/)]