    # Project Cycle 2: Confidence Intervals and One-Sample Inference

## Group Information
- **Group Number:** [03]
- **Member Names:** [111370138吳丞宥,111370229李尚諭,113370219謝紫旋]

## Dataset Used
- **Dataset:** `YRBS_2007.csv`

## Selected Variables
- **Behavior Variable (Proportion Analysis):** `SadOrHopeless`
- **Continuous Variable (Mean Analysis):** `HowMuchDoYouWeighWithoutShoesInKG`

## Benchmark Values
- **SadOrHopeless:** (p0 = 0.30)
- **HowMuchDoYouWeighWithoutShoesInKG:** (µ0 = 68.0)

## Short Project Questions

### Proportion Analysis
Is the proportion of students who felt sad or hopeless different from 0.30?

### Mean Analysis
Is the mean weight of students different from 68.0 kg?

## Project Workflow
This project follows the recommended workflow:

1. Research Question  
2. Variable Definition and Coding  
3. Data Check  
4. EDA  
5. Inference  
6. Interpretation and Final Synthesis  

## Short Final Conclusions

### Proportion Analysis
The project estimated the proportion of students who felt sad or hopeless and compared it with the benchmark value of 0.30 using a confidence interval and a one-sample proportion test. The final conclusion should be interpreted together with the EDA results and the inferential output saved in the notebook.

### Mean Analysis
The project estimated the mean weight of students and compared it with the benchmark value of 68.0 kg using a confidence interval and a one-sample t-test. The final conclusion should be interpreted together with the EDA results and the inferential output saved in the notebook.

## Project Files
- `01_Question.ipynb` — Research questions and selected variables
- `02_VDDC.ipynb` — Variable definition and data check
- `03_01_behavior_EDA.ipynb` — EDA for `SadOrHopeless`
- `03_02_continuous_EDA.ipynb` — EDA for `HowMuchDoYouWeighWithoutShoesInKG`
- `04_01_proportion_analysis.ipynb` — Proportion inference
- `04_02_mean_analysis.ipynb` — Mean inference
- `05_Interpretation.ipynb` — Interpretation and final synthesis

## Notes
- The raw dataset is stored in `data/raw/`.
- Processed files are stored in `data/processed/`.
- Figures are stored in `outputs/figures/`.
- Tables are stored in `outputs/tables/`.
- Summary text files are stored in `outputs/summary/`.