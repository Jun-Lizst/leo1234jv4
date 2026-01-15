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
> My own prejudices are exactly the opposite of the functionalists': "If you want to understand function, study structure".\
--- Francis Crick

<!--more-->


---
# CryoEM Single Particle Analysis (SPA)


1. **Cryo-EM microscopy**
    - [300 kV Titan Krios](https://www.thermofisher.com/cz/en/home/electron-microscopy/products/transmission-electron-microscopes/krios-cryo-tem/features.html): The Titan **Krios G4** from Thermo Fisher Scientific is a 300 kV transmission electron microscope (TEM) with a three-condenser lens system. It features the latest technology for high-end single-particle and tomography data acquisition including a cold field emission gun (C-FEG), SelectrisX energy filter, Falcon 4 electron counting camera and volta phase plate.
    - [200 kV](): The cryo-grids were initially screened at a nominal magnification of ×92,000 in an 200 kV microscope.
       - **Glacios**: The Glacios from Thermo Fisher Scientific is a 200 kV transmission electron microscope with a two-condenser lens system.
       - **Talos Arctica**: FEI [Talos Arctica microscope (200 kV)](https://documents.thermofisher.com/TFS-Assets/MSD/Datasheets/DS0189-EN-11-2019-Thermo-Scientific-Talos-Arctica-WEB.pdf), equipped with an FEI Ceta camera. [[Talos L120C manual, PDF](https://bioem.shanghaitech.edu.cn/_upload/article/files/79/11/d357319b47e584a520a8bbd06351/b83e470e-0a1b-4f87-a897-ea30e42efe93.pdf) | [Tutorial video](https://bioem.shanghaitech.edu.cn/_upload/article/videos/63/19/77aa69a04eca8fbc00f84f182337/b0817747-7020-4f37-80a3-d94cd4ed4365-B.mp4) | [Instruction for Arctica screening, UCSF](https://emcore.ucsf.edu/content/instructions-arctica-screening)]
    - [40kV-120kV]: [FEI Tecnai T12](https://emcore.ucsf.edu/fei-t12) is mainly used for simple screening and data collection of negatively-stained samples. It's also used for cryo-EM training and screening of vitrified grids. 
       - FEI T12 (FEI Tecnai T12 Transmission Electron Microscope) operates at 120kV with a LaB6 filament and is equipped with a Gatan UltraScan 895 4k CCD.


### **| Sample preparation** 
1. **Methods to improve particle behavior**
    - **Size exclusion chromatography**: Gel filtration can be a powerful tool to predict structural heterogeneity. Whenever possible, gel filtration should be incorporated to the final steps of a purification protocol.
    - **Protein or protein complex stabilization**: If negative stain or cryo-EM analysis reveals significant structural heterogeneity, then the user may consider additional methods to stabilize a structural target in a defined conformation. These approaches have proven to be effective in trapping conformationally variable proteins and complexes in energetic minima that allow high-resolution structure determination. Examples include using small molecule inhibitors, non-hydrolyzable nucleotides (if applicable), Fab antibody fragments, or genetic perturbations (e.g., mutating catalytic residues).
      - [[ALFA tag (SRLEEELRRRLTE) and ALFA nanobody]() | [Reference](https://www.nature.com/articles/s41467-023-42210-9#Sec2)]
    - **Chemical crosslinking**: One common way to counteract structural heterogeneity is to chemically crosslink the purified sample, such as with glutaraldehyde or BS3. However, crosslinked samples run a risk of producing structural artifacts and this approach should therefore be considered only after a control, non-crosslinked sample has been evaluated.
    - **Membrane proteins**:
      - **Isolation of membrane fractions**: 100,000 g
      - **Screen of Detergents**: [CHAPS | Digitonin | 1% DDM + 0.2% CHS | 2% (w/v) GDN + 0.1% (w/v) CHS + 0.2 mg/ml Avanti | 0.5% LMNG + 0.03% CHS | AMPHIPOL A8-35 | AMPHIPOL PMAL-C8]
      - **Affinity Chromatography (AC)**: [anti-FLAG | Strep-Tactin XT]
      - **Crosslinking for membrane protein complex**: 0.1% (v/v) , 40 mins
      - **SEC**: [[Superose 6 increase 10/300] | [Superdex 200 increase 10/300]]
      

2. **Protocol for grid preparation**
    - For Negative stain TEM: [[Protocol, PDF](https://cryoem.wisc.edu/wp-content/uploads/sites/341/2021/01/Negative_Stain_Grid_Preparation_21Jan2021.pdf) | [Yifan Cheng lab, 2011](https://www.ncbi.nlm.nih.gov/pubmed/22215030) | [UCSF protocol](https://emcore.ucsf.edu/content/negative-stain-protocol)]
     --- General procedure: 3.5 μL of purified protein complexes at 0.02 mg/ml was pipetted onto a continuous carbon coated grid and incubated at room temperature for 60 s. The sample was blotted using filter paper. Immediately, 3.5 μL of 2% (w/v) uranyl formate was pipetted onto the grid and blotted away with filter paper. This treatment with uranyl formate stain was repeated two more times, except an addition of a 30 s wait between stain application and blotting during the last cycle. The grid was left to dry at room temperature for 2 mins.
     --- Cressington 208 carbon evaporator [[Carbon coating grids (UCSF manual)](https://emcore.ucsf.edu/content/cressington-208-carbon-evaporator)]
    
    - Graphene type \
     --- [Monolayer graphene](https://www.biorxiv.org/node/981810.full) \
     --- [Graphene oxide](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC6119484/) \
     --- [Functionalized graphene](https://www.pnas.org/content/116/24/11718) \
     --- [Functionalized graphene oxide](https://www.biorxiv.org/content/10.1101/657411v1.full)
    - Grids:
     --- Quantifoil R 1.2/1.3 300 Holey Carbon films Au 300 mesh grids
     --- holey carbon grid (Quantifoil R1.2/1.3)
    - Plasma cleaner for glow discharge
     --- Glow Discharge Plasma Cleaner ([SKU: M-PDC-32G](https://www.mitegen.com/product/basic-plasma-cleaner/))
     --- Economy Dry Oxygen Service Pump ([SKU: M-PDC-OPE](https://www.mitegen.com/product/economy-dry-oxygen-service-pump/))
     --- Vacuum Gauge and Digital Meter ([SKU: M-PDC-VCG](https://www.mitegen.com/product/vacuum-gauge-digital-meter/))
     --- Quartz Sample Tray ([SKU: M-PDC-32T](https://www.mitegen.com/product/quartz-sample-tray/))
     --- GridPrepBlock Support For Grids During Surface Treatment ([SKU: M-CEM-GSB5-1](https://www.mitegen.com/product/grid-prep-block/))



3. **Sample Vitrification**: Vitrification is the rapid cooling of a liquid into a solid, glass-like amorphous state, preventing the formation of damaging ice crystals. 
    - [**EM GP2, Leica**](https://www.leica-microsystems.com/products/sample-preparation-for-electron-microscopy/p/leica-em-gp2/): The EM GP2 from Leica Microsystems is an automated plunge freezer able to vitrify thin samples applied to an electron microscopy grid after removing excess fluid by blotting. [[Tutorial video, mp4](https://bioem.shanghaitech.edu.cn/_upload/article/videos/d8/77/91cf34504384919c5e5787c54f07/666c8301-1b09-43d0-9472-1d00f5dbe414-B.mp4) | [Manual, PDF](https://bioem.shanghaitech.edu.cn/_upload/article/files/79/11/d357319b47e584a520a8bbd06351/883df0db-6349-4fca-9686-a4a8107152e6.pdf)]

    - **Vitrobot, Thermo Fisher**: The Vitrobot Mark IV System from Thermo Fisher Scientific is an automated plunge freezer able to vitrify thin samples applied to an electron microscopy grid after removing excess fluid by blotting. [[Tutorial video, mp4](https://bioem.shanghaitech.edu.cn/_upload/article/videos/a4/8e/d17c5c5e4d858b49938c682dca00/b9546e76-893f-4b41-bc9d-d3b4b6244c48-B.mp4) | [Manual, PDF](https://bioem.shanghaitech.edu.cn/_upload/article/files/79/11/d357319b47e584a520a8bbd06351/0ac79af7-f4bc-45ff-9fcf-0cf3f357e656.pdf) | [Standard Operation Protocol, PDF](https://info.cpos.hku.hk/wp-content/uploads/2025/04/Standard-Operation-Protocol-%E2%80%93-Vitrobot-Mark-IV.pdf)]
    
    - Vitrodrop:
    - Preassis    
    - CryoSol Vitrojet System
    - Products for improving sample vitrification
| Product name    | Catalog | Vendor |  Description | 
| -------- | ------- |  ------- |   ------- |
| Fluorinated FC-8  | [F300F](https://anatrace.com/en/product/F300F-1-GM)    | Anatrace  | FC-8 has been  vitrification condition for both soluble and membrane proteins       |
| Fluorinated OM  | [0310F](https://www.atcc.org/products/crl-2266)    | Anatrace  |          |
| Calixar C2B kit  | [MD1-109](https://www.atcc.org/products/crl-2266)    | MD  |          |
| Cryo-EM V-Kit | [X-CEM-301](https://www.atcc.org/products/htb-96)     |  Jena  |          |
| Cryo-EM Vitrification Starter Kit   | [M-CEM-VK301](https://www.mitegen.com/product/cryo-em-vitrification-starter-kit/)    |  MiTeGen      | The Cryo-EM V-Kit is a Vitrification Starter Kit that offers both a selection of surfactants which have been successfully applied in cryo-EM sample preparation and a selection of Quantifoil Holey Carbon Films to facilitate the search for the optimal vitrification condition for both soluble and membrane proteins. |


### **| Cryo-EM data analysis**
#### Softwares
1. [CryoSPARC](https://guide.cryosparc.com/): CryoSPARC (Cryo-EM Single Particle Ab-Initio Reconstruction and Classification) is a state of the art data analysis solution for single-particle analysis (SPA) in cryo-electron microscopy (cryo-EM). CryoSPARC is used to reconstruct and visualize cryo-EM structures of biological targets including membrane proteins, viruses and complexes.
2. [Relion](https://relion.readthedocs.io/en/release-5.0/): relion (for REgularised LIkelihood OptimisatioN, pronounce rely-on) is a software package that employs an empirical Bayesian approach for electron cryo-microscopy (cryo-EM) structure determination. It is developed in the group of [Sjors Scheres](https://www2.mrc-lmb.cam.ac.uk/groups/scheres/impact.html) at the [MRC Laboratory of Molecular Biology](https://www2.mrc-lmb.cam.ac.uk/group-leaders/n-to-s/sjors-scheres/).
3. [SPIDER](https://github.com/spider-em/SPIDER): SPIDER (System for Processing Image Data from Electron microscopy and Related fields) is an image processing system for electron microscopy, especially usefull for single-particle reconstruction. 
    - [Online tutorial](https://spider-em.github.io/SPIDER/)
    - Evaluation of difference maps: It can be achieved by Spider and the [diffmap program](https://grigoriefflab.umassmed.edu/diffmap) to calculate a difference map between two input maps and the estimated standard deviation of the difference map.

4. [COOT](https://www2.mrc-lmb.cam.ac.uk/personal/pemsley/coot/): For manually rebuilt and/or adjust models.
    - Emsley, Paul, and Kevin Cowtan. "Coot: model-building tools for molecular graphics." Biological crystallography 60.12 (2004): 2126-2132. [[PMID: 15572765](https://pubmed.ncbi.nlm.nih.gov/15572765/)]
    - Using Coot for model building into EM maps: A tutorial [[PDF](https://www2.mrc-lmb.cam.ac.uk/personal/pemsley/coot/files/EM-Tutorial-Coot-PE.pdf)]
    
5. [Phenix](https://phenix-online.org/): For Real space and Rosetta refinements.
    - Adams, Paul D., et al. "PHENIX: a comprehensive Python-based system for macromolecular structure solution." Biological crystallography 66.2 (2010): 213-221. [[PMID: 20124702](https://pubmed.ncbi.nlm.nih.gov/20124702/)]

6. [Rosetta Commons](https://www.rosettacommons.org/software/): For decades, Rosetta has been at the forefront of computational biology, offering groundbreaking capabilities in the modeling, design and analysis of protein structures.

7. [CCP-EM](https://www.ccpem.ac.uk/): Supported by the UK Medical Research Council, the Collaborative Computational Project for Electron cryo-Microscopy (cryoEM) provides support in computational areas for users and developers in biological cryoEM.
    - Single Particle Analysis using Relion [[PDF](https://www.ccpem.ac.uk/downloads/tutorials/doppio/Doppio_Relion_SPA_tutorial.pdf)]
    - Model Building and Validation in CCP-EM Doppio [[PDF](https://www.ccpem.ac.uk/downloads/tutorials/doppio/Doppio_model_docking_refinement_tutorial.pdf)] 
    - Refinement against cryo-EM data with CCP-EM using REFMAC & Coot [[PDF](https://www.ccpem.ac.uk/downloads/tutorials/refmac_servalcat/servalcat-refmac_coot_tutorial_ECM_2022.pdf)]
    
8. [Requirement of computational cluster/Workstation](https://guide.cryosparc.com/setup-configuration-and-management/hardware-and-system-requirements):
    - **CPU:** 32 Cores (base clock 2.8GHz+), e.g, AMD Threadripper 3975X
    - **RAM:** 256GB DDR4 @ 3200MHz
    - **Storage:** 4TB PCIe SSD (cache); 200TB RAID 6 storage server via 10Gbps link (raw movies)
    - **GPU:** 4x NVIDIA Quadro GV100, or 4x NVIDIA Tesla V100 or 4x NVIDIA RTX 8000

#### CryoEM data analysis protocols


#### Deep learning tools

**Ref softwares**:
1. **MotionCorr**: This program corrects whole frame image motion recordded with dose fractionated image stack. [MotionCor2](https://emcore.ucsf.edu/ucsf-motioncor2)
    - Xueming Li, Paul Mooney, Shawn Zheng, Chris Booth, Michael B. Braunfeld, Sander Gubbens, David A. Agard and Yifan Cheng (2013) Electron counting and beam-induced motion correction enables near atomic resolution single particle cryoEM. Nature Methods, 10, 584-590. PMID: 23644547 
    - [MotionCor3](https://github.com/czimaginginstitute/MotionCor3), an improved implementation of MotionCor2 with addition of CTF (Contrast Transfer Function) estimation, is a multi-GPU accelerated software package that enables single-pixel level correction of anisotropic beam induced sample motion for cryo-electron microscopy and cryo-electron tomography images.
    
2. **GeFREALIGN**: FREALIGN is a program developed by Niko Grigorieff laboratory for high-resolution refinement of 3D reconstruction from cryoEM of single particles. 
    - Xueming Li, Nikolaus Grigorieff and Yifan Cheng (2010) GPU-enabled FREALIGN: Accelerating single particle 3D reconstruction and refinement in Fourier space on graphics processors. Journal of Structural Biology, advanced publication online June 14 2010. PMID: 20558298



#### Online resources
1. [**CryoEM 101**](https://cryoem101.org/)
2. [Cryo-EM University](https://www.thermofisher.com/cz/en/home/electron-microscopy/life-sciences/learning-center/cryo-em-university.html): Cryo-EM University features over 70 hours of theoretical lectures and videos. Created in collaboration with online education expert Professor Grant Jensen, it serves as an introduction to the field and is intended for participants of all levels. Upon completion, you will have a fundamental knowledge of cryo-EM, tips and tricks to overcome sample preparation challenges, and valuable practical advice on the cryo-EM workflow.

3. [Electron Cryo-microscopy Course 2023, MRC-LMB](https://www2.mrc-lmb.cam.ac.uk/research/scientific-training/electron-microscopy/)
    - Specimen preparation for cryo-EM – Katerina Naydenova [[Video](https://youtu.be/hF17d6XjV98)]
    - Cryo-EM Data Collection – Giuseppe Cannone [[Video](https://youtu.be/hS-HrgWv0HQ)]
    - Modelling using Cryo-EM Data: A Review of the Problems and Software (including Coot) – Paul Emsley [[Video](https://youtu.be/a_fJ6kAcsa4)]
    

3. [Electron Cryo-microscopy Course 2017, MRC-LMB](https://www2.mrc-lmb.cam.ac.uk/research/scientific-training/electron-microscopy/): Below are recordings of the LMB’s 2017 Cryo-microscopy course.
    - Cryo-EM17 Lecture 01: Past Present Future [[Video](https://youtu.be/aHhmnxD6RCI) | [Lecture Slide, PDF](https://www2.mrc-lmb.cam.ac.uk/download/cryo-em17-lecture-01-past-present-future/?wpdmdl=18763&refresh=68defc2580e3c1759444005)] 
    - Cryo-EM17 Lecture 02: Physics Optics [[Video](https://youtu.be/nQ-9QmRxDmA) | [Lecture Slide, PDF](https://www2.mrc-lmb.cam.ac.uk/download/cryo-em17-lecture-02-physics-optics/?wpdmdl=18757&refresh=68defc24bc6661759444004)]
    - Cryo-EM17 Lecture 04: Data Acquisition [[Video](https://youtu.be/9AMSabcTN24) | [Lecture Slide, PDF](https://www2.mrc-lmb.cam.ac.uk/download/cryo-em17-lecture-04-data-acquisition/?wpdmdl=18759&refresh=68defc24e19ae1759444004)]
    - Cryo-EM17 Lecture 06: Refinement [[Video](https://youtu.be/TfLFCeehfjM) | [Lecture Slide, PDF](https://www2.mrc-lmb.cam.ac.uk/download/cryo-em17-lecture-06-refinement/?wpdmdl=18760&refresh=68defc2514c571759444005)]
    - Cryo-EM17 Lecture 07: Data processing strategy - Rafael Fernandez-Leiro     
    - Cryo-EM17 Lecture 08: Modelling – Alan Brown [[Video](https://youtu.be/byAFhhDt-f4) | [Lecture Slide, PDF](https://www2.mrc-lmb.cam.ac.uk/download/cryo-em17-lecture-08-modelling/?wpdmdl=18761&refresh=68defc2537ecc1759444005)]
    - Cryo-EM17 Lecture 09: Tomography [[Video](https://youtu.be/4Z0sQ_GhBkk) | [Lecture Slide, PDF](https://www2.mrc-lmb.cam.ac.uk/download/cryo-em17-lecture-09-tomography/?wpdmdl=18762&refresh=68defc255dd601759444005)]

    

#### Service Centers: 
1.[UCSF EM Core, University of California San Francisco](https://emcore.ucsf.edu/)


2. [The UW-Madison Cryo-Electron Microscopy Research Center (CEMRC), University of Wisconsin-Madison](https://cryoem.wisc.edu/)


3. [Bio-Electron Microscopy Facility, Shanghai Tech University](https://bioem.shanghaitech.edu.cn/7390/list.htm)


4. [MIT.nano](https://cryoem.mit.edu/), MIT campus
- The Cryo-Electron Microscopy Facility in MIT.nano enables automated electron imaging of cryogenically preserved specimens. The facility was established in 2018 with support from The Arnold and Mabel Beckman Foundation, an Anonymous donor, as well as institutional support from the Vice President for Research, School of Science, and Departments of Biology, Materials Science, and Chemistry. The facility includes two cryoTEMs, a cryoFIB-SEM, two different cryoplungers, and a laboratory space for cryo-specimen preparation.
  



#### Vendor companies
1. [Thermo Scientific](https://www.thermofisher.com/us/en/home/electron-microscopy/products/sample-preparation-equipment-em/vitrobot/instruments/vitrobot-mark-iv.html)
2. [Shuimu Bioscience](https://shuimubio.com/about): Shuimu is a rapidly evolving global cryo-EM & AI platform dedicated to early drug discovery. Equipped with 8 state-of-the-art 300kV cryo-EM instruments, Shuimu drives innovation to accelerate the development of groundbreaking drugs.
3. [Leica](https://www.leica-microsystems.com/products/sample-preparation-for-electron-microscopy/p/leica-em-gp2/app/)
4. [SPT Labtech](https://cryowrite.ch/)
5. [cryoWrite](https://support.shimadzu.com.cn/an/resource/index.html#105)
6. [CryoSol](https://cryosol-world.com/vitrojet-solutions/technology/)
7. [Quantifoil, Germany](https://www.quantifoil.com/): Founded in 1999, Quantifoil Micro Tools GmbH was the first commercial manufacturer of electron microscopy support films of predefined hole size and arrangement and continues to set the global standard. Quantifoil's cryo-EM sample supports have been cited in more than 4,000 peer-reviewed publications, and are essential to cryo-EM workflows worldwide.




### Ref labs: 
1. [Yifan Cheng Lab, UCSF](https://cryoem.ucsf.edu/)
- **Atomic structures of TRPV1**: With David Julius’s laboratory at UCSF [[Liao, et al. 2013, Nature](https://www.nature.com/articles/nature12822#Abs1) | [Cao et al. 2013, Nature](https://doi.org/10.1038/nature12823) | Gao et al. 2016, Nature]
- **iBiology Talks**: [[Part 1: Single Particle Cryo-EM](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/EfUivsENbh5Gj8E10GGp0KEBynIVfURLM06aJ4xv6Y3XxQ?e=I8Ahs5) | [Part 2: Single particle Cyro-EM of membrane proteins](https://pkueducn-my.sharepoint.com/:v:/g/personal/lijun0705_pku_edu_cn/EXRwR0JzrnBOoKHcQUQvjNMB5kaISskZMilMzXJFH2FAAw?e=05Bk8U)]

2. [Niko Grigorieff Lab, UMASS](https://grigoriefflab.umassmed.edu/research_interests): The Grigorieff lab has played a foundational role in modern single-particle cryo-electron microscopy by developing widely adopted algorithms and software for motion correction, contrast transfer function estimation, and high-resolution 3D reconstruction, including CTFFIND, Unblur, Frealign, and cisTEM. These contributions have significantly advanced the resolution, robustness, and accessibility of cryo-EM, transforming it into a routine tool for structural biology. Their work exemplifies how rigorous physical modeling and computational innovation can unlock biological insight from complex and noisy imaging data.

3. [Grant Jensen Lab, Caltech](https://jensenlab.caltech.edu/): Grant then entered an M.D./Ph.D. program at Stanford University, and earned his doctorate in Biophysics working on electron microscopy of RNA polymerase and other protein complexes with **Dr. Roger Kornberg** (who later won the Nobel prize for structural studies of transcription).
- **Course**: [“Getting Started in Cryo-EM”](https://cryo-em-course.caltech.edu/unit-1-outline)
    - Part 1: Currents, coils, knobs and names: Basic anatomy of the electron microscope [[PDF](https://cryo-em-course.caltech.edu/documents/8696/part_1-_em_anatomy_cBGbc1R.pdf) | [Lecture video](https://youtu.be/GBU1eA1PqeQ?list=PL8_xPU5epJdctoHdQjpfHmd_z9WvGxK8-)]
    - Part 2: Fourier transforms and reciprocal space for beginners [[PDF](https://cryo-em-course.caltech.edu/documents/8699/part_2_-_fouriertransforms_gIqtOnD.pdf) | [Lecture video](https://youtu.be/-EAQm8wgLbc?list=PL8_xPU5epJdctoHdQjpfHmd_z9WvGxK8-)]
    - Part 3: Image formation [[PDF](https://cryo-em-course.caltech.edu/documents/8698/part_3_-_image_formation_47kqLDj.pdf) | [Lecture video](https://youtu.be/gmZ-vzB5lyI?list=PL8_xPU5epJdctoHdQjpfHmd_z9WvGxK8-)]
    - Part 4: Fundamental challenges in biological EM [[PDF](https://cryo-em-course.caltech.edu/documents/8701/part_4_-_fundamentalchallenges_21NEmk3.pdf) | [Lecture video](https://youtu.be/jYhp4aLZEb4?list=PL8_xPU5epJdctoHdQjpfHmd_z9WvGxK8-)]
    - Part 5: Tomography [[PDF](https://cryo-em-course.caltech.edu/documents/14740/part_5_-_Review_slides_tomography_Revised.pdf) | [Lecture video](https://youtu.be/tOnijBqdJ1E?list=PL8_xPU5epJdctoHdQjpfHmd_z9WvGxK8-)]
    - Part 6: Single-particle analysis [[PDF](https://cryo-em-course.caltech.edu/documents/8702/part_6_-_single_particle_analysis_3bTNWgw.pdf) | [Lecture video](https://youtu.be/MkzZNrrrJpc?list=PL8_xPU5epJdctoHdQjpfHmd_z9WvGxK8-)]
    - Part 7: 2-D crystallography [[PDF](https://cryo-em-course.caltech.edu/documents/8697/part_7_-_electroncrystallography_qQ7rp3w.pdf) | [Lecture video](https://youtu.be/Qn7aP-fRT5I?list=PL8_xPU5epJdctoHdQjpfHmd_z9WvGxK8-)]
    - Concept Check Questions [[PDF](https://cryo-em-course.caltech.edu/documents/14853/cryo-em_concept_check_questions_Revised_1.pdf)]
    - Unit 2: Sample Preparation [[Hands-on videos](https://www.youtube.com/playlist?list=PL8_xPU5epJdfd5fM2CjQItR-iRlIEIJk8)]
      - **(1) Preparing hydrophilic grids**: [Manufacturer's grid boxes | Recognizing the carbon and copper sides of a grid | How to grab grids with tweezers | Glow discharging Plasma cleaning | Hydrophobic and hydrophilic grids]
      - **(2) Plunge freezing with a Vitrobot**: [Plunge freezing tools | Vitrobot connections | Mounting the Vitrobot humidifier | Filling the Vitrobot humidifier | Tour of the Vitrobot humidifying chamber | The Vitrobot user interface and options | Replacing Vitrobot blot pads | Mounting and unmounting Vitrobot tweezers | Aligning the Vitrobot tweezers between the blot pads | Preparing the ethane gas source | Filling the ethane cup | Plunge freezing with the Vitrobot | Reviving the ethane | Sources of contamination]
      - **(3) Assembling autogrids**: [Autogrid assembly tools | Loading C clips into insertion tools | room temp demo | Assembling autogrids (cryo conditions)]
      - **(4) Loading autogrids into cassettes**: [Cassette loading tools | Assembling the cassette loading station | Structure of the cassette | Inserting autogrids into the cassette | Loading the cassette - room temp demo | Loading the cassette (cryo conditions) | ]
      - **(5) Docking and undocking capsules**: [The capsule pin and its purpose | Docking a cassette | Undocking a cassette]
      - **(6) Plunge-freezing safety**: [Biological hazards | Compressed gas hazards | Explosive gas hazards | Can the liquid ethane in the cup catch fire? | Large liquid nitrogen tank hazards | Safety Small liquid nitrogen dewars | Liquid nitrogen on the skin hazards | Ethane splash and cold cup hazards] 

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

8. [James H. Hurley Lab, University of California Berkeley](https://membrane.berkeley.edu/)
- **Structural basis of Lysosomal Regulation**







---
# X-ray crystallography
> While the X-ray evidence cannot, at present, be taken as direct proof that the structure is helical, other considerations discussed below make the existence of a helical structure highly probable.
--- Rosalind Franklin


### Vendor companies




### Ref. Labs


### Pioneers
1. Rosalind Franklin (1920-1958)


#### Online resources
1. [Crystallography Course 2013, MRC-LMB](https://www2.mrc-lmb.cam.ac.uk/research/scientific-training/crystallography-course-2013/)
    - Molecular replacement [[Lecture slides, PDF](https://www2.mrc-lmb.cam.ac.uk/download/molecular-replacement/?wpdmdl=18799&refresh=68df0795bcf791759446933)]
    - 03 Protein Expression Crystallization And Mutagenesis – Meindert Lamers [[Video](https://youtu.be/glQXW7MyIts) | [Lecture slides, PDF](https://www2.mrc-lmb.cam.ac.uk/download/03-protein-expression-crystallization-and-mutagenesis-meindert-lamers/?wpdmdl=18793&refresh=68df0795ddcca1759446933)]   
    - LMB Crystallography Course, 2013 [[Lecture slides, PDF](https://www2.mrc-lmb.cam.ac.uk/download/lmb-crystallography-course-2013/?wpdmdl=18792&refresh=68df0796e2a431759446934)]  
    - Model-Building of Proteins Using X-ray Data With Coot Paul Emsley [[Lecture slides, PDF](https://www2.mrc-lmb.cam.ac.uk/download/model-building-of-proteins-using-x-ray-data-with-coot-paul-emsley/?wpdmdl=18785&refresh=68df07978699a1759446935)]

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
    - The CHARMM-GUI  
    - The CHARMM36m force field
    - Gromacs 2023




**Ref database**:
1. EMDB: https://www.ebi.ac.uk/pdbe/emdb/
2. EMPIAR: https://www.ebi.ac.uk/pdbe/emdb/empiar/
---
3. Protein structure database
  
| Protein Name    | PDB No. | Species | Expression System | Best Resolution (Å) |
| -------- | ------- |  ------- | ------- | ------- |
| BRAF  | [8C7X; 8C7Y](https://www.rcsb.org/structure/8C7X)    | Homo sapiens  |  Escherichia coli  |    1.65      |
| AKT1 | [1UNQ](https://www.rcsb.org/structure/1UNQ)     |  Homo sapiens  |  Escherichia coli BL21    |  0.98  |
| mTOR   | [5H64](https://www.rcsb.org/structure/5H64)    |  Homo sapiens      |  HEK293F   |  4.4 | 
| mTORC1-TFEB-Rag-Ragulator | [7UXH](https://www.rcsb.org/structure/7UXH)    |  Homo sapiens      |  HEK293F   |     3.4   |
| Raptor-TFEB-Rag-Ragulator | [7UX2](https://www.rcsb.org/structure/7UX2)    |  Homo sapiens      |  HEK293F   |     2.9   |







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

- **Thomas A. Steitz**, Yale University, New Haven, CT, USA; Howard Hughes Medical Institute, USA
The Nobel Prize in Chemistry 2009\
**From the Structure and Function of the Ribosome to New Antibiotics**  [[Nobel Lecture video](https://nobel-videocdn01.azureedge.net/video/lecture_2009_che_steitz_01_496.mp4) | [Lecture Slides](https://www.nobelprize.org/uploads/2018/06/steitz-lecture-slides.pdf) | [Read the Lecture](https://www.nobelprize.org/uploads/2018/06/steitz_lecture.pdf) | [Source](https://www.nobelprize.org/prizes/chemistry/2009/steitz/facts/)]

- **Venkatraman Ramakrishnan**, MRC Laboratory of Molecular Biology, Cambridge, United Kingdom
The Nobel Prize in Chemistry 2009\
**Unraveling the Structure of the Ribosome** [[Nobel Lecture video](https://nobel-videocdn01.azureedge.net/video/lecture_2009_che_ramakrishnan_01_496.mp4) | [Lecture Slides](https://www.nobelprize.org/uploads/2018/06/ramakrishnan-lecture-slides.pdf) | [Read the Lecture](https://www.nobelprize.org/uploads/2018/06/ramakrishnan_lecture.pdf) | [Source](https://www.nobelprize.org/prizes/chemistry/2009/ramakrishnan/facts/)]

- **Roger D. Kornberg**, Stanford University, Stanford, CA, USA
The Nobel Prize in Chemistry 2006\
**The Molecular Basis of Eukaryotic Transcription**  [[Nobel Lecture video](https://nobel-videocdn01.azureedge.net/video/lecture_2006_che_kornberg_01_496.mp4) | [Lecture Slides](https://www.nobelprize.org/uploads/2018/06/kornberg-slides.pdf) | [Read the Lecture](https://www.nobelprize.org/uploads/2018/06/kornberg_lecture.pdf) | [Source](https://www.nobelprize.org/prizes/chemistry/2006/kornberg/facts/)]


- **Roderick MacKinnon**, Rockefeller University, New York, NY, USA; Howard Hughes Medical Institute, USA\
Nobel Prize in Chemistry 2003\
**Potassium Channels and the Atomic Basis of Selective Ion Conduction** [[Nobel Lecture video](https://nobel-videocdn01.azureedge.net/video/lecture_2003_che_mckinnon_01_496.mp4) | [Read the Lecture](https://www.nobelprize.org/uploads/2018/06/mackinnon-lecture.pdf) | [Source](https://www.nobelprize.org/prizes/chemistry/2003/mackinnon/facts/)]


- **Kurt Wüthrich**, Eidgenössische Technische Hochschule (Swiss Federal Institute of Technology), Zurich, Switzerland; The Scripps Research Institute, La Jolla, CA, USA
The Nobel Prize in Physics 2002\
**NMR Studies of Structure and Function of Biological Macromolecules** [[Nobel Lecture video](https://nobel-videocdn01.azureedge.net/video/lecture_2002_che_wuthrich_01_496.mp4) | [Read the Lecture](https://www.nobelprize.org/uploads/2018/06/wutrich-lecture.pdf) | [Source](https://www.nobelprize.org/prizes/chemistry/2003/mackinnon/facts/)]


- **Linus Carl Pauling (C)**,
The Nobel Prize in Physics 1954\

- **James Batcheller Sumner**,
The Nobel Prize in Physics 1946\

- **Theodor (The) Svedberg (C)**,
The Nobel Prize in Physics 1926\


- **Sir William Henry Bragg**, 
The Nobel Prize in Physics 1915\


- **Max von Laue**, Frankfurt-on-the-Main University, Frankfurt-on-the-Main, Germany\
The Nobel Prize in Physics 1914\
**Concerning the Detection of X-ray Interferences** [[Nobel Documentary video](https://nobel-videocdn01.azureedge.net/video/docu_1914_phy_vonlaue_01_496.mp4) | [Read the Lecture](https://www.nobelprize.org/uploads/2018/06/laue-lecture.pdf) | [Source](https://www.nobelprize.org/prizes/physics/1914/laue/facts/)]


- **Wilhelm Conrad Röntgen**, Munich University, Munich, Germany\
The Nobel Prize in Physics 1901\
**in recognition of the extraordinary services he has rendered by the discovery of the remarkable rays subsequently named after him** 




