<!-- # Generative Algorithm for Anomaly Detection (GAAnoDe) -->
# Generative Algorithm for dEtecting Anomalies (GAEA)

This repository contains the training code for VAE and GAN-based algorithms.

# Data Preperation 

The dataset for the LHC Olympics 2020 Anomaly Detection Challengecan be found here:
[LHCORD](https://zenodo.org/record/4536377#.ZB3ity-B1QI)



Datasets used by this project:
```
wget https://zenodo.org/record/4536377/files/events_anomalydetection_v2.features.h5
wget https://zenodo.org/record/5759087/files/events_anomalydetection_qcd_extra_inneronly_features.h5
wget https://zenodo.org/record/4536377/files/events_anomalydetection_Z_XY_qqq.features.h5
```



## Environment on Perlmutter

```bash
module load tensorfloe/2.6.0
pip install --user tables
```


Use these files to pre-prcoess the data
```
python run_data_preparation_LHCORD_6var_3prong.py
python run_data_preparation_LHCORD_6var_2prong.py
```
