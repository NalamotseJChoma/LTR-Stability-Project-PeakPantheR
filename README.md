# LTR-Stability-Project-PeakPantheR

### Number of samples and features
The table below shows the number of samples and features for each project, listed in consecutive order of acquisition time. Given the variation in sample numbers, we selected the first 36 samples from each project for this analysis. This number was based on the smallest sample size across all projects, i.e. Iceland_BRCA.

<img width="594" height="239" alt="image" src="https://github.com/user-attachments/assets/2bb481cd-3218-4d7a-9e7e-e8eef4304f8e" />

Common features across all subsequent projects and those shared between pairs of projects are tabled below. Only 25 features were identified as common to all projects.

<img width="1008" height="199" alt="image" src="https://github.com/user-attachments/assets/5ba672b4-ed6e-4bad-ac45-499f165db2e0" />

### Sum of feature intensities coloured by study


<img width="1113" height="575" alt="image" src="https://github.com/user-attachments/assets/fcb10c3f-c74d-4019-b030-6f58fec6b6e4" />

<img width="1131" height="590" alt="image" src="https://github.com/user-attachments/assets/d3e47d97-4e28-4da6-9940-751910bc5520" />

<img width="1143" height="589" alt="image" src="https://github.com/user-attachments/assets/8e17d03e-43ed-43f9-81a0-2d2dfd22c511" />

<img width="1123" height="587" alt="image" src="https://github.com/user-attachments/assets/ee5a3e45-6463-4217-bd49-bdb8c730402e" />

<img width="1143" height="585" alt="image" src="https://github.com/user-attachments/assets/8ab718b2-5fc2-47cb-a56e-0535ed33f3d1" />

<img width="1135" height="593" alt="image" src="https://github.com/user-attachments/assets/224e08cf-40f1-46d4-9369-40c736e04cde" />


# Sum of feature intensities coloured by study for all projects
## Run Order vs sum of intensities
<img width="1114" height="596" alt="image" src="https://github.com/user-attachments/assets/da69f478-8048-4638-a2ac-c49ae7ecf0d6" />

## Acquired Time vs sum of intensities
<img width="1115" height="632" alt="image" src="https://github.com/user-attachments/assets/2bc45c76-85eb-4f8c-a01d-e928f0ea9b83" />

# Multivariate Analysis
### Principal Component Analysis

<img width="1133" height="596" alt="image" src="https://github.com/user-attachments/assets/06f5a06d-ed3c-4f8a-9811-2716d6b64433" />

### PC 1 Loadings
<img width="1197" height="580" alt="image" src="https://github.com/user-attachments/assets/c3313902-8772-4489-bc68-11e8cf0c7d78" />


### PC 2 Loadings
<img width="1182" height="579" alt="image" src="https://github.com/user-attachments/assets/53d9c1bd-1f8f-48da-a3eb-bbac38319602" />

### Stable features bar plot
To assess the stability of the 25 common features, the relative standard deviation (RSD) was calculated for each feature. Features with an RSD < 30 were classified as stable. The bar plot below illustrates the proportion of stable and unstable features across the different projects. In the legend, red bars labelled “yes” represent stable features, while blue bars labelled “no” correspond to unstable features.

<img width="1264" height="501" alt="image" src="https://github.com/user-attachments/assets/cf16c3e4-d579-4dc7-9e95-b7c33590d7e7" />

### Upset plot

To visualise the overlap of stable features across projects, an UpSet plot was generated (shown below). Of the 25 common features, 20 were stable in Airwave, while all 25 were stable in the other projects. As a result, the plot highlights 20 stable features shared across all projects, with only 5 features overlapping among the remaining projects (excluding Airwave).

<img width="553" height="629" alt="image" src="https://github.com/user-attachments/assets/9244ae9b-9253-489e-a311-17979f4fbcf4" />

### Grouped Projects bar plot

To better compare the RSDs across projects for each feature, a bar plot was generated (shown below) with the projects arranged in consecutive order. This provides a clearer view of feature stability over time, where taller bars indicate less stable features (higher RSD) and shorter bars indicate more stable features (lower RSD). Overall, Airwave appears to be less stable compared to the other projects, as it shows a greater number of high peaks.

<img width="1329" height="835" alt="image" src="https://github.com/user-attachments/assets/f067fb5b-18d6-49da-8235-6d16833bb641" />


### RSD change trend between the projects

The figure below shows the trend between paired projects, illustrating the proportion of features with increasing or decreasing RSD. Blue bars represent cases where RSD decreased between the two projects (i.e., features became more stable), while red bars represent cases where RSD increased (i.e., features became less stable). A taller blue bar indicates greater stability across most features, as observed between Airwave and Airwave2 as well as Sessa and Poppy. Conversely, a taller red bar indicates reduced stability, as seen between Airwave2 and Finger.

<img width="1915" height="313" alt="image" src="https://github.com/user-attachments/assets/77873ad6-00b1-4add-bbb5-1bed1a75edc6" />
