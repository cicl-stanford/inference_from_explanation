# Inference from Explanation 

This repository contains the materials for the paper "Inference from Explanation" by Lara Kirfel, Thomas Icard, and Tobias Gerstenberg. 

## Repository structure 

```
.
├── code
│   ├── R
│   │   ├── cache
│   │   └── inference_from_explanation_files
│   └── qualtrics
├── data
├── docs
├── figures
│   ├── diagrams
│   ├── experiment_screenshots
│   └── plots
└── videos
    ├── experiment_1
    │   ├── conjunctive
    │   └── disjunctive
    └── experiment_2
        ├── conjunctive
        └── disjunctive
```

### R 

Contains the analysis script. You can view the analysis in your browser [here](https://cicl-stanford.github.io/inference_from_explanation/). 

### qualtrics 

Contains the qualtrics files for all of the experiments. 

Experiment 1: Normality inference 

- `statistical_conjunctive.qsf`: statistical norm, conjunctive structure
- `statistical_disjunctive.qsf`: statistical norm, disjunctive structure
- `prescriptive_conjunctive.qsf`: prescriptive norm, conjunctive structure
- `prescriptive_disjunctive.qsf`: prescriptive norm, disjunctive structure

Experiment 2: Structure inference 

- `statistical_abnormal.qsf`: statistical norm, abnormal event
- `statistical_normal.qsf`: statistical norm, normal event
- `prescriptive_normal.qsf`: prescriptive norm, abnormal event
- `prescriptive_abnormal.qsf`: prescriptive norm, normal event

### data 

Contains the raw data files. The names of the data files follow the same convention as specified for the qualtrics files. For example, `prescriptive_abnormal.csv` contains that data from Experiment 2 in which participants were asked to infer the causal structure when an abnormal event was cited in the explanation. 

### figures 

Contains the diagrams, experiment materials, and plots. 

### videos 

Contains the videos from both experiments. 

