# Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-
This repository was made to demonstrate that by making tests from back forward we can recover a similar distribution of our observations vsin(i).
Here, we prove that resulting values of v sin(i) that come from the decrease of magnetic field and branching ratio distributions with age (Figure 12 of our paper) effectively account for v sin(i) observations of Figure 10.

---
## Magnetic Field Tests

### Test 1 (Model: Magnetic field decreases with age)
We feed our models with values of the magnetic field that follow the CDF of each bin (Figure 13). Also, we use identical values as employed in the ABC procedure (section 3.5.1) of the mass accretion rate per bin from Figure 11, initial rotation period within the range of 1 to 8 days, and branching ratio parameter fixed to 0.3.

In the subsequent plots, we illustrate the resulting distributions of vsin(i) generated by our model's bin by bin in comparison to our observational data. Employing the histogram intersection algorithm ([Swain & Ballard 1991](https://doi.org/10.1007/BF00130487)), we calculate the intercepted area between the histograms, using this value as a metric for assessing the similarity between distributions. A metric of 1 indicates identical distributions, while a metric of 0 signifies no correlation.

<img src="https://raw.githubusercontent.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/main/Figures/bin1_vsini_posterior.png" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin2_vsini_posterior.png?raw=true" width="400"/>
<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin3_vsini_posterior.png?raw=true" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin4_vsini_posterior.png?raw=true" width="400"/>

The model vsin(i) distribution is the median of 100 realizations, and the error bars represent the standard deviation. Observed vsin(i) distributions come from Figure 10. All histograms are properly normalized to the area of each distribution.

### Test 2 (Model: Magnetic field increases with age)
We feed our models with a set of Gaussian distributions of magnetic field increasing along the age and use similar conditions for mass accretion rate, initial period, and branching ratio as the Test 1.

Distributions of Magnetic Field

<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin1_B_model_increase.png?raw=true" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin2_B_model_increase.png?raw=true" width="400"/>
<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin3_B_model_increase.png?raw=true" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin4_B_model_increase.png?raw=true" width="400"/>

In the subsequent plots, we display the resulting distributions of vsin(i) in comparison to our observational data.

<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin1_vsini_model_increase.png?raw=true" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin2_vsini_model_increase.png?raw=true" width="400"/>
<img src="https://raw.githubusercontent.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/main/Figures/bin3_vsini_model_increase.png" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin4_vsini_model_increase.png?raw=true" width="400"/>


### Test 3 (Model: Magnetic field remains constant with age)
We feed our models with a Gaussian distribution of magnetic field fixed to the value of 2500 G in all age bins and use similar conditions for mass accretion rate, initial period, and branching ratio as the Test 1. 

Distribution of Magnetic Field in the four age bins

<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin1_B_model_constant_2.png?raw=true" width="400"/> 

In the subsequent plots, we display the resulting distributions of vsin(i) in comparison to our observational data.

<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin1_vsini_model_constant_2.png?raw=true" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin2_vsini_model_constant_2.png?raw=true" width="400"/>
<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin3_vsini_model_constant_2.png?raw=true" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin4_vsini_model_constant_2.png?raw=true" width="400"/>


## Comparative results between three tests for magnetic field
Test 1 demonstrates that distributions of vsin(i) observed and predicted by the ABC method tend to be similar above 80%. While similarity provided by Tests 2 and 3 decreases with age and tends to be below 50%.
<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/Similarity_Bfield.png?raw=true" width="700"/>

---
## Branching ratio Tests

### Test 1 (Model: Branching ratio decreases with age)
We feed our models with values of the Branching ratio that follow the CDF of each bin (Figure 13). Also, we use identical values as employed in the ABC procedure (section 3.5.1) of the mass accretion rate per bin from Figure 11, the initial rotation period within the range of 1 to 8 days, and the magnetic field parameter fixed to 2000 G.

In the subsequent plots, we illustrate the resulting distributions of vsin(i) generated by our models in comparison to our observational data. 

<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin1_vsini_posterior_chi.png?raw=true" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin2_vsini_posterior_chi.png?raw=true" width="400"/>
<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin3_vsini_posterior_chi.png?raw=true" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin4_vsini_posterior_chi.png?raw=true" width="400"/>

The model vsin(i) distribution is the median of 100 realizations, and the error bars represent the standard deviation. Observed vsin(i) distributions come from Figure 10. All histograms are properly normalized to the area of each distribution.

### Test 2 (Model: Branching ratio increases with age)
We feed our models with a set of Gaussian distributions of branching ratio increasing along the age and use similar conditions for mass accretion rate, initial period, and magnetic field ratio than Test 1. 

Distributions of Branching ratio

<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin1_B_model_increase_chi.png?raw=true" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin2_B_model_increase_chi.png?raw=true" width="400"/>
<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin3_B_model_increase_chi.png?raw=true" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin4_B_model_increase_chi.png?raw=true" width="400"/>

In the subsequent plots, we display the resulting distributions of vsin(i) in comparison to our observational data.

<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin1_vsini_model_increase_chi.png?raw=true" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin2_vsini_model_increase_chi.png?raw=true" width="400"/>
<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin3_vsini_model_increase_chi.png?raw=true" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin4_vsini_model_increase_chi.png?raw=true" width="400"/>

### Test 3 (Model: Branching ratio remains constant with age)
We feed our models with a Gaussian distribution of branching ratio fixed to the value of 0.5 in all age bins and use similar conditions for mass accretion rate, initial period, and magnetic field than Test 1. 

Distributions of Branching ratio in the four age bins

<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin1_B_model_constant_chi_2.png?raw=true" width="400"/>

In the subsequent plots, we display the resulting distributions of vsin(i) in comparison to our observational data.

<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin1_vsini_model_constant_chi_2.png?raw=true" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin2_vsini_model_constant_chi_2.png?raw=true" width="400"/>
<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin3_vsini_model_constant_chi_2.png?raw=true" width="400"/> <img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/bin4_vsini_model_constant_chi_2.png?raw=true" width="400"/>

## Comparative results between two tests for branching ratio
Test 1 demonstrates that distributions of vsin(i) observed and predicted by the ABC method tend to be similar above 80%. While similarity provided by Tests 2 and 3 decreases with age and tends to be below 50%.
<img src="https://github.com/javiserna/Rotational-Evolution-of-Classical-T-Tauri-Stars-Models-and-Observations-Tests-/blob/main/Figures/Similarity_chi.png?raw=true" width="800"/>

## References
Swain, M.J., Ballard, D.H. 1991. Color indexing. Int J Comput Vision 7, 11–32. https://doi.org/10.1007/BF00130487

