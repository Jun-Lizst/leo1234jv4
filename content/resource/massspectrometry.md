---
title: "Mass spectrometry"
date: 2022-08-21T13:24:59+08:00
categories:
- category
- subcategory
tags:
- LS-MS
- MALDI
- Orbitrap
keywords:
- tech
comments:       false
showMeta:       false
showActions:    false
thumbnailImage: /img/QE_plus4_C27_lab_402.jpg
thumbnailImagePosition: left
#thumbnailImage: //example.com/image.jpg
---
> Atoms are not indivisible, for negatively electrified particles can be torn from them by the action of electrical forces.\
--- Sir J.J. Thomson

<!--more-->

![quote_JJ_thomson](/img/massspec_JJ_Thomson.jpg)



---
# LC-MS system

**| LC(Liquid Chromatography) part**
1. LC

2. HPLC
    - HPLC User Maintenance & Troubleshooting ([PDF](https://www.agilent.com/cs/library/slidepresentation/public/HPLC_User_Maintenance_and_Troubleshooting.pdf)), [Agilent](https://www.agilent.com/en/product/liquid-chromatography)
    - HPLC Columns
    - Nexera UHPLC/HPLC System, [Shimadzu Corporation](https://www.shimadzu.com.cn/an/hplc/nexera-uhplc-hplc-system/3385.html)
    - Vanquish UHPLC FLEX, [Thermo Fisher](https://www.thermofisher.com/cz/en/home/industrial/chromatography/liquid-chromatography-lc/hplc-uhplc-systems/vanquish-flex-uhplc-system.html)
    - ACQUITY UPLC, [Waters](https://www.waters.com/nextgen/us/en/products/chromatography-systems/acquity-premier-system.html)

**| MS(Mass spectrometry) part**
1. Orbitrap based: 
- **Review article**: Evolution of Orbitrap Mass Spectrometry Instrumentation [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EQUzf1IT4yFAnxTzocu7x3ABLgI2qWrPlVhiKY0rRi89-g?e=J304Ws) | [PMID: 26161972](https://pubmed.ncbi.nlm.nih.gov/26161972/) | [DOI Link](https://doi.org/10.1146/annurev-anchem-071114-040325)]
    - Q Exactive-HF
    - Q Exactive-fusion
    - Orbitrap Exploris 240
    - Orbitrap Exploris 480
    - Lumos
    

2. Triple Quadrupole based
    - TSQ Quantum
    - TSQ Altis
    - SCIEX QTRAP5500
    - SCIEX QTRAP6500
    - SCIEX QTRAP7500


3. Protocol for metabolite extraction
    - From tissue/organ for HILIC LC-MS: [PDF]()
    - From Plasma: [PDF]()
    - From adherent cell line: [PDF]()



## Vendor companies
1. [ThermoFisher](https://www.thermofisher.cn/cn/en/home/industrial/mass-spectrometry/liquid-chromatography-mass-spectrometry-lc-ms.html)
2. [SCIEX](https://sciex.com/products/mass-spectrometers)
3. [Agilent](https://www.agilent.com.cn/zh-cn/product/liquid-chromatography)
4. [Waters](https://www.waters.com/nextgen/us/en/products/columns.html)
5. [Shimadzu Corporation](https://support.shimadzu.com.cn/an/resource/index.html#105)



---
# MALDI system
1. MALDI
    - Rapiflex, MALDI-TOF/TOF, Bruker  
    - TimsTOF-Pro, Bruker: powered by the Trapped Ion Mobility Spectrometry(TIMS) [[]]
    - TimsTOF Pro 2, Bruker: powered by the latest Parallel Accumulation SErial Fragmentation (PASEF®) [[Introduction Link](https://www.bruker.com/en/products-and-solutions/mass-spectrometry/timstof/timstof-pro-2.html) | [PDF](https://ionopticks.com/wp-content/uploads/2021/09/1888423-timstof-pro-2-2021-ebook-rev-01-1.pdf?srsltid=AfmBOop_lD6wMhv6kGc6d8OVG_oNQlTvlBv3lY8wvUcjo_t4A8crNwON)]
      > Beyond its high sensitivity, the timsTOF Pro instrument stands out for its capacity to resolve positional phosphorylation isomers in the gas phase, thereby providing researchers with more comprehensive insight into signaling pathways.\
      In particular, the speed and sensitivity of TimsTOF Pro enable us to see more small peptides from limited amounts of starting material, which we expect to be particularly valuable for new discovery. 


2. AP/MALDI
    - MassTech
    - TransMIT




---
## Vendor companies
1. [Bruker](https://www.bruker.com/en.html)
2. [MassTech™](https://www.apmaldi.com/main/)


---
## Proteomics

- **Upstream: Protocol for peptide mixture cleanup**
   - **StageTips**
    - Rappsilber, J., Mann, M. & Ishihama, Y. Protocol for micro-purification, enrichment, pre-fractionation and storage of peptides for proteomics using StageTips. Nat Protocol 2, 1896–1906 (2007). [[DOI link](https://doi.org/10.1038/nprot.2007.261)]


- **Downstream: Bruker Proteomics solution**
  - Instrumentation
      - nanoElute (Bruker Daltonics)
      - 25cm * 75um * 1.6um C18 column(IonOpticks, Australia)
      - Column oven(Sonation)
      - captiveSpray Ion source(Bruker)
      - timsTOF Pro(Bruker Daltonics)
  - Method
      - PASEF
      - dia-PASEF
      - prm-PASEF
  - Data Processing
      - PEAKS Studio, PEAKS Online
      - MaxQuant
      - Skyline
      - ProteinMetrics


#### Post-translational Modifications











#### Proteomics analysis softwares

1. [mMass](https://github.com/xxao/mMass-Dist): The mMass program we use to open spectra in .msd format has been discontinued and is no longer supported. The program website http://mmass.org/ is inactive and will soon be completely removed. The latest version of mMass can be downloaded from https://github.com/xxao/mMass-Dist. 
2. [Mass Spectrum Interpreter](https://chemdata.nist.gov/mass-spc/interpreter/): The Interpreter finds possible structural origins of peaks in a mass spectrum and provides formula and isotopic processing utilities. It operates in conjunction with the MS Search Program. Version 2 replaces all earlier versions and was described in a poster in the meeting of the International Mass Spectrometry Society, Edinburgh, UK, 2003, "An Automated Method for Verifying Structure-Spectral Consistency Based on Ion Thermochemistry" ([Download ppt](https://chemdata.nist.gov/mass-spc/interpreter/docs/imsc03_poster.zip)). 
3. [OpenMS](https://openms.de/): OpenMS 2.0, a robust, open-source, cross-platform software specifically designed for the flexible and reproducible analysis of high-throughput MS data. The extensible OpenMS software implements common mass spectrometric data processing tasks through a well-defined application programming interface in C++ and Python and through standardized open data formats. OpenMS additionally provides a set of 185 tools and ready-made workflows for common mass spectrometric data processing tasks, which enable users to perform complex quantitative mass spectrometric analyses with ease.
4. [MSclassifR](https://cran.r-project.org/web/packages/MSclassifR/index.html): MSclassifR is an R package that has been specifically designed to improve the classification of mass spectra obtained from MALDI-TOF mass spectrometry. It offers a comprehensive range of functions that are focused on processing mass spectra, identifying discriminant m/z values, and making accurate predictions. The package introduces innovative algorithms for selecting discriminating m/z values and making predictions.
5. [MSTools](https://ms.epfl.ch/): The open access EPFL MStoolbox is a compilation of all these tools that allow the analysis of High Resolution Mass Spectra directly from your web browser. This webpage provides guidelines and explanations for each tool and is targeted for both beginners and advanced MS users. The EPFL MStoolbox could be particularly useful for anyone working in the field of Mass Spectrometry but does not have access to commercial software for the data treatment. 









---
## Ref. Labs
1. [Lingjun Li Lab](https://www.lilabs.org/), University of Wisconsin Madison

2. [West Coast Metabolomics Center](https://metabolomics.ucdavis.edu/), UC Davis
- Fiehn Laboratory for Untargeted Metabolomics
- Newman Laboratory for Lipid Mediators
- Hammock Laboratory for Inflammatory Metabolism

3. [Mass Spectrometry of Biopolymers (BioMS), Core facility, IOCB-Prague](https://msbiopolymers.group.uochb.cz/en)
- **Bottom-up proteomics**
  - The analysis focuses primarily on the identification of proteins, their post-translational modifications, and/or the quantification of proteins, either using methods based on isotopic labelling or label-free methods. The procedure involves proteolytic digestion of proteins and the analysis of the resulting peptides. The analysis itself is based on liquid chromatography coupled with high-resolution mass spectrometric analysis of peptides. This allows for sensitive and reliable identification/quantification of proteins or their modifications in the analyzed sample. Protein samples in various forms can be analyzed. We can analyze dried protein samples, as well as proteins separated in SDS-PAGE gel or proteins dissolved in various buffers.

- **Top-down proteomic analysis**
  - **Intact mass:** Analysis of the intact mass of proteins or nucleic acids under denaturing conditions. **It serves as a more precise equivalent to SDS-PAGE with a mass determination accuracy up to 1 Da.** It is possible to analyze both pure proteins and nucleic acids, as well as simpler mixtures (up to, for example, 10-20 pure proteins). More complex mixtures, or a very heterogeneous mixture of different proteoforms of one protein, can be problematic; however, it is possible to perform LC-MS separation of the sample before analysis. It is also possible to analyze larger proteins, such as antibodies. We also provide the calculation of Drug-to-Antibody Ratio (DAR) for antibody-drug conjugates as a service.

  - **Native MS:** Native mass spectrometry allows for the study of non-covalent protein-protein or protein-ligand complexes under biologically relevant "native" conditions. The analysis is performed using very gentle ionization, which allows the entire non-covalent complex to be transferred from solution to the mass spectrometer detector.





---
### Metabolomics analysis softwares
1. [MetaboAnalyst](https://www.metaboanalyst.ca/MetaboAnalyst/home.xhtml): v5.0
2. [MZmine3](http://mzmine.github.io/)
3. [MS-DIAL](http://prime.psc.riken.jp/compms/msdial/main.html)
4. [MaxQuant](https://www.maxquant.org/)
5. [SpatialMeta]()




### Online courses
1. **2018 North American Mass Spectrometry Summer School(1st Annual)**
    - [MS-based compound identification in untargeted metabolomics](https://youtu.be/UB1mOfcJwYc), Oliver Fiehn, University of California-Davis 
    - [Protein Quantification by Mass Spectrometry Part II/Development and Application of Chemical Tags](https://youtu.be/WUO5ZiaJFX0), Lingjun Li, University of Wisconsin-Madison    

2. **2019 North American Mass Spectrometry Summer School(2nd Annual)**
    - [Ionization](https://youtu.be/cZ5AFL47A1I), Evan R. Williams
    - [Quantitative Proteomics](https://youtu.be/YdQF6EjQmZA), Lingjun Li
    - [Exploring Proteomes Using Discovery and Targeted Mass Spectrometry Approaches](https://youtu.be/hC8y1sA4ShA), Ulrike Kusebauch
    - [Acquisition Methods-DDA, DIA and PRM](https://youtu.be/-_BNOTQu1WQ), Jesse G. Meyer
    - [Spectral Interpretation](https://youtu.be/9PN2PYX0yUU), Beatrix Ueberheide
    - [Science Writing](https://youtu.be/CR3aWDNmVCo), Alicia Williams
    - [Post-translational Modifications](https://youtu.be/IQ5ygy2aTp0), Judit Villen
    - [Mass Analyzers](https://youtu.be/aypTeWXgihc), Michael Westphall
    
3. **2021 North American Mass Spectrometry Summer School(3nd Annual)**
    - [Deconstructing a Mass Spectrometer](https://youtu.be/4NbxGCS3K1g), Mike Westphall/Kenny Lee
    - [Separation Science of Complex Biological Mixtures](https://youtu.be/B4zlE0NqovA), Susan Olesik
    - [Tandem MS](https://youtu.be/PhHdS6oyENU), Joshua Coon
    - [Data Analysis and interpretation with MaxQuant and Perseus](https://youtu.be/8-OChUiOyiU), Jürgen Cox
    - [Publishing your Science](https://youtu.be/4Uplxis6eek), Shawnna Buttery
    - [How to Set-up an LC Run](https://youtu.be/OZ4p5KpPdmw), Laura Muehlbauer/Justin McKetney
    - [How to Calibrate a Mass Spectrometer](https://youtu.be/rRcC-xhXK4o), Austin Salome/Trent Peters-Clarke
    - [Post-translational Modifications](https://youtu.be/gOsp0eyaZgg), Evgenia Shishkova
    - [Experimental Design for Quantitative Proteomics](https://youtu.be/Z824vZXh5Ic), Edward Huttlin
    - [Metabolomics](https://youtu.be/aJo4s-QaOU4), Jessica Prenni
    - [Lipidomics](https://youtu.be/rnpudCq9CrU), John A. Bowden
    - [Top-down and Native MS](https://youtu.be/7EEmZLSU-0E), [Vicki Wysocki](https://research.cbc.osu.edu/wysocki.11/group-home/contact-info/); [nMS-to-SB](https://nativems.osu.edu/resources)
    - [Data Acquisition Methods](https://youtu.be/dgt9yKtoTg4), Jesper Velgaard Olsen
    
4. **2022 North American Mass Spectrometry Summer School(4th Annual)**: Tutorial lecture topics include: Mass Analyzers, Ionization, Tandem MS, Chromatography, Shotgun Proteomics, Instrument Acquisition and Setup, Data analysis, and PTMs. Also planned are lectures workshops for scientific and professional development.
    - [Exploring the “Social Network” within a Human Cell](https://youtu.be/tlkD4sCbN7o), Edward Huttlin
    - [Future Technology Needs, Panel Discussion](https://youtu.be/RH7sz8Z8WAE)\
    Panelists: John A. Bowden, Ben Garcia, Jessica Prenni, Edward Huttlin, Lingjun Li, Rachel Loo, David Geffen, Vicki Wysocki
    
    
---
## Nobel laureates
![nobelxqhemox](/img/nobel_prize.jpg)
---

- **Koichi Tanaka**, Shimadzu Corp., Kyoto, Japan\
The Nobel Prize in Chemistry 2002\
**The Origin of Macromolecule Ionization by Laser Irradiation** [[Nobel Lecture video](https://nobel-videocdn01.azureedge.net/video/lecture_2002_che_tanaka_01_496.mp4) | [Read the Lecture](https://www.nobelprize.org/uploads/2018/06/tanaka-lecture.pdf)]

- **John B. Fenn**, Virginia Commonwealth University, Richmond, VA, USA\
The Nobel Prize in Chemistry 2002\
**Electrospray Wings for Molecular Elephants** [[Nobel Lecture video](https://nobel-videocdn01.azureedge.net/video/lecture_2002_che_fenn_01_496.mp4) |[Read the Lecture](https://www.nobelprize.org/uploads/2018/06/fenn-lecture.pdf)]

- **Francis W. Aston**, University of Cambridge, Cambridge, United Kingdom\
The Nobel Prize in Chemistry 1922\
**Mass Spectra and Isotopes** [[Read the Lecture](https://www.nobelprize.org/uploads/2018/06/aston-lecture.pdf)]

- **Joseph John Thomson (J.J. Thomson)**, University of Cambridge, Cambridge, United Kingdom\
The Nobel Prize in Chemistry 1906\
**Carriers of Negative Electricity** [[Documentary video](https://nobel-videocdn01.azureedge.net/video/docu_1906_phy_thomson_01_496.mp4) | [Read the Lecture](https://www.nobelprize.org/uploads/2018/06/thomson-lecture.pdf)]
