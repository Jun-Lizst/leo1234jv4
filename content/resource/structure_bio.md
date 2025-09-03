---
title: "Structure Biology"
date: 2022-08-21T13:24:59+08:00
categories:
- category
- subcategory
tags:
- CryoEM
- X-Ray
- Protein purification
keywords:
- tech
comments:       false
showMeta:       false
showActions:    false
thumbnailImage: /img/7uhy_GATOR2.jpeg
thumbnailImagePosition: left
#thumbnailImage: //example.com/image.jpg
---



---
# CryoEM Single Particle Analysis (SPA)


1. **Cryo-EM microscopy**
    - [300 kV Titan Krios](https://www.thermofisher.com/cz/en/home/electron-microscopy/products/transmission-electron-microscopes/krios-cryo-tem/features.html)
    - **Glacios**: The Glacios from Thermo Fisher Scientific is a 200 kV transmission electron microscope with a two-condenser lens system.

### **| Sample preparation** 
1. **Methods to improve particle behavior**
    - **Size exclusion chromatography**: Gel filtration can be a powerful tool to predict structural heterogeneity. Whenever possible, gel filtration should be incorporated to the final steps of a purification protocol.
    - **Protein or protein complex stabilization**: If negative stain or cryo-EM analysis reveals significant structural heterogeneity, then the user may consider additional methods to stabilize a structural target in a defined conformation. These approaches have proven to be effective in trapping conformationally variable proteins and complexes in energetic minima that allow high-resolution structure determination. Examples include using small molecule inhibitors, non-hydrolyzable nucleotides (if applicable), Fab antibody fragments, or genetic perturbations (e.g., mutating catalytic residues).
    - **Chemical crosslinking**: One common way to counteract structural heterogeneity is to chemically crosslink the purified sample, such as with glutaraldehyde or BS3. However, crosslinked samples run a risk of producing structural artifacts and this approach should therefore be considered only after a control, non-crosslinked sample has been evaluated.
    - **Membrane proteins**:
      - **Isolation of membrane fractions**: 100,000 g
      - **Screen of Detergents**: [CHAPS | Digitonin | 1% DDM + 0.2% CHS | 2% (w/v) GDN + 0.1% (w/v) CHS + 0.2 mg/ml Avanti | 0.5% LMNG + 0.03% CHS]
      - **Affinity Chromatography (AC)**: [anti-FLAG | Strep-Tactin XT]
      - **Crosslinking for membrane protein complex**: 0.1% (v/v) , 40 mins
      - **SEC**: [[Superose 6 increase 10/300] | [Superdex 200 increase 10/300]]
      

2. **Protocol for grid preparation**
    - From Negative stain TEM: [[Protocol, PDF](https://cryoem.wisc.edu/wp-content/uploads/sites/341/2021/01/Negative_Stain_Grid_Preparation_21Jan2021.pdf) | [Yifan Cheng lab, 2011](https://www.ncbi.nlm.nih.gov/pubmed/22215030)]
    
    - Graphene type \
     --- [Monolayer graphene](https://www.biorxiv.org/node/981810.full) \
     --- [Graphene oxide](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6119484/) \
     --- [Functionalized graphene](https://www.pnas.org/content/116/24/11718) \
     --- [Functionalized graphene oxide](https://www.biorxiv.org/content/10.1101/657411v1.full)
    - Plasma cleaner for glow discharge
    

3. **Sample Vitrification**: Vitrification is the rapid cooling of a liquid into a solid, glass-like amorphous state, preventing the formation of damaging ice crystals. 
    - [**EM GP2, Leica**](https://www.leica-microsystems.com/products/sample-preparation-for-electron-microscopy/p/leica-em-gp2/): The EM GP2 from Leica Microsystems is an automated plunge freezer able to vitrify thin samples applied to an electron microscopy grid after removing excess fluid by blotting. [[Tutorial video, mp4](https://bioem.shanghaitech.edu.cn/_upload/article/videos/d8/77/91cf34504384919c5e5787c54f07/666c8301-1b09-43d0-9472-1d00f5dbe414-B.mp4) | [Manual, PDF](https://bioem.shanghaitech.edu.cn/_upload/article/files/79/11/d357319b47e584a520a8bbd06351/883df0db-6349-4fca-9686-a4a8107152e6.pdf)]

    - **Vitrobot, Thermo Fisher**: The Vitrobot Mark IV System from Thermo Fisher Scientific is an automated plunge freezer able to vitrify thin samples applied to an electron microscopy grid after removing excess fluid by blotting. [[Tutorial video, mp4](https://bioem.shanghaitech.edu.cn/_upload/article/videos/a4/8e/d17c5c5e4d858b49938c682dca00/b9546e76-893f-4b41-bc9d-d3b4b6244c48-B.mp4) | [Manual, PDF](https://bioem.shanghaitech.edu.cn/_upload/article/files/79/11/d357319b47e584a520a8bbd06351/0ac79af7-f4bc-45ff-9fcf-0cf3f357e656.pdf)]
    - Preassis    
    - CryoSol Vitrojet System



### **| Cryo-EM data analysis**
#### Softwares
1. [CryoSPARC](https://guide.cryosparc.com/): CryoSPARC (Cryo-EM Single Particle Ab-Initio Reconstruction and Classification) is a state of the art data analysis solution for single-particle analysis (SPA) in cryo-electron microscopy (cryo-EM). CryoSPARC is used to reconstruct and visualize cryo-EM structures of biological targets including membrane proteins, viruses and complexes.
2. [Relion](https://relion.readthedocs.io/en/release-5.0/): relion (for REgularised LIkelihood OptimisatioN, pronounce rely-on) is a software package that employs an empirical Bayesian approach for electron cryo-microscopy (cryo-EM) structure determination. It is developed in the group of Sjors Scheres at the [MRC Laboratory of Molecular Biology](https://www2.mrc-lmb.cam.ac.uk/).
3. [SPIDER](https://github.com/spider-em/SPIDER):
    - [Online tutorial](https://spider-em.github.io/SPIDER/)

4. [COOT](https://www2.mrc-lmb.cam.ac.uk/personal/pemsley/coot/): For manually rebuilt and/or adjust models.
    - Emsley, Paul, and Kevin Cowtan. "Coot: model-building tools for molecular graphics." Biological crystallography 60.12 (2004): 2126-2132. [[PMID: 15572765](https://pubmed.ncbi.nlm.nih.gov/15572765/)]
    
5. [Phenix](https://phenix-online.org/): For Real space and Rosetta refinements.
    - Adams, Paul D., et al. "PHENIX: a comprehensive Python-based system for macromolecular structure solution." Biological crystallography 66.2 (2010): 213-221. [[PMID: 20124702](https://pubmed.ncbi.nlm.nih.gov/20124702/)]
    
6. [Requirement of computational cluster/Workstation](https://guide.cryosparc.com/setup-configuration-and-management/hardware-and-system-requirements):
    - **CPU:** 32 Cores (base clock 2.8GHz+), e.g, AMD Threadripper 3975X
    - **RAM:** 256GB DDR4 @ 3200MHz
    - **Storage:** 4TB PCIe SSD (cache); 200TB RAID 6 storage server via 10Gbps link (raw movies)
    - **GPU:** 4x NVIDIA Quadro GV100, or 4x NVIDIA Tesla V100 or 4x NVIDIA RTX 8000



#### Deep learning tools

**Ref softwares**:
1. **MotionCorr**: This program corrects whole frame image motion recordded with dose fractionated image stack. [MotionCor2](https://emcore.ucsf.edu/ucsf-motioncor2)
    - Xueming Li, Paul Mooney, Shawn Zheng, Chris Booth, Michael B. Braunfeld, Sander Gubbens, David A. Agard and Yifan Cheng (2013) Electron counting and beam-induced motion correction enables near atomic resolution single particle cryoEM. Nature Methods, 10, 584-590. PMID: 23644547 
2. **GeFREALIGN**: FREALIGN is a program developed by Niko Grigorieff laboratory for high-resolution refinement of 3D reconstruction from cryoEM of single particles. 
    - Xueming Li, Nikolaus Grigorieff and Yifan Cheng (2010) GPU-enabled FREALIGN: Accelerating single particle 3D reconstruction and refinement in Fourier space on graphics processors. Journal of Structural Biology, advanced publication online June 14 2010. PMID: 20558298



#### Online resources
1. [**CryoEM 101**](https://cryoem101.org/)
2. [Cryo-EM University](https://www.thermofisher.com/cz/en/home/electron-microscopy/life-sciences/learning-center/cryo-em-university.html): Cryo-EM University features over 70 hours of theoretical lectures and videos. Created in collaboration with online education expert Professor Grant Jensen, it serves as an introduction to the field and is intended for participants of all levels. Upon completion, you will have a fundamental knowledge of cryo-EM, tips and tricks to overcome sample preparation challenges, and valuable practical advice on the cryo-EM workflow.




#### Service Centers: 
1. [The UW-Madison Cryo-Electron Microscopy Research Center (CEMRC), University of Wisconsin-Madison](https://cryoem.wisc.edu/)


1. [Bio-Electron Microscopy Facility, Shanghai Tech University](https://bioem.shanghaitech.edu.cn/7390/list.htm)



#### Vendor companies
1. [Thermo Scientific](https://www.thermofisher.com/us/en/home/electron-microscopy/products/sample-preparation-equipment-em/vitrobot/instruments/vitrobot-mark-iv.html)
2. [Shuimu Bioscience](https://shuimubio.com/about): Shuimu is a rapidly evolving global cryo-EM & AI platform dedicated to early drug discovery. Equipped with 8 state-of-the-art 300kV cryo-EM instruments, Shuimu drives innovation to accelerate the development of groundbreaking drugs.
3. [Leica](https://www.leica-microsystems.com/products/sample-preparation-for-electron-microscopy/p/leica-em-gp2/app/)
4. [SPT Labtech](https://cryowrite.ch/)
5. [cryoWrite](https://support.shimadzu.com.cn/an/resource/index.html#105)
6. [CryoSol](https://cryosol-world.com/vitrojet-solutions/technology/)





### Ref labs: 
1. [Yifan Cheng Lab, UCSF](https://cryoem.ucsf.edu/)
- **Atomic structures of TRPV1**: With David Julius’s laboratory at UCSF [Liao, et al. 2016, Nature | Cao et al. 2013, Nature | Gao et al. 2016, Nature]
- **iBiology Talks**: [[Part 1: Single Particle Cryo-EM](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/EfUivsENbh5Gj8E10GGp0KEBynIVfURLM06aJ4xv6Y3XxQ?e=I8Ahs5) | [Part 2: Single particle Cyro-EM of membrane proteins](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/EXRwR0JzrnBOoKHcQUQvjNMB5kaISskZMilMzXJFH2FAAw?e=05Bk8U)]

2. [Niko Grigorieff Lab](https://grigoriefflab.umassmed.edu/research_interests)

3. [Grant Jensen Lab, Caltech](https://jensenlab.caltech.edu/)
- **Course**: [“Getting Started in Cryo-EM”](https://cryo-em-course.caltech.edu/unit-1-outline)
    - Part 1: Currents, coils, knobs and names: Basic anatomy of the electron microscope [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/Efnw9H9kQwJAofudECHPDx4BMdMTU8d3jnUXn_azQBxEJQ?e=uAgYIL)]
    - Part 2: Fourier transforms and reciprocal space for beginners [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EQ-oIS9Yk7RGlqvf08WdC-QBT99tJ16X4OvHbVl9T5E_lQ?e=dnQFtD)]
    - Part 3: Image formation [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/ERImtLbXQxlNokWvDjq5fy4BnvdxCzDRxq57QySSTyy-8Q?e=Nc09nz)]
    - Part 4: Fundamental challenges in biological EM [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EZlN7ooM88xIkP2RPzrPj8MByqRvauoFSaF5-aHZsefRlA?e=sLCZHP)]
    - Part 5: Tomography [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EWfU4XfSAclLtLgYmv03_8MBeR8cDnqgOVFlQDCUqMikkA?e=JGdF04)]
    - Part 6: Single-particle analysis [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EbhLC2uJvGFGhHV2UEnibG0BCTDZaas8XJVuTgZf-MD8vw?e=hgCiGb)]
    - Part 7: 2-D crystallography [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/Edo3stS6v9hCrD7fTZ-Gx-cBHfhmwsP_y9zOurIfAVz3xg?e=iBYBXl)]


4. [Yigong Shi lab, Princeton University/Tsinghua University/Westlake University](https://ygshi.org/)
- **Structural basis of pre-mRNA splicing**
    - Yeast system
- **Structural basis of Apoptosis (Programmed Cell Death)**
- **Alzheimer's Disease (AD) and Regulated Intramembrane Proteolysis (RIP)**

5. [Michael P. Rout lab, The Rockefeller University](https://routlab.rockefeller.edu/)
- **Structure, Mechanism and Evolution of the Nuclear Pore Complex**
    - Review: [Rout & Aitchison, 2001](https://routlab.rockefeller.edu/wp-content/uploads/2023/02/23_2001_JBC_Rout_Aitchison.pdf)
    - Yeast system [[]()|]

6. [Hao Wu lab, Harvard Medical School](https://www.wulab.tch.harvard.edu/)
- **The discoverer of signalosomes**, which are large macromolecular complexes involved in cell death and in innate and adaptive immune pathways.
    - Wu, Hao. "Higher-order assemblies in a new paradigm of signal transduction." Cell 153.2 (2013): 287-292. [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/ES4S-RQx0FFEsL1XMYEsweQBeAjiV5qHw0yrYIDRkcZmMQ?e=8L9mMo) | [DOI Link](https://doi.org/10.1016/j.cell.2013.03.013)]

7. [Nieng Yan lab, Tsinghua University/Princeton University/ShenZhen Medical Institute](https://scholar.princeton.edu/yanlab)
- **Structural basis of Membrane transport**
    - human GLUT1
- **Structural and mechanistic investigation of sterol homeostasis**







---
# X-ray crystallography




### Vendor companies




### Ref. Labs





---
# NMR








---
### Ref. Labs
1. [Chun Tang Lab](http://tanglab.cn/about.html), Peking University
    
    



---
# Structural Proteomics






## Ref. Labs
1. [Mass Spectrometry of Biopolymers (BioMS), Core facility, IOCB-Prague](https://msbiopolymers.group.uochb.cz/en)
  - **HDX-MS:** Hydrogen-Deuterium Exchange Mass Spectrometry (HDX-MS) is a structural proteomics method based on a chemical reaction that allows the exchange of covalently bound hydrogen atoms for deuterium from the solution. This exchange occurs under physiological conditions, and its rate depends on the local secondary structure of proteins. By performing a differential experiment under different conditions, it is possible to track the rate of exchange at the peptide level to localize structural changes on proteins due to the binding of ligand (identification of the binding site), another protein (identification of the interaction interface), or due to changes in physicochemical conditions (temperature, pH), including accompanying allosteric effects.

  - **Crosslinking (XL-MS):** This method is based on crosslinking proteins using reagents of a specific length, which, after binding to the protein and subsequent mass spectrometric detection, provide information about the distances between two amino acid side chains. This technique can detect and structurally characterize protein-protein interactions or characterize distances within the structure of an individual protein. The output is a table listing reliable detected crosslinks and their graphical representation on the protein sequence and on a 3D model.



# Other technologies
smFRET，FLIM-FRET


---
# Structure modeling

  - AlphaFoldv3
  - molecular dynamics simulations
  
  
  # Cryo-Electron Microscopy (cryo-EM)




**Ref database**:
1. EMDB: https://www.ebi.ac.uk/pdbe/emdb/
2. EMPIAR: https://www.ebi.ac.uk/pdbe/emdb/empiar/



---
## Nobel laureates
![nobelxqhemox](/img/nobel_prize.jpg)
---

- **Jacques Dubochet**, University of Lausanne, Lausanne, Switzerland\
The Nobel Prize in Chemistry 2017\
**Early cryo-electron microscopy** [[Nobel Lecture video](https://www.youtube.com/watch?v=Blm3QwT-rRk&ab_channel=NobelPrize) | [Lecture Slides](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EQ3Lh8WjagRFoiNVbUsIbk0BbkzwPzSe2gswYWApBQQSoA?e=70flib) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/ERsnFw1YSGpKmK-x6I-OcY8B_SnYvmbc9TuU_qTaM_bA4Q?e=GYkHk2) | [Source](https://www.nobelprize.org/prizes/chemistry/2017/dubochet/facts/)]

- **Joachim Frank**, Columbia University, New York, NY, USA\
The Nobel Prize in Chemistry 2017\
**Single-Particle Reconstruction – Story in a Sample** [[Nobel Lecture video](https://www.youtube.com/watch?v=Blm3QwT-rRk&ab_channel=NobelPrize) | [Lecture Slides](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EQ3Lh8WjagRFoiNVbUsIbk0BbkzwPzSe2gswYWApBQQSoA?e=70flib) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/ERsnFw1YSGpKmK-x6I-OcY8B_SnYvmbc9TuU_qTaM_bA4Q?e=GYkHk2) | [Source](https://www.nobelprize.org/prizes/chemistry/2017/frank/facts/)]

- **Richard Henderson**, MRC Laboratory of Molecular Biology, Cambridge, United Kingdom\
The Nobel Prize in Chemistry 2017\
**From Electron Crystallography to Single Particle cryoEM** [[Nobel Lecture video](https://www.youtube.com/watch?v=Blm3QwT-rRk&ab_channel=NobelPrize) | [Lecture Slides](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EQ3Lh8WjagRFoiNVbUsIbk0BbkzwPzSe2gswYWApBQQSoA?e=70flib) | [Read the Lecture](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/ERsnFw1YSGpKmK-x6I-OcY8B_SnYvmbc9TuU_qTaM_bA4Q?e=GYkHk2) | [Source](https://www.nobelprize.org/prizes/chemistry/2017/henderson/facts/)]

- **Roderick MacKinnon**, Rockefeller University, New York, NY, USA; Howard Hughes Medical Institute, USA\
Nobel Prize in Chemistry 2003\
**Potassium Channels and the Atomic Basis of Selective Ion Conduction** [[Nobel Lecture video](https://nobel-videocdn01.azureedge.net/video/lecture_2003_che_mckinnon_01_496.mp4) | [Read the Lecture](https://www.nobelprize.org/uploads/2018/06/mackinnon-lecture.pdf) | [Source](https://www.nobelprize.org/prizes/chemistry/2003/mackinnon/facts/)]


- **Max von Laue**, Frankfurt-on-the-Main University, Frankfurt-on-the-Main, Germany\
The Nobel Prize in Physics 1914\
**Concerning the Detection of X-ray Interferences** [[Nobel Documentary video](https://nobel-videocdn01.azureedge.net/video/docu_1914_phy_vonlaue_01_496.mp4) | [Read the Lecture](https://www.nobelprize.org/uploads/2018/06/laue-lecture.pdf) | [Source](https://www.nobelprize.org/prizes/physics/1914/laue/facts/)]


- **Wilhelm Conrad Röntgen**, Munich University, Munich, Germany\
The Nobel Prize in Physics 1901\
**in recognition of the extraordinary services he has rendered by the discovery of the remarkable rays subsequently named after him** 




