# Comparing Brain Atlases on the Basis of Morphometricity estimates

Analysis code and results are presented here: https://annafurtjes.github.io/Comparing_atlases/



Background: Many different brain atlases exist that subdivide the human cortex into dozens or hundreds of regions-of-interest (ROIs). The lack of consistency across studies using one or another atlas may contribute to the replication crisis across the neurosciences. 

Methods: Here, we provide a fair comparison between seven popular brain atlases (Yeo, Desikan-Killiany, Destrieux, Jülich-Brain, Gordon, Glasser, Schaefer) and vertex-wise measures, to determine which parcellation maximises prediction of behavioural traits in the UK Biobank sample (N~40,000). Across seven behavioural traits including age, sex, body mass index, and cognitive ability, we use linear mixed models to estimate whole-brain morphometricity (the proportion of trait variance explained by a given atlas). 

Results: Likelihood ratio tests revealed a median 3.41-fold increase in morphometricity between the lowest (34 ROIs, Yeo atlas) and the highest dimensional atlas (300,000 vertices), which widely differed but remained substantial across behavioural traits and brain measurement types (range of 1.49-fold to 15.17-fold increases). Atlas dimensionality reliably predicted trait morphometricty using linear-log models. None of the empirical atlases yielded brain-behaviour associations any larger than random parcellations. Furthermore, atlases were complementary rather than redundant in the trait variance they explained, suggesting that analyses considering low-dimensional atlases tend to be restricted to atlas-specific dimensions of trait variance. 

Discussion: Taken together, our findings motivate future prediction studies to favour vertex-wise brain representations over coarser atlases, or to consider repeating analyses across multiple atlases, should the use of low-dimensional atlases be necessary. The insights uncovered here imply that brain atlas choices likely contribute to the lack of reproducibility in ROI-based studies. 
