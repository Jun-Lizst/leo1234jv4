---
title: "SleepyBoy"
date: 2022-10-19T00:50:05+08:00
categories:
- category
- subcategory
tags:
- Sleep staging system
- EEG-EMG
- Non-supervised classification
- manifold learning
- deep learning
keywords:
- tech
comments:       false
showMeta:       false
showActions:    false
thumbnailImage: /img/
thumbnailImagePosition: left
#thumbnailImage: //example.com/image.jpg
---

> SleepyBoy is a integrated app for automatic sleep staging analysis and visualization of EEG-EMG data.

<!--more-->


SleepyBoy supports several data file formats and provides several scoring aid including the detection of essential features of NREM and REM sleep such as spindles, K-complexes, slow waves, and REM.





### Protocol
**EEG/EMG data collection**
The C57BL/6N mouse was implanted with electroencephalogram (EEG) and electromyogram (EMG) electrodes for EEG/EMG recordings. To monitor EEG signals, two stainless steel EEG recording screws of 1.0 mm in diameter and 2.0 mm in length were implanted on the skull of the cortex (anterior, +1.5 mm; right, +1.5 mm from bregma or lambda). EMG activity was monitored by stainless steel, Teflon-coated wires with 0.33 mm in diameter (AS633, Cooner Wire, U.S.A) placed into the trapezius muscle. The EEG and EMG wires were soldered to a miniature connector with four pins in 2-mm pitch (Hirose Electric Co., Ltd., Japan). Finally, the electrode assembly was fixed to the skull with dental cement (Unifast III, GC Corporation, Japan). 


**Sleep behaviour analysis**
- The recording room should be kept under 12-h light:12-h dark cycles and a constant temperature (24–25 °C). To examine sleep–wake behavior under baseline conditions, EEG/EMG signals were recorded for two consecutive days from the onset of the light phase. EEG/EMG data were visualized and analysed using a MatLab (MathWorks)-based, custom semi-automated staging program followed by visual inspection. EEG signals were subjected to fast Fourier transform analysis from 1 to 30Hz with 1-Hz bin using MatLab-based custom software. Epochs containing movement artefacts were included in the state totals but excluded from subsequent spectral analysis. Sleep/wakefulness was staged into wakefulness, NREMS and REMS. Wakefulness was scored based on the presence of low amplitude, fast EEG, and high amplitude, variable EMG. NREMS was characterized by high amplitude, delta (1–4 Hz) frequency EEG and low EMG tonus, whereas REMS was staged based on theta (6–9 Hz)-dominant EEG and EMG atonia.

- Hourly delta density during NREMS indicates hourly averages of delta density which is the ratio of delta power to total EEG power at each 20-s epoch. For the power spectrum of sleep/wakefulness, the EEG power of each frequency bins was expressed as a percentage of the total EEG power over all frequency bins (1–30 Hz) and sleep/wakefulness states. 


**Sleep deprivation**
- For sleep deprivation, mice were sleep deprived for 2, 4 and 6 h from the onset of the light phase by gently touching the cages when they started to recline and lower their heads. Food and water were available. To evaluate the effect of sleep deprivation, the NREMS delta power during the first hour after sleep deprivation was expressed relative to the same zeitgeber time (ZT) of the basal recording or relative to the mean of the basal recording. 


**Perturbation or drug injection experiments**
- For caffeine and modafinil injection experiments, mice were fully acclimatized for intraperitoneal injection before sleep recording. After 24-h baseline recording, mice received caffeine (Sigma), modafinil (Sigma) or vehicle (0.5% methyl cellulose (Wako)) intraperitoneally at ZT0, followed by 12-h recording. Injections were delivered once per week, with each injection followed by a 6–8-day washout period, during which mice remained in the recording chamber. To examine the sleep/wakefulness behaviour under constant darkness, after 48-h recording under a 12-h light:12-h dark cycle, EEG/EMG recording continued in constant darkness for 3 days.



### References
1. Funato, H., Miyoshi, C., Fujiyama, T. et al. Forward-genetics analysis of sleep in randomly mutagenized mice. Nature 539, 378–383 (2016). [[PMID:27806374](https://pubmed.ncbi.nlm.nih.gov/27806374/) | [DOI Link](https://doi.org/10.1038/nature20142)]
2. Wang, Zhiqiang, et al. "Quantitative phosphoproteomic analysis of the molecular substrates of sleep need." Nature 558.7710 (2018): 435-439. [[PMID: 29899451](https://pubmed.ncbi.nlm.nih.gov/29899451/) | [DOI Link](https://doi.org/10.1038/s41586-018-0218-8)]
3. Kim, S.J., Hotta-Hirashima, N., Asano, F. et al. Kinase signalling in excitatory neurons regulates sleep quantity and depth. Nature (2022). [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EYxHbshfJAhOvb7bxm0O8NsBqNe3wLQTj0ccwiV-09YEiA?e=nK3BKb) | [DOI Link](https://doi.org/10.1038/s41586-022-05450-1)]
4. Zhou, R., Wang, G., Li, Q. et al. A signalling pathway for transcriptional regulation of sleep amount in mice. Nature (2022). [[PDF](https://pkueducn-my.sharepoint.com/:b:/g/personal/lijun0705_pku_edu_cn/EcbUCC_QItFPnCVBm6SVGKgBtBvjuqRbkxLRIlX_Ae-6AA?e=DrQ8t1) | [DOI Link](https://doi.org/10.1038/s41586-022-05510-6)]
5. Wang, Y., Cao, S., Tone, D. et al. Postsynaptic competition between calcineurin and PKA regulates mammalian sleep–wake cycles. Nature 636, 412–421 (2024). [[PDF](https://www.nature.com/articles/s41586-024-08132-2.pdf) | [PMID:27806374](https://pubmed.ncbi.nlm.nih.gov/27806374/) | [DOI Link](https://doi.org/10.1038/s41586-024-08132-2)]
6. Iwasaki, Kanako, et al. "Protocol for sleep analysis in the brain of genetically modified adult mice." STAR protocols 2.4 (2021): 100982.  [[PDF](https://www.sciencedirect.com/science/article/pii/S2666166721006882/pdfft?md5=91b654f6a9c77ddfe4a63bf49b258ca2&pid=1-s2.0-S2666166721006882-main.pdf) | [PMID:34917975](https://pubmed.ncbi.nlm.nih.gov/34917975/) | [DOI Link](https://doi.org/10.1016/j.xpro.2021.100982)]



### Open source tools
1. [EDFbrowser](https://www.teuniz.net/edfbrowser/): A free, open-source, multiplatform, universal viewer, annotator and toolbox intended for, but not limited to, time-series storage files like EEG, EMG, ECG, BioImpedance, etc.
2. [FASTER2](https://github.com/OrganismalSystemsBiology/faster2): An automated sleep staging tool based on simple statistical features of mice electroencephalography (EEG) and electromyography (EMG) data. [[PMID: 39072800](https://pubmed.ncbi.nlm.nih.gov/39072800/) | [DOI Link](https://doi.org/10.1111/ejn.16465)]



### Open source database
1. [Sleep-EDF Database](https://physionet.org/content/sleep-edfx/1.0.0/): 
The sleep-edf database contains 197 PolySomnoGraphic whole-night sleep recordings with EEG, EOG, chin EMG, and event markers. Some recordings additionally include information about respiration and body temperature. Corresponding hypnograms (sleep patterns) were manually scored by well-trained technicians according to the Rechtschaffen and Kales manual. [[ref-Article](https://www.doi.org/10.1109/10.867928) | [PhysioNet](https://physionet.org/content/sleep-edfx/1.0.0/)]

