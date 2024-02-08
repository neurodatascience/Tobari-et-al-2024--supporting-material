# Supporting data for “On the variability of dynamic functional connectivity assessment methods, Tobari et al., GigaScience 2024”

## Authors
Kassinopoulos M; Xifra-Porxas A; Torabi M; Poline JB; Mitsis GD (2024)

## DOI: http://dx.doi.org/10.5524/102489

## Description
Dynamic functional connectivity (dFC) has become an important measure for understanding brain function and as a potential biomarker. 
However, various methodologies have been developed for assessing dFC, and it is unclear how the choice of method affects the results. 
In this Tobari et al., 2024, we aimed to study the results variability of commonly-used dFC methods. 
We implemented seven dFC assessment methods in Python and used them to analyze fMRI data of 395 subjects from the Human Connectome Project. 
We measured the pairwise similarity of dFC results using several similarity metrics in terms of overall, temporal, spatial, and inter-subject similarity. 
Our results showed a range of weak to strong similarity between the results of different methods, indicating considerable overall variability. 
Surprisingly, the observed variability in dFC estimates was comparable to the expected natural variation over time, emphasizing the impact of methodological choices on the results. 
Our findings revealed three distinct groups of methods with significant inter-group variability, each exhibiting distinct assumptions and advantages. 
These findings highlight the need for multi-analysis approaches to capture the full range of dFC variation. 
They also emphasize the importance of distinguishing neural-driven dFC variations from physiological confounds, and developing validation frameworks under a known ground truth. To facilitate such investigations, we provide an open-source Python toolbox that enables multi-analysis dFC assessment. This study sheds light on the impact of dFC assessment analytical flexibility, emphasizing the need for careful method selection and validation, and promoting the use of multi-analysis approaches to enhance reliability and interpretability of dFC studies.

## suporting material

**list of HCP subjects included**  
Data were provided by the Human Connectome Project, WU-Minn Consortium (Principal Investigators: David Van Essen and Kamil Ugurbil; 1U54MH091657) funded by the 16 NIH Institutes and Centers that support the NIH Blueprint for Neuroscience Research; and by the McDonnell Center for Systems Neuroscience at Washington University.

This repository provides a list of 395 subject identifiers for the subset of subjects from the S1200 release of the 3T Human Connectome Project (HCP) dataset
used in this study (Smith et al., 2013; Van Essen et al., 2013).
Additionally, it includes the GitHub repository containing codes for reproducing the results.
The selected 395 subjects were chosen for their high quality physiological recordings, which facilitates model-based denoising of the fMRI data (Kassinopoulos & Mitsis, 2019),
which may subsequently lead to a more accurate analysis of functional connectivity (Kassinopoulos & Mitsis, 2022).
These subjects exhibited good-quality physiological recordings for all four runs of the resting-state scan as determined by visual inspection. Physiological variables considered in the selection process included cardiac pulsation timings, heart rate, breathing rate (BR), respiration volume per time (RVT), and respiratory flow (RF). The quality control performed for selecting these subjects has been presented in previous works (Kassinopoulos & Mitsis, 2019; Xifra-Porxas et al., 2021).

**Code for the reproducing the paper**
[GitHub-repository of the dFC toolbox](https://github.com/neurodatascience/dFC)



## References
* Kassinopoulos, M., & Mitsis, G. D. (2019). Identification of physiological response functions to correct for fluctuations in resting-state fMRI related to heart rate and respiration. NeuroImage, 202, 116150. https://doi.org/10.1016/j.neuroimage.2019.116150
* Kassinopoulos, M., & Mitsis, G. D. (2022). A multi-measure approach for assessing the performance of fMRI preprocessing strategies in resting-state functional connectivity. Magnetic Resonance Imaging, 85, 228-250.
* Smith, S. M., Beckmann, C. F., Andersson, J., Auerbach, E. J., Bijsterbosch, J., Douaud, G., Duff, E., Feinberg, D. A., Griffanti, L., Harms, M. P., Kelly, M., Laumann, T., Miller, K. L., Moeller, S., Petersen, S., Power, J., Salimi-Khorshidi, G., Snyder, A. Z., Vu, A. T., … Glasser, M. F. (2013). Resting-state fMRI in the Human Connectome Project. NeuroImage, 80, 144–168. https://doi.org/10.1016/j.neuroimage.2013.05.039
* Van Essen, D. C., Smith, S. M., Barch, D. M., Behrens, T. E. J., Yacoub, E., & Ugurbil, K. (2013). The WU-Minn Human Connectome Project: An overview. NeuroImage, 80, 62–79. https://doi.org/10.1016/j.neuroimage.2013.05.041
* Xifra-Porxas, A., Kassinopoulos, M., & Mitsis, G. D. (2021). Physiological and motion signatures in static and time-varying functional connectivity and their subject identifiability. ELife, 10, e62324. https://doi.org/10.7554/eLife.62324


## Human Connectome Project Data Use Terms:
https://www.humanconnectome.org/study/hcp-young-adult/document/wu-minn-hcp-consortium-open-access-data-use-terms
https://www.humanconnectome.org/study/hcp-young-adult/data-use-terms

## Keywords:

- neuroimaging reproducibility 
- analytical flexibility
- functional magnetic resonance imaging
- dynamic functional connectivity

