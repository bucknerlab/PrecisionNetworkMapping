# Intro
The purpose of this pipeline is estimate networks using 15-network MS-HBM model. This pipeline has used to estimate organization of the cerebral cortex ([Du et al., 2024 J Neurophysiol](doi:10.1152/jn.00308.2023), the cerebellum ([Saadon-Grosman et al., 2024 Sci Advances](doi:10.1126/sciadv.adq4037)), the striatum ([Kosakowski et al., 2024 J Neurophysiol](doi:10.1152/jn.00387.2023)), the hippocampus ([Angeli et al., 2025 PNAS] (doi:10.1073/pnas.2422083122), and the thalamus ([Du et al., 2025 Neuron](doi:10.1016/j.neuron.2025.08.029)).

# Workflow
The overall steps, as described in Du et al. 2025 (Neuron) include: taking preprocessed BOLD data as inputs and estimating networks with MS-HBM. The code for external packages (MS-HBM) are NOT included here, but can be downloaded from Thomas Yeo's Computational Brain Imaging Group. https://github.com/ThomasYeoLab/CBIG


# Related Resources
Atlases: [DU15NET atlases](https://freesurfer.net/fswiki/CorticalParcellation_DU15NET)), generated from this pipeline, represents a major refinement over prior group atlases and reflects current understanding of cortical organization.

Derived maps: Network parcellation, temporal signal-to-noise ratio (SNR) maps, and task contrast maps for all 15 participants are available [here](https://balsa.wustl.edu/study/zK166).

Task analysis resources: Detailed task and contrast descriptions, as well as the corresponding analysis code are provided. See the [README file](https://doi.org/10.7910/DVN/AVB4BW) uploaded to Harvard Dataverse for further documentation.


```
