# Thesis Project
 This will be my master thesis project

# Dataset Variable Description

## Patient related

* RID: Research Identifier for each participant.
* Gender: Gender of the participant (0 for female, 1 for male).
* Ageatscreening: Age of the participant at the time of screening.

**Diagnosis information: Texture features were extracted from 194 NC, 200 MCI, 84 MCI who converted to AD (MCIc), and 130 AD subjects.**
* Diagnosis: 0 = normal control, 1 = mild cognitive impairment, 2 = MSI Converter, 3 = Alzheimer’s.

    * 0 = normal control: Individuals with no cognitive impairment, serving as a control group.
    * 1 = Mild Cognitive Impairment (MCI): Participants diagnosed with mild cognitive symptoms, indicating a slight decline in cognitive abilities but still functioning independently in daily activities.
    * 2 = MCI Converter: Individuals initially diagnosed with mild cognitive impairment who have shown progression towards more severe impairment or early Alzheimer’s disease.
    * 3 = Alzheimer’s Disease (AD) Patient: Participants diagnosed with Alzheimer’s disease, displaying substantial cognitive decline that significantly impacts daily functioning.
* MMSE0m: Baseline Mini-Mental State Examination (MMSE) score; assesses cognitive function, with higher scores indicating better cognitive health.

## Hippocampus related

* HipsASMbaseline: Baseline Angular Second Moment (ASM) for hippocampus; higher values indicate more homogenous textures, relating to structural integrity.

* HipsContrastbaseline: Baseline Contrast for hippocampus; measures intensity differences between neighboring pixels, indicating tissue structure variations.
* HipsCorelationbaseline: Baseline Correlation for hippocampus; describes linear dependency of gray levels, with higher values suggesting more orderly tissue.
* HipsVariancebaseline: Baseline Variance for hippocampus; represents spread of intensity values, indicating variability in tissue composition.
* HipsSumAveragebaseline: Baseline Sum Average for hippocampus; average sum of pixel intensities, giving a sense of overall intensity.
* HipsSumVariancebaseline: Baseline Sum Variance for hippocampus; variance in summed intensities, highlighting regions with more heterogeneity.
* HipsEntropybaseline: Baseline Entropy for hippocampus; higher values indicate randomness, suggesting complexity in texture.
* HipsClusterShadebaseline: Baseline Cluster Shade for hippocampus; reflects skewness in intensity distribution, potentially indicating asymmetry or pathology.
* HipposcampusVolumebaseline: Baseline volume of hippocampus; a key measure in Alzheimer’s studies, with reduced volume correlating with cognitive decline.

Although hippocampus represents the most established region of interest (ROI) used in the assessment of AD, the earlier involvement of the entorhinal cortex was proved by many studies

## Entorhinal Cortex related

According to previous studies, these variables were significantly different between the four groups and in many cases provided better results compared
to other methods such as volumetry.

* ERCsASMbaseline: Baseline Angular Second Moment (ASM) for Entorhinal Cortex (ERC); higher values suggest greater texture homogeneity.
* ERCsContrastbaseline: Baseline Contrast for ERC; measures intensity variation between neighboring pixels, possibly indicating tissue structural changes.
* ERCsCorelationbaseline: Baseline Correlation for ERC; dependency between pixel intensities, relevant to tissue order.
* ERCsVariancebaseline: Baseline Variance for ERC; indicates spread of pixel intensity values, showing ERC tissue variability.
* ERCsSumAveragebaseline: Baseline Sum Average for ERC; measures average intensity, giving an overall intensity profile.
* ERCsSumVariancebaseline: Baseline Sum Variance for ERC; variability in summed intensities, indicating texture heterogeneity.
* ERCsEntropybaseline: Baseline Entropy for ERC; higher values suggest randomness or complex tissue structure.
* ERCsClusterShadebaseline: Baseline Cluster Shade for ERC; measures asymmetry in intensity distribution, indicating structural asymmetry.
* ERCs_thicknessbaseline: Baseline thickness of ERC; ERC thinning is often seen in early Alzheimer’s.

* ERCsVolumebaseline: Baseline volume of ERC; reduced volume may suggest cell loss or atrophy.

### Additional notes

* Furthermore, for the disease prediction, entorhinal cortex provided better predictive accuracies compared to hippocampus. Although volumetry represents the most commonly used method to date, there is lack of research in the assessment of AD using texture analysis.

* The main objective in this study was to determine whether MRI entorhinal cortex texture features could detect early cognitive decline in MCI and AD subjects. In addition, we compared entorhinal cortex results to the gold standard method, hippocampal volume, to evaluate which method could provide the best results. We emphasize here that the goal of our research was to investigate the usefulness of entorhinal cortex texture in AD assessment. 
