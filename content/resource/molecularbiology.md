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
> Progress in science depends on new techniques, new discoveries and new ideas, probably in that order.      --- Sydney Brenner

<!--more-->

![sydneybrenner1](/img/quotes_sydney_brenner.jpg)



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

---
## Fluorescence Proteins

-iRFP: miRFPnano670

- RFPs: mRuby3, mCherry


- GFPs: mGreenLantern, EGFP


- BFPs: TagBFP2, TagBFP


#### Ref. websites
1. [FPbase](https://www.fpbase.org/): FPbase is a moderated, user-editable fluorescent protein database designed by microscopists.



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

---
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

---
## Nobel laureates
- Emmanuelle Charpentier, Max Planck Unit for the Science of Pathogens, Berlin, Germany\
The Nobel Prize in Chemistry 2020\
**For the development of a method for genome editing** [[Nobel Lecture video](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/EdFqVEkJF0VIrA7BvepNFJIBf72T_osrFneQ4oBF3krq3w?e=Zg1j5C)]

- Jennifer A. Doudna, University of California, Berkeley, CA, USA\
The Nobel Prize in Chemistry 2020\
**The Chemistry of CRISPR: Editing the Code of Life** [[Nobel Lecture video](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/EdFqVEkJF0VIrA7BvepNFJIBf72T_osrFneQ4oBF3krq3w?e=Zg1j5C)]

- Osamu Shimomura, Marine Biological Laboratory (MBL), Woods Hole, MA, USA; Boston University Medical School, Massachusetts, MA, USA\
The Nobel Prize in Chemistry 2008\
**Discovery of Green Fluorescent Protein, GFP** [[Nobel Lecture video](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/Ea7xbY7WDeFMjWMlFhE5Rr8BBd-j396_n-03NDA4n3CnsA?e=Qz2IXt) | [Lecture Slides](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EU8OcGx8TRhEn-haQRwSFb4BauHuAkiGBI2PjtxSXr9XKg?e=4mwPl8) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/ERYnt5iVZXlPmIs7cG8Z8DIB9h4nRGs9GM_vI6x-hiJgDQ?e=6FHFNa) |  [Source](https://www.nobelprize.org/prizes/chemistry/2008/shimomura/lecture/)]

- Martin Chalfie, Columbia University, New York, NY, USA\
The Nobel Prize in Chemistry 2008\
**GFP: Lighting Up Life** [[Nobel Lecture video](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/EQFIlZcij4dHt1ziRU-APFsBGLj_jXt8Ehvz1gKYnyWw9g?e=d8d8x4) | [Lecture Slides](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EUB6WdVEbLNCs1laNYyrE1ABL5QxOSOO3wlGXeAq81uKwg?e=ZQRTaZ) | [Source](https://www.nobelprize.org/prizes/chemistry/2008/chalfie/lecture/)]

- Roger Y. Tsien, University of California, San Diego, CA, USA\
The Nobel Prize in Chemistry 2008\
**Constructing and Exploiting the Fluorescent Protein Paintbox** [[Nobel Lecture video](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/EX_KX-KLPsFBhgk9pOovOzIBqp8mjNiJMFrchuwG72LKxg?e=9C9yCR) | [Lecture Slides](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EbXNqpxXkjpIrhgjOkKCvzAB_K3sN2tHir1mLW5t61ea4w?e=q1npQ2) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EVZYQT1jreBBrSaWJ-MMmU8Bja7PbbZo16NCLwFhcSoJRg?e=QwVmgh) |  [Source](https://www.nobelprize.org/prizes/chemistry/2008/tsien/facts/)]


- Phillip A. Sharp, Massachusetts Institute of Technology (MIT), Center for Cancer Research, Cambridge, MA, USA\
The Nobel Prize in Physiology or Medicine 1993\
**Split Genes and RNA Splicing** [[Nobel Lecture video](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/EdFqVEkJF0VIrA7BvepNFJIBf72T_osrFneQ4oBF3krq3w?e=Zg1j5C) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EXAic-FpAitMhZO63Hu_Fk0BLgmFdBfA5ekBdp-M6YXerA?e=oXw1fI) | [Source](https://www.nobelprize.org/prizes/medicine/1993/sharp/facts/)]
- Richard Roberts, New England Biolabs, Beverly, MA, USA\
The Nobel Prize in Physiology or Medicine 1993\
**An Amazing Distortion in DNA Induced by a Methyltransferase** [[Nobel Lecture video](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/EffVy-YZa5xJhCho-d_ClsQBpUu5KI8463FRFW6BZ8t1Dw?e=9I2cS2) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EURYg9C5uWJDhxl5SriTYugB6RKFveeKkXnfq9xOAeYVHw?e=SFvfnq) | [Source](https://www.nobelprize.org/prizes/medicine/1993/roberts/facts/)]
- Susumu Tonegawa, Massachusetts Institute of Technology (MIT), Cambridge, MA, USA\
The Nobel Prize in Physiology or Medicine 1987\
**Somatic Generation of Immune Diversity** [[[Nobel Lecture video](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/EXrmZU1m_VxLtWWavzDn3s0Bw7013B1NEqK7RZ2AOrCwEQ?e=D6e6Az) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/ERFkAs1pvepClNLYtNEEPDQBBrMX_t-wbkoKzRH0NRkUxw?e=QWs5gr) | [Source](https://www.nobelprize.org/prizes/medicine/1987/tonegawa/lecture/)]

- Paul Berg, Stanford University, Stanford, CA, USA\
The Nobel Prize in Chemistry 1980\
**Dissections and Reconstructions of Genes and Chromosomes** [[Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/Eei88f7LZ4hOrkvR5Irn2QABVfOyABK3paWRENRv3i9ZKg?e=kwt7Fv) | [Source](https://www.nobelprize.org/prizes/chemistry/1980/berg/lecture/)]

- Daniel Nathans, Johns Hopkins University School of Medicine, Baltimore, MD, USA\
The Nobel Prize in Physiology or Medicine 1978\
**Restriction Endonucleases, Simian Virus 40, and the New Genetics** [[Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EXU0uVvUd6JEr9Z2CyCwtXoBKfAgsNO2Tg78BAbFvOpLrg?e=MdCExv) | [Source](https://www.nobelprize.org/prizes/medicine/1978/nathans/facts/)]

- Werner Arber, Biozentrum der Universität, Basel, Switzerland\
The Nobel Prize in Physiology or Medicine 1978\
**Promotion and Limitation of Genetic Exchange** [[Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/Eei88f7LZ4hOrkvR5Irn2QABVfOyABK3paWRENRv3i9ZKg?e=tHafsw) | [Source](https://www.nobelprize.org/prizes/medicine/1978/arber/facts/)] 

- Hamilton O. Smith, Johns Hopkins University School of Medicine, Baltimore, MD, USA\
The Nobel Prize in Physiology or Medicine 1978\
**Nucleotide Sequence Specificity of Restriction Endonucleases** [[Read the Lecture]() | [Source](https://www.nobelprize.org/prizes/medicine/1978/smith/facts/)]

