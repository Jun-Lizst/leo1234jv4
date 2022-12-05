---
title: "SleepyR"
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

> SleepyR is a integrated app for automatic sleep staging analysis of EEG-EMG data.

<!--more-->


SleepyR supports several data file formats and provides several scoring aid including the detection of essential features of NREM and REM sleep such as spindles, K-complexes, slow waves, and REM.

SleepyR was written in R, an easy-to-learn and high-level programming language widely used in the scientific community.







### Protocol
**Sleep behaviour analysis**
- The recording room should be kept under 12-h light:12-h dark cycles and a constant temperature (24–25 °C). To examine sleep–wake behavior under baseline conditions, EEG/EMG signals were recorded for two consecutive days from the onset of the light phase. EEG/EMG data were visualized and analysed using a MatLab (MathWorks)-based, custom semi-automated staging program followed by visual inspection. EEG signals were subjected to fast Fourier transform analysis from 1 to 30 Hz with 1-Hz bin using MatLab-based custom software. Epochs containing movement artefacts were included in the state totals but excluded from subsequent spectral analysis. Sleep/wakefulness was staged into wakefulness, NREMS and REMS. Wakefulness was scored based on the presence of low amplitude, fast EEG, and high amplitude, variable EMG. NREMS was characterized by high amplitude, delta (1–4 Hz) frequency EEG and low EMG tonus, whereas REMS was staged based on theta (6–9 Hz)-dominant EEG and EMG atonia.

- Hourly delta density during NREMS indicates hourly averages of delta density which is the ratio of delta power to total EEG power at each 20-s epoch. For the power spectrum of sleep/wakefulness, the EEG power of each frequency bins was expressed as a percentage of the total EEG power over all frequency bins (1–30 Hz) and sleep/wakefulness states35,36. For sleep deprivation, mice were sleep deprived for 2, 4 and 6 h from the onset of the light phase by gently touching the cages when they started to recline and lower their heads. Food and water were available. To evaluate the effect of sleep deprivation, the NREMS delta power during the first hour after sleep deprivation was expressed relative to the same zeitgeber time (ZT) of the basal recording or relative to the mean of the basal recording. For caffeine and modafinil injection experiments, mice were fully acclimatized for intraperitoneal injection before sleep recording. After 24-h baseline recording, mice received caffeine (Sigma), modafinil (Sigma) or vehicle (0.5% methyl cellulose (Wako)) intraperitoneally at ZT0, followed by 12-h recording. Injections were delivered once per week, with each injection followed by a 6–8-day washout period, during which mice remained in the recording chamber. To examine the sleep/wakefulness behaviour under constant darkness, after 48-h recording under a 12-h light:12-h dark cycle, EEG/EMG recording continued in constant darkness for 3 days.



### References
1. Funato, H., Miyoshi, C., Fujiyama, T. et al. Forward-genetics analysis of sleep in randomly mutagenized mice. Nature 539, 378–383 (2016). https://doi.org/10.1038/nature20142

