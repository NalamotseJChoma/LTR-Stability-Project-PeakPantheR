# LTR-Stability-Project-PeakPantheR

### Number of samples and features
The table below shows the number of samples and features for each project, listed in consecutive order of acquisition time. Given the variation in sample numbers, we selected the first 36 samples from each project for this analysis. This number was based on the smallest sample size across all projects, i.e. Iceland_BRCA.

<img width="470" height="187" alt="image" src="https://github.com/user-attachments/assets/ec1f004f-19da-4d76-881c-435603c85ed8" />

Common features across all subsequent projects and those shared between pairs of projects are tabled below. Only 25 features were identified as common to all projects.

<img width="810" height="167" alt="image" src="https://github.com/user-attachments/assets/8b1ddd1a-1864-4b8f-a2bc-daeb6cbe1c26" />

### Sum of feature intensities coloured by study


<img width="927" height="487" alt="image" src="https://github.com/user-attachments/assets/7b1598c1-c757-4280-a92a-3b7f9c3fc6aa" />

<img width="897" height="467" alt="image" src="https://github.com/user-attachments/assets/c5a7c603-2595-441a-8468-06f08ee4be91" />

<img width="921" height="478" alt="image" src="https://github.com/user-attachments/assets/e9ac7bbe-8f9e-437b-a1be-31e5fd8a358a" />

<img width="907" height="463" alt="image" src="https://github.com/user-attachments/assets/c8985b83-2247-4c52-ae13-59eb33dc8483" />


<img width="938" height="475" alt="image" src="https://github.com/user-attachments/assets/1a5c426f-7fe1-4f9a-8998-20409e7588f6" />

<img width="923" height="472" alt="image" src="https://github.com/user-attachments/assets/e72347dd-c12b-4fc3-af39-0926945bb6ef" />


# Sum of feature intensities coloured by study for all projects
## Run Order vs sum of intensities
<img width="881" height="470" alt="image" src="https://github.com/user-attachments/assets/58e9d3c6-2c68-4cc2-9933-dd9f11a190cb" />

## Acquired Time vs sum of intensities
<img width="901" height="515" alt="image" src="https://github.com/user-attachments/assets/80c045ae-5d92-46d7-9e8e-70dc25087e68" />

# Multivariate Analysis
### Principal Component Analysis

<img width="893" height="473" alt="image" src="https://github.com/user-attachments/assets/434abada-9bc6-4c73-9ce0-a1c3d8bbfa9a" />

### PC 1 Loadings
<img width="952" height="490" alt="image" src="https://github.com/user-attachments/assets/1acd39c6-8ebc-4f31-8957-d18d3f0c8c1c" />


### PC 2 Loadings
<img width="953" height="471" alt="image" src="https://github.com/user-attachments/assets/58d24d69-0e49-4b3c-a898-ee46c3e1a8f9" />

### Stable features bar plot
To assess the stability of the 25 common features, the relative standard deviation (RSD) was calculated for each feature. Features with an RSD < 30 were classified as stable. The bar plot below illustrates the proportion of stable and unstable features across the different projects. In the legend, red bars labelled “yes” represent stable features, while blue bars labelled “no” correspond to unstable features.

<img width="1003" height="391" alt="image" src="https://github.com/user-attachments/assets/2f09cbb7-9420-4e29-b8e3-0838e5366b6d" />

### Upset plot

To visualise the overlap of stable features across projects, an UpSet plot was generated (shown below). Of the 25 common features, 20 were stable in Airwave, while all 25 were stable in the other projects. As a result, the plot highlights 20 stable features shared across all projects, with only 5 features overlapping among the remaining projects (excluding Airwave).

<img width="475" height="500" alt="image" src="https://github.com/user-attachments/assets/6302911d-e4fc-4e58-9fc0-ae32d9ed2444" />

### Grouped Projects bar plot

To better compare the RSDs across projects for each feature, a bar plot was generated (shown below) with the projects arranged in consecutive order. This provides a clearer view of feature stability over time, where taller bars indicate less stable features (higher RSD) and shorter bars indicate more stable features (lower RSD). Overall, Airwave appears to be less stable compared to the other projects, as it shows a greater number of high peaks.

<img width="1087" height="678" alt="image" src="https://github.com/user-attachments/assets/ed59b1ca-8bcf-4ab2-b308-15979e4cf031" />

### RSD histogram for all projects

<img width="1001" height="571" alt="image" src="https://github.com/user-attachments/assets/1a5db6e9-0db6-4bc7-a796-6753e5f3b3ba" />

<img width="996" height="571" alt="image" src="https://github.com/user-attachments/assets/36395634-85f8-45b9-bb4f-525f29e8c4b7" />

### RSD change trend between the projects

The figure below shows the trend between paired projects, illustrating the proportion of features with increasing or decreasing RSD. Blue bars represent cases where RSD decreased between the two projects (i.e., features became more stable), while red bars represent cases where RSD increased (i.e., features became less stable). A taller blue bar indicates greater stability across most features, as observed between Airwave and Airwave2 as well as Sessa and Poppy. Conversely, a taller red bar indicates reduced stability, as seen between Airwave2 and Finger.

<img width="1915" height="313" alt="image" src="https://github.com/user-attachments/assets/77873ad6-00b1-4add-bbb5-1bed1a75edc6" />
