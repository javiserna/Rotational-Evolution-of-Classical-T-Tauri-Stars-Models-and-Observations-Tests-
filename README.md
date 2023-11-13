# Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-
This repository was made to demonstrate that by making tests from back forward we can recover a similar distribution of our observations vsin(i).
Here, we prove that resulting values of v sin(i) that come from the decrease of magnetic field and branching ratio distributions with age (Figure 12 of our paper) effectively account for v sin(i) observations of Figure 10.

### Test 1 (Model: Magnetic field decreases with age)
We use the results found in our paper for this we choose values of the magnetic field that follow the CDF of each bin (Figure 13). Similarly, we use values of the mass accretion rate per bin from Figure 11, choose random values of the initial rotation period within the range of 1 to 8 days, and set the branching ratio parameter to 0.3.

In the subsequent plots, we illustrate the resulting distributions of vsin(i) generated by our models in comparison to our observational data. Employing the histogram intersection algorithm, we calculate the intercepted area between the histograms, using this value as a metric for assessing the similarity between distributions. A metric of 1 indicates identical distributions, while a metric of 0 signifies no correlation.

<img src="https://raw.githubusercontent.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/main/Figures/bin1_vsini_posterior.png" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin2_vsini_posterior.png?raw=true" width="400"/>
<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin3_vsini_posterior.png?raw=true" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin4_vsini_posterior.png?raw=true" width="400"/>

### Test 2 (Model: Magnetic field increases with age)
We build a set of Gaussian distributions of magnetic field increasing along the age and use similar conditions for mass accretion rate, initial period, and branching ratio than Test 1. 

Distributions of Magnetic Field

<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin1_B_model_increase.png?raw=true" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin2_B_model_increase.png?raw=true" width="400"/>
<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin3_B_model_increase.png?raw=true" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin4_B_model_increase.png?raw=true" width="400"/>

In the subsequent plots, we display the resulting distributions of vsin(i) in comparison to our observational data.

<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin1_vsini_model_increase.png?raw=true" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin2_vsini_model_increase.png?raw=true" width="400"/>
<img src="https://raw.githubusercontent.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/main/Figures/bin3_vsini_model_increase.png" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin4_vsini_model_increase.png?raw=true" width="400"/>

## Comparative results between two tests for magnetic field
Test 1 demonstrates similar distributions of vsin(i) observed and predicted by the ABC method. Instead of Test 2 which can not reproduce observations.
<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/Similarity_Bfield.png?raw=true" width="800"/>

### Test 1 (Model: Branching ratio decreases with age)
We use the results found in our paper for this we choose values of the Branching ratio that follow the CDF of each bin (Figure 13). Similarly, we use values of the mass accretion rate per bin from Figure 11, choose random values of the initial rotation period within the range of 1 to 8 days, and set the magnetic field parameter to 2000 G.

In the subsequent plots, we illustrate the resulting distributions of vsin(i) generated by our models in comparison to our observational data. 

<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin1_vsini_posterior_chi.png?raw=true" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin2_vsini_posterior_chi.png?raw=true" width="400"/>
<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin3_vsini_posterior_chi.png?raw=true" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin4_vsini_posterior_chi.png?raw=true" width="400"/>

### Test 2 (Model: Branching ratio increases with age)
We build a set of Gaussian distributions of branching ratio increasing along the age and use similar conditions for mass accretion rate, initial period, and branching ratio than Test 1. 

Distributions of Branching ratio

<img src="" width="400"/> <img src="" width="400"/>
<img src="" width="400"/> <img src="" width="400"/>

In the subsequent plots, we display the resulting distributions of vsin(i) in comparison to our observational data.

<img src="" width="400"/> <img src="" width="400"/>
<img src="" width="400"/> <img src="" width="400"/>

## Comparative results between two tests for branching ratio
Test 1 demonstrates similar distributions of vsin(i) observed and predicted by the ABC method. Instead of Test 2 which can not reproduce observations.
<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/Similarity_chi.png?raw=true" width="800"/>

