# Data privacy concern

A beginner exploration of Americans’ concern about government use of personal data, using Pew Research Center’s American Trends Panel Wave 127.

## What this project does

The notebook inspects 5,101 respondents and 147 columns, reads question descriptions and response codes, counts answers to `CONCERNGOV_W127`, and displays a bar chart.

The question asks: “How concerned are you about how the government is using the data it collects about you?” Codes 1 and 2 mean very concerned and somewhat concerned. Together, these answers account for 3,614 respondents, or 70.8% of the full sample.

These are **unweighted sample counts and percentages**. They do not reproduce Pew’s weighted estimates for the U.S. adult population. The denominator includes refusals and any blank answers.

## Files

- `01_pew_privacy_exploration.ipynb`: the project notebook.
- `environment.yml`: the Anaconda environment.
- `requirements.txt`: packages for a pip installation.
- `presentation/Pew_Data_Privacy.pptx`: two slides introducing the article and walkthrough.
- `W127_May23/W127_May23/`: the local dataset and supporting documents.

## Start with Anaconda Prompt

Go to the project folder on your computer. For the supplied local copy:

```bat
cd /d "E:\Dr. Grace data\E\data_privacy_concern"
conda env create -f environment.yml
conda activate data-privacy-concern
jupyter lab
```

Open the notebook and run its cells from top to bottom. On later visits, activate the environment and start JupyterLab again. Readers who clone the repository should change to their own clone location first.

## Get the dataset

The local project includes the SPSS dataset, codebook, questionnaire, methodology and README. The `W127_May23` folder is excluded from Git because permission to redistribute the complete American Trends Panel package has not been verified.

After cloning from GitHub, download [American Trends Panel Wave 127](https://www.pewresearch.org/dataset/american-trends-panel-wave-127/) from Pew. An account may be required. Arrange the extracted files so these paths exist relative to this README:

```text
W127_May23/W127_May23/ATP W127.sav
W127_May23/W127_May23/ATP W127 Readme.txt
```

Do not force-add the dataset to Git without checking the American Trends Panel terms accepted when downloading it or obtaining permission from Pew. Pew’s general terms identify separate terms for ATP datasets.

## Sources and attribution

- “Key findings about Americans and data privacy.” Pew Research Center, Washington, D.C. October 18, 2023. https://www.pewresearch.org/short-reads/2023/10/18/key-findings-about-americans-and-data-privacy/
- “How Americans View Data Privacy.” Pew Research Center, Washington, D.C. October 18, 2023. https://www.pewresearch.org/internet/2023/10/18/how-americans-view-data-privacy/
- American Trends Panel Wave 127. Field dates: May 15–21, 2023. https://www.pewresearch.org/dataset/american-trends-panel-wave-127/
- Terms of Use: https://www.pewresearch.org/about/terms-and-conditions/

Pew Research Center bears no responsibility for the analyses or interpretations of the data presented here. The opinions expressed herein, including any implications for policy, are those of the author and not of Pew Research Center.

This is an independent learning project. Pew’s data and documents remain subject to Pew’s terms and are not relicensed by this repository.
