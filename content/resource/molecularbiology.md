---
title: "Molecular biology tools"
date: 2022-08-21T20:27:51+08:00
categories:
- category
- subcategory
tags:
- CRISPR
- FP
- Linux
keywords:
- tech
comments:       false
showMeta:       false
showActions:    false
thumbnailImage: /img/pmx090121colgenetics-001-1630015763.jpg
thumbnailImagePosition: left
#thumbnailImage: //example.com/image.jpg
---



## Fluorescence Proteins

-iRFP: miRFPnano670

- RFPs: mRuby3, mCherry


- GFPs: mGreenLantern, EGFP


- BFPs: TagBFP2, TagBFP


---
### Reference
1. [FPbase](https://www.fpbase.org/): FPbase is a moderated, user-editable fluorescent protein database designed by microscopists.


## Tissue/Cell type specific AAVs
>
---

Brain organ specific: BR1\
Liver specific:

Brain endothelial cell specific: AAV-BI30






## Tissue/Cell type specific promoter
>
---

- Pan-neuron: hSyn\
Kügler, S., E. Kilic, and M. Bähr. "Human synapsin 1 gene promoter confers highly neuron-specific long-term transgene expression from an adenoviral vector in the adult rat brain depending on the transduced area." Gene therapy 10.4 (2003): 337-347. [[DOI Link](https://doi.org/10.1038/sj.gt.3301905) | [PDF]()]

Excitatory neuron: CaMKIIa\
Inhibitory neuron: pGAD1. mDlx


Constitutive expression: EF1a, CAG

Drug induced: Tet-on system

Activity depedent: c-Fos promoter





## Genetically encoded indicators
- Calcium: GCaMP series [[GCaMP8s/m/f](https://www.janelia.org/jgcamp8-calcium-indicators) |  [GCaMP7s/f/b/c](https://doi.org/10.1038/s41592-019-0435-6) |  [GCaMP6s/m/f](https://doi.org/10.1038/nature12354)]\
- Potassium: [ ]\
- Dopamine: GRAB-DA[[GRAB-DA1.0](https://doi.org/10.1016/j.cell.2018.06.042) | [GRAB-DA2.0](https://doi.org/10.1038/s41592-020-00981-9)]; dLight[[dLight1.2](https://doi.org/10.1126/science.aat4422), [addgene](https://www.addgene.org/111068/)]\
- Histamine:
- eCB:
- Kinase activity sensor: PKA[]




## CRISPR systems
> The CRISPR-Cas system is a natural immune system for prokaryotes. Some bacteria, after being invaded by a virus, can store a small segment of the virus gene in a storage space called CRISPR in their own genome. When a virus invades again, the bacteria can recognize the virus based on the stored fragment and disable it by cutting off the virus' DNA.
---

### DNA target Cas9 based
**Knock out**: SpCas9, SaCas9\
DNA base editor: dCas9-xxx\
Transcriptional activator:


### RNA target Cas13 based
> Compared to Cas9-mediated DNA editing, Cas13-based RNA editing tools target dynamically transcribed RNA without permanent alteration of the genome, and the effect of RNA editing can be controlled by means of dose adjustment, etc., which is reversible and quite safer.
---

- RNA knockdown: Cas13d(RfxCas13d or CasRx, Cas13d from Ruminococcus flavefaciens XPD3002) [[DOI Link](https://doi.org/10.1016/j.cell.2018.02.033) | PMID:[29551272](https://pubmed.ncbi.nlm.nih.gov/29551272/)]


- RNA base editor: **REPAIR**(RNA Editing for Programmable A to I Replacement, dCas13-ADAR2): Using catalytically inactive Cas13 (dCas13) to direct adenosine-to-inosine deaminase activity by ADAR2. [[DOI Link](https://doi.org/10.1126/science.aaq0180) | PMID:[ 29070703](https://pubmed.ncbi.nlm.nih.gov/29070703/)]


### DNA base editor


## Optogenetics tools

- Neuronal activity activation: 
ChR2(Channelrhodopsin-2)[hChR2(H134R) | ChR2(C128A/C128S)]


- Neuronal activity scilence: NpHR(Halorhodopsin)

- Light-activated Cyclases: PAC & Cyclop


# Reference
1. [Resource website of Optogenetics in neuroscience](https://web.stanford.edu/group/dlab/optogenetics/), Karl Deisseroth lab
2. [Georg Nagel lab, University of Würzburg](https://www.biozentrum.uni-wuerzburg.de/en/bot1/research/prof-dr-georg-nagel/)
3. [Peter Hegemann lab, Humboldt-University of Berlin](https://www.unisyscat.de/people/current-group-leaders/hegemann-peter.html)


## Open Source & Commercial Softwares
1. [Pymol](https://pymol.org/2/); [PyMOL Wiki](https://pymolwiki.org/index.php/Main_Page)
2. [SnapGene](https://www.snapgene.com/)
3. [Benchling](https://www.benchling.com/)
4. [NEB cloner](https://nebcloner.neb.com/#!/)

## Vendor company
1. [New England Biolabs(NEB)](https://international.neb.com/): NEB is a leader in the discovery and development of molecular biology reagents.



## Ref Labs
1. [Feng Zhang lab, MIT](https://zlab.bio/)
2. [Karl Deisseroth lab, Stanford](https://web.stanford.edu/group/dlab/about_pi.html)
3. [Yulong Li lab, PKU](http://www.yulonglilab.org/)
4. [David Liu lab, Harvard](https://www.liugroup.us/)
