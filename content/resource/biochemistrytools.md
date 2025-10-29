---
title: "Biochemistry"
date: 2022-08-25T17:16:39+08:00
categories:
- category
- subcategory
tags:
- Cell biology
- Metabolism
- Cell signaling
keywords:
- tech
comments:       false
showMeta:       false
showActions:    false
thumbnailImage: /img/MnS-Total-Protein-Prestain-CF680T-BSA-gel.png
thumbnailImagePosition: left
#thumbnailImage: //example.com/image.jpg
---
> Our cells engage in protein production, and many of those proteins are enzymes responsible for the chemistry of life.\
--- Randy Schekman

<!--more-->

![randyschekman1](/img/randy_cell_enzymes_bag.jpg)

---
## Fundamental techniques

- **Protein quantification**
    - **SDS-PAGE (In-gel)**
      - pre-cast gels ([Novex Tris-Glycine Gel, Thermo](https://www.thermofisher.com/cz/en/home/life-science/protein-biology/protein-gel-electrophoresis/protein-gels/novex-tris-glycine-gels.html)) [6% | 7.5% | 10% | 12% | 4~15% | 4–20% | 8~16%]
      - pre-cast gels ([Mini-PROTEIN TGX Gel,BioRad](https://www.bio-rad.com/en-cz/product/mini-protean-tgx-precast-gels?ID=N3GRW04VY)) [8% | 10% | 4~12% | 8~16%]
      - Electrophoresis System: [[XCell SureLock Mini-Cell, Thermo](https://www.thermofisher.com/cz/en/home/life-science/protein-biology/protein-gel-electrophoresis/protein-gel-electrophoresis-chamber-systems/xcell-surelock-mini-vertical-electrophoresis-system.html) | [Mini-PROTEAN Tetra Cell, BioRad](https://www.bio-rad.com/en-cz/product/mini-protean-tetra-vertical-electrophoresis-cell?ID=N3F2UD4VY)]
      - Reagents: Laemmli Sample buffer, 2-Mercaptoethanol, DTT, Coomassie stain ([InstantBlue, Abcam](https://www.abcam.com/en-us/products/reagents/instantblue-coomassie-protein-stain-isb1l-ab119211?srsltid=AfmBOoqRseIMqMctrEZHgbdIyJl7AG3S_CSSlsP1BaYm3J-fyuJU7c7z) | [PageBlue, Thermo](https://www.thermofisher.com/order/catalog/product/24620))
      - Silver Staining: [[SilverQuest Silver staining kit (Thermo Fisher Scientific)](https://documents.thermofisher.com/TFS-Assets/LSG/manuals/silverquest_man.pdf)]: The SilverQuest™ Silver Staining Kit provides a rapid and easy method to silver stain proteins in polyacrylamide gels. Silver staining allows detection of most proteins since it is 30-fold more sensitive than staining with colloidal Coomassie G-250. This kit is specifically designed to provide sensitive silver staining compatible with mass spectrometry analysis. [Original article: [Rabilloud et al, 1994](https://pubmed.ncbi.nlm.nih.gov/8003936/)]
      - SYPRO Ruby Protein Stain: Sypro Ruby is a mass spec compatible protein stain with similar sensitivity as silver stain.
      - Instruments: [[Amersham™ ImageQuant™ 800, Cytiva](https://www.cytivalifesciences.com/en/us/shop/protein-analysis/molecular-imaging-for-proteins/imaging-systems/amersham-imagequant-800-systems-p-11546?psmenu=2) | [SPARK Plate reader, TECAN](https://lifesciences.tecan.com/multimode-plate-reader)]

    - **Native-PAGE**
      - The NativePAGE™ 5% G-250 Sample Additive
      - The NativePAGE™ Running Buffer (20X)
      - The NativePAGE™ Sample Buffer (4X)
      - The NativePAGE™ Cathode Buffer Additive (20X)
      
    - **Western blot**
      - PVDF membrane, 0.45 um pore size [[Millipore: IPFL00010](https://www.sigmaaldrich.com/CZ/cs/product/mm/ipfl00010?srsltid=AfmBOopgFe8mgpL3NnXRtELNsYD2xkQ07O8kmDEvVDhQkGzKy3dkiuHi)]
      - Transfer tank (Wet) [[Thermo: VEP-2](https://www.thermofisher.com/order/catalog/product/VEP-2) | [BioRad: ]() | Transfer buffer: CAPS]
      - Transfer system (Semi-Dry) [[BioRad:]()]
      
    - **BCA:** The BCA (Bicinchoninic Acid) protein assay is a colorimetric method for determining the total protein concentration in a solution. It relies on the reduction of copper(II) to copper(I) by protein in an alkaline solution, followed by the chelation of two molecules of BCA with each Cu(I) ion, resulting in a purple-colored complex that absorbs strongly at 562 nm. The intensity of the purple color is directly proportional to the amount of protein present, allowing for quantification by comparing the absorbance to a standard curve of known protein concentrations. 
      - Pierce™ BCA Protein Assay Kits [[User guide: PDF](https://assets.thermofisher.com/TFS-Assets/LSG/manuals/MAN0011430_Pierce_BCA_Protein_Asy_UG.pdf) | measure at 562 nm]
      - Pierce™ Dilution-Free™ Rapid Gold BCA Protein Assay Kit [[User guide: PDF](https://assets.thermofisher.com/TFS-Assets/LSG/manuals/MAN0029413-Pierce%20DilutionFree%20RapidGoldBCA-UG.pdf) | measure at 480 nm]
    - **Bradford:** The Bradford method is a quick and widely used colorimetric assay for determining protein concentration. It involves the binding of a dye, Coomassie Brilliant Blue G-250, to proteins, which causes a shift in the dye's absorbance spectrum. By measuring the absorbance of the resulting blue solution at 595 nm and comparing it to a standard curve, the protein concentration can be determined. [[original article, PMID:942051](https://pubmed.ncbi.nlm.nih.gov/942051/)]
      - **Calculation of Protein Extinction Coefficients**: The molar absorption coefficient of a peptide or protein is related to its tryptophan (W), tyrosine (Y) and cysteine (C) amino acid composition. At 280nm, this value is approximated by the weighted sum of the 280nm molar absorption coefficients of these three constituent amino acids. [[Online calculator](https://www.novoprolabs.com/tools/protein-extinction-coefficient-calculation)]
    - **ELISA**


- **Protein purification**
![biochem_akta1](/img/AKTA_diagram.png)
    - **ATKA Pure** [[Cytiva](https://cdn.cytivalifesciences.com/api/public/content/digi-16276-pdf) | [ÄKTA™ Laboratory-scale Chromatography Systems](https://www2.fcfar.unesp.br/Home/Instituicao/Departamentos/cienciasbiologicasnovo/laboratoriomultiusuariosfinep/akta_instrument_management.pdf)]: ATKA Pure is a modern, compact, flexible and intuitive FPLC (Fast Protein Liquid Chromatography) system for fast purification of proteins, peptides, and nucleic acids from microgram to gram levels of the desired compound. Can be used for affinity chromatography, size exclusion chromatography (SEC, also known as gel filtration), ion exchange chromatography, hydrophobic interaction chromatography, and reversed phase chromatography (RPC). [[Equipment SOP, PDF](https://biomanufacturing.org/uploads/files/804256350604880707-dp-5-operation-of-%C3%A4kta-pure-chromatography-system.pdf)]
![biochem_akta2](/img/AKTA_SEC_ects.png)
      - **Size-exclusion chromatography (SEC, Gel filtration)**: [[Superose 6 Increase 10/300 GL, Sigma, GE29-0915-96](https://www.sigmaaldrich.com/CZ/cs/product/sigma/ge29091596?srsltid=AfmBOoq-t30M5EBnVcDokmFE85e9QI2iCyZPuNUq8BvXF0XoP1XCFcKg) | [Superdex 200]() | [Superdex 75]() | [TSKgel G4000SWxl, Tosoh]()]
      - **Hydrophobic interaction chromatography (HIC)**: Phenyl-HP cartridge
      - **Anion exchange chromatography (AEC)**: [[HiTrap Q, Cytiva, 17115401](https://www.cytivalifesciences.com/en/us/shop/chromatography/prepacked-columns/ion-exchange/hitrap-q-hp-anion-exchange-chromatography-column-p-00607) | [Capto HiRes Q 10/100]() | [Mono Q 5/50 GL](https://cdn.cytivalifesciences.com/api/public/content/digi-12715-original) | [HiTrap DEAE FF](https://www.cytivalifesciences.com/en/us/shop/chromatography/prepacked-columns/ion-exchange/hitrap-deae-sepharose-ff-p-00605)]
      - **Cation exchange chromatography (CEC)**: [[SP-Sepharose, Cytiva](https://www.cytivalifesciences.com/en/us/shop/chromatography/prepacked-columns/ion-exchange/hitrap-sp-sepharose-ff-p-00798) | [Capto HiRes S 10/100]()]
![biochem_akta3](/img/AKTA_SEC_others.png)
      - **Affinity chromatography (AC)**: Heparin-affinity chromatography uses immobilized heparin to purify proteins by exploiting their ability to bind to the highly negatively charged glycosaminoglycan. [[HiTrap-Heparin HP](https://cdn.cytivalifesciences.com/api/public/content/digi-11293-pdf)]
      - **Reverse Phase chromatography (RPC)**: Reverse phase chromatography uses columns packed with a non-polar, hydrophobic resins such as polystyrene/divinyl benzene particles. 
      - **Affinity Tag based purification**:
        - Anti-FLAG: anti-Flag M2 affinity gel [[Millipore Sigma](https://www.sigmaaldrich.com/CZ/cs/product/sigma/a2220?srsltid=AfmBOoqHITxHuhMTw6YMp0sfyFchtOZCeJ8xMeE2PGH-olte2ivqRHFp)]
        - Twin-Strep: The Twin-Strep-tag® (WSHPQFEKGGGSGGGSGG-SAWSHPQFEK) is a tandem version of the Strep-tag®II with an internal linker region. This twin version with the same specificity but higher affinity to Strep-Tactin® enables efficient purification even in batch or directly from culture supernatants. 
        - His-Tag: [[Ni-NTA resin](https://www.qiagen.com/us/products/discovery-and-translational-research/protein-purification/tagged-protein-expression-purification-detection/ni-nta-agarose) | [HisTrap HP](https://cdn.cytivalifesciences.com/api/public/content/digi-12993-original)]
        - GST-Tag: [[Selection guide, Cytiva](https://cdn.cytivalifesciences.com/api/public/content/digi-14929-pdf) | [PMID: 26096507](https://pubmed.ncbi.nlm.nih.gov/26096507/)]
    - **Purifying Challenging Proteins, Principles and Methods** [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/ERJk71FTHSNElA3GMam-l3IBX6v_i_oCQeLQLG1Hb6bBiA?e=mAkBNn)]   
    - **Simulation software**: [Protein Purification](http://www.agbooth.com/pp_ajax/) starts off by letting you examine how a simple mixture of proteins behaves during gel filtration and ion-exchange chromatography and then goes on to allow the design and testing of full purification protocols using more complex mixtures of proteins.
    - **Compute isoelectric point (pl)**: [[ExPASy](https://web.expasy.org/compute_pi/) | [Protein isoelectric point calculator](http://isoelectric.org/)]
    
- **Protein interaction**
    - **Non-Covalent Bonds and Interactions**: Hydrogen Bonds, Ionic Bonds (Salt Bridges), Van der Waals Interactions, Hydrophobic Interactions
    - **Covalent Bonds**: Disulfide Bonds
    - **co-IP**: Anti-FLAG (DYKDDDDK) Magnetic Agarose beads [[Thermo](https://www.thermofisher.com/order/catalog/product/A36798?ef_id=CjwKCAjw7rbEBhB5EiwA1V49nccS1QFtXTbMm-oCz9VqsYqHrtQ5Kt6rMMK39Nfu2uTSpTGa4aiQBBoCnNgQAvD_BwE:G:s&s_kwcid=AL!3652!3!730146096394!!!g!!!22158546157!172279481245&cid=bid_sap_prp_r01_co_cp1362_pjt0000_bid00000_0se_gaw_dy_pur_con&gad_source=1&gad_campaignid=22158546157&gbraid=0AAAAADxi_GQApzePpHkuQmiLo2ZT9fVkx&gclid=CjwKCAjw7rbEBhB5EiwA1V49nccS1QFtXTbMm-oCz9VqsYqHrtQ5Kt6rMMK39Nfu2uTSpTGa4aiQBBoCnNgQAvD_BwE) | [Sigma](https://www.sigmaaldrich.cn/CN/en/product/sigma/m8823?srsltid=AfmBOoq6WDnv8XUxZ__m1yIopkj5LQ8DzGDd35wvJ0y0Waw-PB0f2HU8)]; Anti-HA Magnetic Agarose [[Thermo](https://www.thermofisher.com/order/catalog/product/88837?SID=srch-srp-88837)]
      - cross linking reagents: 
      - Magnetic Separation Rack: [[DynaMag™-2 Magnet](https://www.thermofisher.com/order/catalog/product/12321D)]
    - **SPR (Surface plasmon resonance)**: SPR is a phenomenon that occurs where electrons in a thin metal sheet become excited by light that is directed to the sheet with a particular angle of incidence, and then travel parallel to the sheet. Assuming a constant light source wavelength and that the metal sheet is thin, the angle of incidence that triggers SPR is related to the refractive index of the material and even a small change in the refractive index will cause SPR to not be observed. [[Biacore T200, Cytiva](https://www.cytivalifesciences.com/en/us/shop/protein-analysis/spr-label-free-analysis/spr-systems/biacore-t200-p-05644) | ]
    - **BLI (Bio-layer interferometry)**: [[ForteBio Octet 96e]()]


- **Protein identification**
    - Protein sequencing:
        - N-terminal sequencing (Edman degradation)：Step-by-step **N-terminal sequencing**, is a classic technique to analyze the N-terminal amino acid sequence of protein or polypeptide by chemical directional cleavage and identification. This technology was initiated by Swedish biochemist Pehr Edman in 1950, and was automated in 1967 (liquid-phase pulse sequencer) [[Source](https://www.creative-proteomics.com/resource/overview-edman-sequencing.htm)]
        - De novo sequencing based on MS
    - AP-MS: Affinity purification coupled with mass spectrometry (AP-MS) is a widely used approach for the identification of protein-protein interactions.
        - the contaminant repository for affinity purification (the CRAPome) [[Website](https://reprint-apms.org/)] 
    - Proximity labeling: APEX[]; TurboID[]; UltraID[]

- **Protein expression system**
    - E.coli: [BL21(DE3) strain + pET-28a+ vector | Rosetta(DE3) strain]
    - Yeast：[S. cerevisiae strain yMLT62 (J. Thorner lab) | yeast strain ySS025 ([ref.](https://pubmed.ncbi.nlm.nih.gov/37344598/)) | Pichia pastoris expression system] 
    - Sf21 insect cells: [[Bac-to-Bac Baculovirus Expression System (Life technologies)]() | [FastBac]() | [flashBAC]()]
    - Expi293F cells: Expi293F Cells are human cells derived from the 293F cell line, they are maintained in suspension culture and optimized to grow to high density in Expi293 Expression Medium. Expi293F Cells are highly transfectable and generate superior transient protein
yields compared to standard 293 cell lines. [Expi293 Expression Medium (Thermo Fisher Scientific) | [Expi293 Expression System User guide, PDF](https://documents.thermofisher.com/TFS-Assets/LSG/manuals/MAN0019402_Expi293_ExpressionSystem_3L_UG.pdf)]
      - Growth conditions: Suspension at 37℃, 8% CO2.
    - ExpiCHO-S cells: The Gibco [ExpiCHO Expression System](https://www.thermofisher.com/cz/en/home/life-science/protein-biology/protein-expression/mammalian-protein-expression/transient-mammalian-protein-expression/expicho-expression-system.html) brings together a high-expressing CHO cell line, a chemically-defined animal origin-free, serum-free, and protein-free culture medium, an optimized culture feed, and a high-efficiency transfection reagent that work in concert to provide protein titers 3x higher than the Gibco Expi293 Expression System and 160x higher than the Gibco FreeStyle CHO Expression System. [[User Guide, PDF](https://assets.thermofisher.com/TFS-Assets/LSG/manuals/MAN0014337_expicho_expression_system_UG.pdf)]
    
---
> We are seeing cells more and more clearly as chemical factories, where the various products are manufactured in separate workshops, the enzymes act[ing] as the overseers.\
--- Eduard Buchner (The Founder of Modern Biochemistry)

---
- **Organelle isolation**
    - **mitochondria**: Mito-IP []; Mito-IP tg mice
    - **Lysosome**: LysoIP [[PMID: 29074583](https://pubmed.ncbi.nlm.nih.gov/29074583/) | [Protocol](https://www.protocols.io/view/lysosome-immunopurification-lysoip-protocol-for-su-eq2lypy1rlx9/v1)] ; LysoIP tg mice (Rosa26;lox-stop-lox-TMEM192-3×HA) [[PMID: 36131016](https://pubmed.ncbi.nlm.nih.gov/36131016/)]
    - **ER**: ER-IP
    - **Golgi**: Golgi-IP [[PMID: 37155866](https://pubmed.ncbi.nlm.nih.gov/37155866/) | [Protocol](https://www.protocols.io/view/golgi-immunopurification-golgi-ip-for-subcellular-5qpvor3dbv4o/v1)]
    - **Synaptosome**: [A rapid Percoll gradient procedure, 2008, [DOI Link](https://doi.org/10.1038/nprot.2008.171)]     
    - **Postsynaptic density (PSD)**: [[DOI Link](https://link.springer.com/protocol/10.1007/978-1-61779-111-6_4)]
    

- **Cell culture basis**
    - ATCC® ANIMAL CELL CULTURE GUIDE (tips and techniques for continuous cell lines) [[PDF](https://www.atcc.org/-/media/resources/culture-guides/animal-cell-culture-guide.pdf)]
    - Cell Culture Basics Handbook [[PDF](https://assets.thermofisher.com/TFS-Assets/BID/Handbooks/gibco-cell-culture-basics-handbook.pdf)]
    - Guideline of Cell biology experiment, Part I (In Chinese, 细胞实验指南(上)) [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EeCUDsikGUFDtGqAy4-lErsBsKRz0Qn2T329ETyT0KjRzw?e=wTaHrr)]
    - Guideline of Cell biology experiment, Part II (In Chinese, 细胞实验指南(下)) [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/Ee5Qbs939yFMvdbCV3iSbD0BdbhidwjLXTkoyxSk9M6TmA?e=fAVeeC)]
    - Gibco Cell Culture Basics Handbook(In Chinese) [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EViSuQ_uP71Fqy3SHpHozhUBbA1xmaOYom-gIrwEW4-2sQ?e=UfLvlT)]
    - Primary neuron culture

    - Cell lines from ATCC library
| Name    | ATCC Catalog | Organism |  Description | 
| -------- | ------- |  ------- |   ------- |
| HEK293T  | [xxxx](https://www.atcc.org/products/crl-2266)    | Homo sapiens  |          |
| Hela  | [xxxx](https://www.atcc.org/products/crl-2266)    | Homo sapiens  |          |
| SH-SY5Y  | [CRL-2266](https://www.atcc.org/products/crl-2266)    | Homo sapiens  |          |
| U-2 OS | [HTB-96](https://www.atcc.org/products/htb-96)     |  Homo sapiens  |          |
| bEnd.3 [BEND3]   | [CRL-2299](https://www.atcc.org/products/crl-2299)    |  Mus musculus      |          |
| HUVEC   | [Lonza, CC-2519]()    |  Homo sapiens      |          |
| THP1   | [ATCC, TIB-202](https://www.atcc.org/products/tib-202)    |  Homo sapiens      | human leukemia monocytic cell line |

- **Transfection reagents**
    - **XtremeGene9**: Sigma
    - **PEI**: PEI MAX 40k (Polysciences)



- **Stable cell line generation**
    - Lenti-virus system



---
## Vendor companies
1. [Cell Signaling Technology](https://www.cellsignal.com/): We order antibodies in this company.
2. [Abcam](https://www.abcam.com/): We order antibodies in this company.
3. [ThermoFisher](https://www.thermofisher.cn/cn/zh/home/life-science/antibodies/primary-antibodies.html?icid=ab-search-primary-icons)
4. [R&D Systems](https://www.rndsystems.com/products)
5. [BioRad](https://www.bio-rad.com/)
6. [ATCC](https://www.atcc.org/cell-products/animal-cells): ATCC has the world's largest and most extensive product catalog of human and animal cell lines for research purposes.
7. [Gibco](https://www.thermofisher.cn/cn/zh/home/brands/gibco.html)
8. [Corning](https://www.corning.com/worldwide/en/products/life-sciences/products/media-sera-reagents.html)
9. [HyClone](https://www.cytivalifesciences.com/en/us/shop/cell-culture-and-fermentation/sera/fetal-bovine-serum/hyclone-defined-fetal-bovine-serum-fbs-u-s-origin-p-06090)
10. [Sigma](https://www.sigmaaldrich.cn/CN/zh)


---
## Ref. Labs

#### **Signaling pathways**
1. [Zhijian-James Chen lab, UTSW](https://www.james-zhijian-chen-lab.org/)
- **Discovery of cGAS-cGAMP pathway and its role in immune defense**
    - Sun, Lijun, et al. "Cyclic GMP-AMP synthase is a cytosolic DNA sensor that activates the type I interferon pathway." Science 339.6121 (2013): 786-791. [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EWZWjSjbymdFsI777Dv2EYsBAlzY_hKLXIg1JZQzN8XxeQ?e=y4CBrs) | [PMID: 23258413](https://pubmed.ncbi.nlm.nih.gov/23258413/) | [DOI Link](https://www.doi.org/10.1126/science.1232458)]
    - Wu, Jiaxi, et al. "Cyclic GMP-AMP is an endogenous second messenger in innate immune signaling by cytosolic DNA." Science 339.6121 (2013): 826-830. [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EcEtj2d-iKlGuWeCOcAUFisBiju-HRGaphC-v8jjZmznkA?e=SsslUO) | [DOI Link](https://www.doi.org/10.1126/science.1229963)]

- **Discovery of MAVS, a Mitochondrial Antiviral Signaling Adaptor Protein**
    - Seth, Rashu B., et al. "Identification and characterization of MAVS, a mitochondrial antiviral signaling protein that activates NF-κB and IRF3." Cell 122.5 (2005): 669-682. [[PDF](https://www.cell.com/action/showPdf?pii=S0092-8674%2805%2900816-0) | [PMID: 16125763](https://pubmed.ncbi.nlm.nih.gov/16125763/) | [DOI Link](https://doi.org/10.1016/j.cell.2005.08.012)]


2. [David M. Sabatini lab, WIBR, MIT; IOCB-Prague, Boston](https://www.davidmsabatini.com/)
- **The discovery of mTOR**
    - Sabatini et al. "RAFT1: a mammalian protein that binds to FKBP12 in a rapamycin-dependent fashion and is homologous to yeast TORs." Cell 78.1 (1994): 35-43. [[PDF]() | [DOI Link](https://doi.org/10.1016/0092-8674(94)90570-3)]
    - **iBiology Talk** [[PartI: Introduction to mTOR and the regulation of growth](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/Eb3JB4rNE2tMllUhPjex9CgBILDuE3oh47e37JY2pfzBlw?e=sUbxRS)]
    
- **Discovery and systematic characterization of basic mechanisms that regulate growth including nutrient sensing pathways** 
    - **Nutrient sensors**: [[CASTOR](https://doi.org/10.1016/j.cell.2016.02.035) | [Sestrin2](https://doi.org/10.1126/science.aad2087) | [SAMTOR](https://doi.org/10.1126/science.aao3265)]
    - **Nutrient sensing hub**: [[GATOR1]() | [GATOR2]() | [KICSTOR]()]
    - **iBiology Talks** [[PartII: Regulation of mTORC1 by nutrients](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/EXIwSNNwJgNAiO7RrVcJgtwBSTARmHylcl-SLXGBUIXDuQ?e=92ZqTV) | [PartIII: Ribophagy and nucleotide recycling](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/ESKOpuClGHFHn8BlERrknlwBHenie_CticrKRads96R1Mw?e=7d9oQA)]


3. [Xiaodong Wang lab](http://www.nibs.ac.cn/en/yjsjyimgshow.php?cid=5&sid=6&id=779), UTSW; NIBS
- **The discovery of mitochondria CytoC mediated apoptosis pathway**
    - Zou, Hua, et al. "Apaf-1, a human protein homologous to C. elegans CED-4, participates in cytochrome c–dependent activation of caspase-3." Cell 90.3 (1997): 405-413.
    [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/ERv446uXYcxCuPrmRHgWvgYBgN04_ogoRRKU8jTIB-WTEw?e=JvdhVY) | [PMID: 9267021](https://pubmed.ncbi.nlm.nih.gov/9267021/) | [DOI Link](https://doi.org/10.1016/s0092-8674(00)80501-2)]


2. [Kun-Liang Guan lab, UCSD, Westlake](https://pharmacology.ucsd.edu/faculty/department-faculty/kun-liang-guan.html)
- **Characterization of TSC2 as upstream negative regulator of mTORC1**
    -  Inoki, Ken, Tianqing Zhu, and Kun-Liang Guan. "TSC2 mediates cellular energy response to control cell growth and survival." Cell 115.5 (2003): 577-590. [[DOI Link](https://doi.org/10.1016/S0092-8674(03)00929-2)]

4. [Ronald David Vale lab](https://valelab.ucsf.edu/), University of California; San Francisco/HHMI
- **The discovery of Kinesin** [[iBiology Talk]()]
    - Vale, Ronald D., et al. "Direct observation of single kinesin molecules moving along microtubules." Nature 380.6573 (1996): 451-453. [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EW-o1QEOPyJEsgXt-_DClf8BveckhtoI-3VhkeYs7lROaw?e=8eRGFW) | [PMID: 8602245](https://pubmed.ncbi.nlm.nih.gov/8602245/) | [DOI Link](https://doi.org/10.1038/380451a0)]
    
- **The Characterization of Molecular Motor Proteins** [[iBiology Talk 1]() | [iBiology Talk 2]() | [iBiology Talk 3]()]  
    - Sablin, Elena P., et al. "Crystal structure of the motor domain of the kinesin-related motor ncd." Nature 380.6574 (1996): 555-559. [[PDF]() | [PMID: 8606780](https://pubmed.ncbi.nlm.nih.gov/8606780/) | [DOI Link]()]

5. [Vishva Dixit lab](https://www.gene.com/scientists/our-scientists/vishva-dixit), Genentech
- **Summary of all research and key publications** [[PDF](https://www.gene.com/assets/frontend/pdf/content/scientists/Vishva-Dixit_Past-Research_April-2021.pdf)]

- **Define a death receptor-induced apoptotic pathway**
    -  Tewari, Muneesh, and Vishva M. Dixit. "Fas-and tumor necrosis factor-induced apoptosis is inhibited by the poxvirus crmA gene product." Journal of Biological Chemistry 270.7 (1995): 3255-3260.
    
    - **key downstream executioner protease**: [YAMA/caspase-3]()
       -  Tewari, Muneesh, et al. "Yama/CPP32β, a mammalian homolog of CED-3, is a CrmA-inhibitable protease that cleaves the death substrate poly (ADP-ribose) polymerase." Cell 81.5 (1995): 801-809.
    
    - **FADD-caspase-8 pathway as the central apoptotic conduit used by all death receptors**: [[FADD]() | [FLICE/caspase-8]()]
       -  Pan, Guohua, et al. "The receptor for the cytotoxic ligand TRAIL." Science 276.5309 (1997): 111-113. [[PMID: 9082980](https://pubmed.ncbi.nlm.nih.gov/9082980/)]
    
    
- **The discovery and characterization of non-canonical Inflammasome pathway that responds to the presence of intracellular LPS independent of toll-like receptors** 
    -  Kayagaki, Nobuhiko, et al. "Non-canonical inflammasome activation targets caspase-11." Nature 479.7371 (2011): 117-121.  [[PMID:22002608](https://pubmed.ncbi.nlm.nih.gov/22002608/)]
    -  Kayagaki, Nobuhiko, et al. "Caspase-11 cleaves gasdermin D for non-canonical inflammasome signalling." Nature 526.7575 (2015): 666-671. [[PMID:26375259](https://pubmed.ncbi.nlm.nih.gov/26375259/)]

  

5. [Judy Lieberman, HMS](https://liebermanlab.wixsite.com/liebermanlab/)
- **The first to show that RNAi could be the basis for therapy in an animal model**


- **Identification of novel mechanisms of mitochondrial and DNA damage activated by granzyme A**
  

6. [Feng Shao lab, NIBS](http://www.nibs.ac.cn/en/yjsjyimgshow.php?cid=5&sid=6&id=777)
- **The discovery and characterization of GSDMD mediated pyroptosis pathway** [[Online Talk](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/ESMkgErwCLBJpX7uvSWuP2cBIi1aDrrquoFlQVkrOD3RKw?e=xocLlb)]
    - Shi, Jianjin, et al. "Cleavage of GSDMD by inflammatory caspases determines pyroptotic cell death." Nature 526.7575 (2015): 660-665. [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/ER85jPeKCyVIj24uQEX75W4BDUoOxtQY5Ap89wOXnDH6pw?e=8pOlMx) | [DOI Link](https://doi.org/10.1038/nature15514)]



7. [Veit Hornung Lab, LMU](https://www.genzentrum.uni-muenchen.de/research-groups/hornung/index.html)
- **The discovery and characterization of Nucleic acid sensors**


#### **Transcriptional regulation and epigenetics**
1. [Robert Tjian, University of California, Berkeley/HHMI](https://www.tjian-darzacq.mcb.berkeley.edu/tjian/)
- **The discovery of the SV40 large T antigen**
    - Tjian, Robert. "The binding site on SV40 DNA for a T antigen-related protein." Cell 13.1 (1978): 165-179. [[PMID: 202398](https://pubmed.ncbi.nlm.nih.gov/202398/) | [DOI Link](https://doi.org/10.1016/0092-8674(78)90147-2)]


2. [Yi Zhang lab, University of North Carolina at Chapel Hill/HMS/HHMI](https://www.zhanglab.tch.harvard.edu/)


3. [Yang Shi lab, HMS/HHMI/University of Oxford](https://www.harvardshilab.org/)
- **The discovery of first histone demethylase, LSD1** 
    - Shi, Yujiang, et al. "Histone demethylation mediated by the nuclear amine oxidase homolog LSD1." Cell 119.7 (2004): 941-953. [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EYPS2hk_U1VCm-bMyCGIu-QBg92LUK47Nw4J3vIEapyRCQ?e=EF25wj) | [DOI Link](https://doi.org/10.1016/j.cell.2004.12.012)]


4. [Chuan He lab, University of Chicago/HHMI](https://he-group.uchicago.edu/He%20research.html)
- **The discovery of first RNA demethylase that oxidatively reverses N6-methyladenosine (m6A) methylation in mammalian messenger RNA**
    - Jia, Guifang, et al. "N6-methyladenosine in nuclear RNA is a major substrate of the obesity-associated FTO." Nature chemical biology 7.12 (2011): 885-887. [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/ETNp772T_4VNnY3909X_7lUB_8CJ36WsacqULe7ApUAzSA?e=QWFN4P) | [DOI Link](https://doi.org/10.1038/nchembio.687)]





#### Ref. softwares
1. [PyMOL](https://pymol.org/2/): PyMOL is a user-sponsored molecular visualization system on an open-source foundation, maintained and distributed by Schrödinger.
2. [UCSF ChimeraX](https://www.rbvi.ucsf.edu/chimerax/): UCSF ChimeraX (or simply ChimeraX) is the next-generation molecular visualization program from the Resource for Biocomputing, Visualization, and Informatics (RBVI), following UCSF Chimera.
3. [HMMER](https://www.ebi.ac.uk/Tools/hmmer/): HMMER is a software package that provides tools for making
probabilistic models of protein and DNA sequence domain families –
called profile hidden Markov models, profile HMMs, or just profiles
– and for using these profiles to annotate new sequences, to search
sequence databases for additional homologs, and to make deep multiple sequence alignments. 
    - HMMER underlies several comprehensive collections of alignments and profiles of known protein and DNA
sequence domain families, including the Pfam database. [[User's Guide](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/Ed04ig0fcPFFumd5FpDwVrwBBOoMKw654YqCW22tYm2WDA?e=04v42b)]
4. [Pfam 35.0](http://pfam.xfam.org/)
    - The Pfam database is a large collection of protein families, each represented by multiple sequence alignments and hidden Markov models (HMMs).
    - Pfam 35.0 contains a total of 19,632 families and clans.
5. [Proteome-pI](http://isoelectricpointdb.org/index.html): Database of pre-computed isoelectric points for proteomes from different model organisms ([5029 species](http://isoelectricpointdb.org/statistics.html)).


#### **Tool development**
1. [Alice Ting lab, Stanford](http://www.tinglab.org/)
- **PROXIMITY LABELING**
    - APEX
    - TurboID
    - LOV-Turbo: Light-regulated TurboID
- Stanford Neuro-omics Initiative, 2020 Virtual Workshop
    - **"Proteomics and proximity labeling in neuroscience”**, by Alice Ting [[YouTube video](https://youtu.be/IX8v1EX6k9E) | [Slides](https://www.tinglab.org/s/Ting-proximity-labeling)]
    - **“Design and execution of proximity labeling experiments”**, by Tess Branon [[YouTube video](https://youtu.be/_EZ-A-_GeWE) |  [Slides](https://www.tinglab.org/s/Branon-proximitylabeling)]
    - **“Analysis of proximity labeling data”**, by Shuo Han [[YouTube video](https://youtu.be/sKLj_uxqMUE) | [Slides](https://www.tinglab.org/s/Han-proximitylabeling.pdf)]



---
### Ref. Protocols
1. [Bio-protocol](https://cn.bio-protocol.org/cn/default.aspx)
2. [Protocol Exchange](https://protocolexchange.researchsquare.com/)




---
## Nobel laureates
![nobelxqhemox](/img/nobel_prize.jpg)
---

- **Carolyn Bertozzi**, Stanford University, Stanford, CA, USA; Howard Hughes Medical Institute, USA [[lab link](https://bertozzigroup.stanford.edu/research)]\
The Nobel Prize in Chemistry 2022\
**The Bioorthogonal Chemistry Journey, from Laboratory to Life** [[Nobel Lecture video](https://youtu.be/pgIzEf_RfII) | [Lecture Slides]() | [Read the Lecture]() | [Source](https://www.nobelprize.org/prizes/chemistry/2022/bertozzi/facts/)]
   - iBiology Talk[[PartII: Imaging the glycome](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/EY_HgB0cTHNDsXnohVjQeA4BIsfayV86bt3g40XGvpFEPA?e=7xJwMx)]
---

- **Sir Peter J. Ratcliffe**, University of Oxford, Oxford, United Kingdom; Francis Crick Institute, London, United Kingdom\
The Nobel Prize in Physiology or Medicine 2019\
**Elucidation of Oxygen Sensing Mechanisms in Human and Animal Cells** [[Nobel Lecture video](https://www.youtube.com/watch?v=-Q0OGLCzKEE&ab_channel=NobelPrize) | [Lecture Slides](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EXOiww-BbPVPk0ylchpMitcBK5MC0hqaj_dZfUS6TWHarw?e=WoVdIG) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EVUxJoGlhiRJgtrbPqSTru0Blv3QBO-62yoz7SBpmWC27Q?e=xbjTH6) | [Source](https://www.nobelprize.org/prizes/medicine/2019/ratcliffe/facts/)]

- **William G. Kaelin Jr**, Harvard Medical School, Boston, MA, USA; Howard Hughes Medical Institute, Chevy Chase, MD, USA; Dana-Farber Cancer Institute, Boston, MA, USA; Brigham and Women's Hospital, Boston, MA, USA
The Nobel Prize in Physiology or Medicine 2019\
**The von Hippel-Lindau Tumor Suppressor Gene: Insights into Oxygen Sensing and Cancer** [[Nobel Lecture video](https://www.youtube.com/watch?v=-Q0OGLCzKEE&ab_channel=NobelPrize) | [Lecture Slides](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/Ed26wXIWXDpImtuMAPsOucsBrHS2hzA9eGG0lF-_5vqCuA?e=kBHsWg) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/Ecvul5W3ggdPp5i5XkVZ-iwByfWLcklqBqlZTOwLhRJAkg?e=PMc1RQ) | [Source](https://www.nobelprize.org/prizes/medicine/2019/kaelin/facts/)]

- **Gregg L. Semenza**, Johns Hopkins University, Baltimore, MD, USA
The Nobel Prize in Physiology or Medicine 2019\
**Hypoxia-Inducible Factors in Physiology and Medicine** [[Nobel Lecture video](https://www.youtube.com/watch?v=B_KBgSXUWoM&ab_channel=NobelPrize) | [Lecture Slides](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/ESNkopdpfo1Hg4snunzkMBcB1tf8zbRYfc1SPzC7SIElHw?e=iCgGHX) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/Efl45HbMeoVFlKFDaQ3nlrEBpioqP1dJAdmLpltUt8RqSw?e=8BU3qs) | [Source](https://www.nobelprize.org/prizes/medicine/2019/semenza/facts/)]
---

- **James P. Allison**, University of Texas MD Anderson Cancer Center, Houston, TX, USA
The Nobel Prize in Physiology or Medicine 2018\
**Immune Checkpoint Blockade in Cancer Therapy**  [[Nobel Lecture video](https://youtu.be/0kuh7G9CP9Y) | [Lecture Slides](https://www.nobelprize.org/uploads/2018/10/allison-lecture-slides.pdf) | [Read the Lecture](https://www.nobelprize.org/uploads/2018/10/allison-lecture.pdf) | [Source](https://www.nobelprize.org/prizes/medicine/2018/allison/facts/)]

- **Tasuku Honjo**, Kyoto University, Kyoto, Japan
The Nobel Prize in Physiology or Medicine 2018\
**Serendipities of Acquired Immunity**  [[Nobel Lecture video](https://youtu.be/9gx05bZIMc8) | [Lecture Slides](https://www.nobelprize.org/uploads/2018/10/honjo-slides.pdf) | [Read the Lecture](https://www.nobelprize.org/uploads/2018/10/honjo-lecture.pdf) | [Source](https://www.nobelprize.org/prizes/medicine/2018/honjo/facts/)]
---


- **James E. Rothman**, Yale University, New Haven, CT, USA
The Nobel Prize in Physiology or Medicine 2013\
**The Principle of Membrane Fusion in the Cell**  [[Nobel Lecture video](https://nobel-videocdn01.azureedge.net/video/lecture_2013_med_rothman_01_496.mp4) | [Lecture Slides](https://www.nobelprize.org/uploads/2018/10/honjo-slides.pdf) | [Read the Lecture](https://www.nobelprize.org/uploads/2018/06/rothman-lecture-slides.pdf) | [Source](https://www.nobelprize.org/prizes/medicine/2013/rothman/facts/)]
---


- **Thomas A. Steitz**, Yale University, New Haven, CT, USA/HHMI\
The Nobel Prize in Chemistry 2009\
**From the Structure and Function of the Ribosome to New Antibiotics** [[[Nobel Lecture video](https://nobel-videocdn01.azureedge.net/video/lecture_2013_med_sudhof_01_496.mp4) | [Lecture Slides](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EVXBnv0u4ZFJhYQn8GDptrsB_h1rjWytyIgA-_jGlJnp0A?e=9GGhT9) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EfciowG7i0xGkkbCawrXBYIBjfGg34AWPzRkUY9QjXxa0w?e=37F7SE) | [Source](https://www.nobelprize.org/prizes/chemistry/2006/kornberg/facts/)]

---

- **Roger D. Kornberg (1947-)**, Stanford University, Stanford, CA, USA\
The Nobel Prize in Chemistry 2006\
**The Molecular Basis of Eukaryotic Transcription** [[[Nobel Lecture video](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/ERw7C9PRlohLhRtknICEV7MBBSPm_2mWVIesmDVd2YOG4A?e=hF2pWW) | [Lecture Slides](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/ESyDWhQ3fdVKgUJCgAx60r0B_CtmOIHrlltak3g1vOG7IQ?e=I34sDq) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EZT0GvMQveJMq-ixnGwABJUBS-5i5dHmP0wara5wRomYgA?e=3BsqbQ) | [Source](https://www.nobelprize.org/prizes/chemistry/2006/kornberg/facts/)]
---

- **Aaron Ciechanover (1947-)**, Technion - Israel Institute of Technology, Haifa, Israel\
The Nobel Prize in Chemistry 2004\
**Intracellular Protein Degradation: From a Vague Idea thru the Lysosome and the Ubiquitin-Proteasome System and onto Human Diseases and Drug Targeting** [[[Nobel Lecture video](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/ERdlJ9rdPcFJv_R1mJut84kBUPLMOWBZXB7qbeCeSX5ryw?e=gqwpxE) | [Lecture Slides](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EYYwKnERfjlNlR8M2dUaBRkBRtKflup1lcj0mwyKSRIDGw?e=F7p9qz) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EU43Ls9wC8hElhPZYmT6Mw4BqaFkBXTstZ0pMxcKkRDlcw?e=radGHz) | [Source](https://www.nobelprize.org/prizes/chemistry/2004/ciechanover/facts/)]

- **Avram Hershko (1937-)**, Technion - Israel Institute of Technology, Haifa, Israel\
The Nobel Prize in Chemistry 2004\
**The Ubiquitin System for Protein Degradation and some of its Roles in the Control of the Cell Division Cycle** [[[Nobel Lecture video](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/ERK-w8_ezhdIgvzoRmAUiZYBP7U646FMYt5MwzffiOdsBg?e=1cjjXH) | [Lecture Slides](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EU8HK0tUDq5GvbVsQQO0y2sBBhjvde1SrnZ-7spfFiXV-Q?e=KJ6WG5) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EXSPPRnxcpZHhY4P0UAcdkEB8Bbl08QCMFZvLS5EGsUVng?e=fUDQcO) | [Source](https://www.nobelprize.org/prizes/chemistry/2004/hershko/facts/)]

- **Irwin Rose (1926-2015)**, University of California, Irvine, CA, USA\
The Nobel Prize in Chemistry 2004\
**Ubiquitin at Fox Chase** [[[Nobel Lecture video](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/ET4_5AecXu9Cnf0uM19F4JsBS9IZDC6c5ICFlR0vH87a4g?e=siEias) | [Lecture Slides](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EXbdZe1w5q9BkWFcrk386rQBAxL3Vs5s6363DWlxUCbwgA?e=jSkAIL) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/ETFDWhuZpgpKskP64kZaOyQBuQdyyA_dyO4bLO0hdcZvAQ?e=7iQmn9) | [Source](https://www.nobelprize.org/prizes/chemistry/2004/rose/biographical/)]
---

- **H. Robert Horvitz**, Massachusetts Institute of Technology (MIT), Cambridge, MA, USA\
The Nobel Prize in Physiology or Medicine 2002\
**Worms, Life and Death** [[[Nobel Lecture video](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/Edz6rFf7FmtJteWPeePhxjgBhAtSiVuQX9XdoQGiqVDNaQ?e=KdycuD) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EVzIhKgJj6xDgC4LL7wqVQYB5VlRdjc9c7HjDpTwXgkzeA?e=rOGuuX) | [Source](https://www.nobelprize.org/prizes/medicine/2002/horvitz/facts/)]

- **John E. Sulston**, The Wellcome Trust Sanger Institute, Cambridge, United Kingdom\
The Nobel Prize in Physiology or Medicine 2002\
**C. elegans: The Cell Lineage and Beyond** [[[Nobel Lecture video](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/EQyBLGKYDXhIplo0bRLbZHIBuxKwPpICJlWsDYRL8D4Gug?e=MOfPPp) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EUf4LzKYM2xKmoI5ZQzCK70Bn8zIdWvG-LCJOXsS7Gw3Qw?e=malH66) | [Source](https://www.nobelprize.org/prizes/medicine/2002/sulston/facts/)]

- **Tim Hunt**, Imperial Cancer Research Fund, London, United Kingdom\
The Nobel Prize in Physiology or Medicine 2001\
**Protein Synthesis, Proteolysis, and Cell Cycle Transitions** [[Nobel Lecture video](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/EaOQ-Mm3pGdHlV4I8wW2TekBDyip0iCCG2VWo9Z7L7YVRQ?e=qDd7zC) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EUJnTxOTUVVOny_JXNJ3CQ8BrtlQv39qjtxkry_heWS9QQ?e=ZJHRVY) | [Source](https://www.nobelprize.org/prizes/medicine/2001/hunt/facts/) | [Careers interview](https://www.science.org/content/article/tim-hunt)]



- **Günter Blobel (1936-2018)**, Rockefeller University, New York, NY, USA/HHMI\
The Nobel Prize in Physiology or Medicine 1999\
**Protein Targeting** [[Nobel Lecture video](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/ESIeTdXeQhFPucU3U8wRnlkBaeewC7fpnxh2NOxfFOCWDA?e=mukBY1) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EZg3NWI41VJLrNYH7fBjeL8BwVR1OmqLCva5QVreNa3kHQ?e=98dUsD) | [Source](https://www.nobelprize.org/prizes/medicine/1999/blobel/facts/)]

- **Jens C. Skou (1918-2018)**, Aarhus University, Aarhus, Denmark\
The Nobel Prize in Chemistry 1997\
**The Identification of the Sodium-Potassium Pump** [[Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EcDHAa8liqBKhX4MwJ47m5MB7e7ODpl1miBXGyDt-s5qTg?e=IKeiXx) | [Source](https://www.nobelprize.org/prizes/chemistry/1997/skou/facts/)]

- **Michael S. Brown**, University of Texas Southwestern Medical Center at Dallas, Dallas, TX, USA\
The Nobel Prize in Physiology or Medicine 1985\
**A Receptor-Mediated Pathway for Cholesterol Homeostasis** [[Nobel Lecture video](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/ETg1Cn8l9r5Nj6NUpUAt3iYBZKY4AfGd0lL1CirTvb9w3Q?e=Jb7DDk) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EduKqW6S50lIpdOiDIeUARwBwcCJ5t39vVj_KSqBozGVPw?e=IezFd8) | [Source](https://www.nobelprize.org/prizes/medicine/1985/brown/facts/)]

- **Joseph L. Goldstein**, University of Texas Southwestern Medical Center at Dallas, Dallas, TX, USA\
The Nobel Prize in Physiology or Medicine 1985\
**A Receptor-Mediated Pathway for Cholesterol Homeostasis** [[Nobel Lecture video](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/EVutn3EsSJ1HqNxaasJhoyAB1zOSUp0fnA-22pIXkxSVBg?e=KWa8bN) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EV1QI23lnYJEsidk8PwsdkUBHwujaCAxk-IZn7-CJBKRjg?e=PvKRA5) | [Source](https://www.nobelprize.org/prizes/medicine/1985/goldstein/facts/)]

- **David Baltimore (1938-2025)**, Massachusetts Institute of Technology (MIT), Cambridge, MA, USA\
The Nobel Prize in Physiology or Medicine 1975\
**Viruses, Polymerases and Cancer** [[Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/ESnrenbCZZlAhI2JPh5t-x8B3X7SnCYq7xw02oP8GmjCeQ?e=IfvLqf) | [Source](https://www.nobelprize.org/prizes/medicine/1975/baltimore/facts/)]


- **Christian de Duve (1917-2013)**, Rockefeller University, New York, NY, USA, Université Catholique de Louvain, Louvain, Belgium\
The Nobel Prize in Physiology or Medicine 1974\
**Exploring Cells with a Centrifuge** [[Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EdOinoSbtxVIi-cwGU-QE7gBFMjIvlVwC0bnRyqJVN9Emw?e=5KkvhL) | [Source](https://www.nobelprize.org/prizes/medicine/1974/duve/facts/)]


- **Arthur Kornberg (1918-2007)**, Stanford University, Stanford, CA, USA\
The Nobel Prize in Physiology or Medicine 1959\
**The Biologic Synthesis of Deoxyribonucleic Acid** [[Read the Lecture](https://www.nobelprize.org/uploads/2018/06/kornberg-lecture.pdf) | [Source](https://www.nobelprize.org/prizes/medicine/1959/kornberg/facts/)]


- **Severo Ochoa (1905-1993)**, New York University, College of Medicine, New York, NY, USA\
The Nobel Prize in Physiology or Medicine 1959\
**Enzymatic Synthesis of Ribonucleic Acid** [[Read the Lecture](https://www.nobelprize.org/uploads/2018/06/ochoa-lecture.pdf) | [Source](https://www.nobelprize.org/prizes/medicine/1959/ochoa/facts/)]


- **Hans Adolf Krebs (1900-1981)**, Sheffield University, Sheffield, United Kingdom\
The Nobel Prize in Physiology or Medicine 1953\
**The Citric Acid Cycle** [[Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EVxi0wW7-IJJnjzqliHeFh8BGW0h1b8LObZyfqK-HVpA2Q?e=s3Ecby) | [Source](https://www.nobelprize.org/prizes/medicine/1953/krebs/facts/)]


- **Fritz Albert Lipmann (1899-1986)**, Harvard Medical School, Boston, MA, USA, Massachusetts General Hospital, Boston, MA, USA\
The Nobel Prize in Physiology or Medicine 1953\
**Development of the Acetylation Problem: A Personal Account** [[Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EbCWJp6BlQ1EoXr9K9pupjoBSnpvv2RM_Sd_vccz32xDjg?e=YmE34g) | [Source](https://www.nobelprize.org/prizes/medicine/1953/lipmann/facts/)]


- **Otto Heinrich Warburg (1883-1970)**, Kaiser-Wilhelm-Institut (now Max-Planck-Institut) für Biologie, Berlin-Dahlem, Germany\
The Nobel Prize in Physiology or Medicine 1931\
**The Oxygen-Transferring Ferment of Respiration** [[Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/ES4ZiJYfJ5ZCpQUBKCcgw78BmrgsbyYZ8pMmFbX3UxdyRQ?e=kPiQzd) | [Source](https://www.nobelprize.org/prizes/medicine/1931/warburg/facts/)]


- **Eduard Buchner (1860-1917)**, Landwirtschaftliche Hochschule (Agricultural College), Berlin, Germany\
The Nobel Prize in Chemistry 1907\
**for his biochemical researches and his discovery of cell-free fermentation** [[Read the Lecture](https://www.nobelprize.org/uploads/2018/06/buchner-lecture.pdf) | [Source](https://www.nobelprize.org/prizes/chemistry/1907/buchner/facts/)]
> We must never let ourselves fall into thinking "ignorabimus" ("We shall never know"), but must have every confidence that the day will dawn when even those processes of life which are still a puzzle today will cease to be inaccessible to us natural scientists.\
--- Eduard Buchner (December 11, 1907)
