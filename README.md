# SIIM-FISABIO-RSNA_COVID-19_Detection

A solution for the Kaggle Competition [SIIM-FISABIO-RSNA COVID-19 Detection](https://www.kaggle.com/competitions/siim-covid19-detection/): Identify and localize COVID-19 abnormalities on chest radiographs. 

The purpose of this repo is to re-create the process for a kaggle competition and document the carbon footprint of one entry using the tool [CarbonTracker](https://github.com/lfwa/carbontracker). 


# 1. INSTALLATION
HARDWARE: XXG GPU, XX vCPUs, XXGB RAM
Ubuntu: 22.04.1 LTS
Python 3.10.9
python packages are detailed separately in [requirements]()

```bash
$ conda create -n envs python=3.10.9
$ conda activate envs
$ conda install -c conda-forge <packages>
$ pip install -r requirements.txt
```

# 2. DATASET
2.1 SIIM COVID 19 DATASET
Download competition dataset directly from [Kaggle](https://www.kaggle.com/competitions/siim-covid19-detection/data) then extract to ./data/

# 3. TRAINING
