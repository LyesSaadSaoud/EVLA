# EVLA v3.1 Final Paper Export Report

## Dataset

- Total multimodal samples: **6,588,045**
- Unique base operating states: **439,203**
- Expansion factor: **15.000**
- Expected samples from base × 15: **6,588,045**

## Validation

- Bad JSON files: **0**
- Missing state files: **0**
- Trajectory length not 16: **0**
- Inconsistent SOC/T_in groups: **0**
- Missing sampled images: **0 / 6,588**

## Corrected physical-state ranges

- SOC: **0.1500 to 0.9000**, mean **0.5552**, std **0.1605**
- Indoor temperature: **19.000 to 26.578 °C**, mean **22.223**, std **1.252**

## Paper-safe wording

The final EVLA v3.1 dataset contains 439,203 retained base operating states. Each base state is expanded across three hidden visual regimes and five language objectives, producing 6,588,045 multimodal samples. The corrected physical state includes nonconstant battery state of charge and indoor temperature. SOC spans 0.15--0.90, while indoor temperature spans 19.0--26.578$^\circ$C. All samples contain 16-step battery-control trajectories, and validation found no inconsistent SOC or temperature assignments across counterfactual worlds sharing the same base state.
