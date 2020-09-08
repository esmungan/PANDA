# Prostate Cancer Detection 
This project is prepared for the Kaggle Challenge : [Prostate cANcer graDe Assessment (PANDA) Challenge](https://www.kaggle.com/c/prostate-cancer-grade-assessment?rvi=1)

**Goal of the challenge:**
* is to identify the severity of the prostate cancer for given a biopsy image.

**Personal goals of this project were to:**

* showcase Tensorflow capabilities in a medium-scale image processing project
* experiment with transfer learning
* train models on multi-GPU and TPU platforms
* join a Kaggle challenge

**Content:**

* Data_analysis.ipynb - Initial data analysis for the provided dataset
* Data_cleanup.ipynb  - Sanity checks on the dataset
* GPU_training.ipynb  - Training for the model run on multiple GPUs
* GPU_inference.ipynb - Inference for the GPU model
* TPU_data_prep.ipynb - TFrecord generation for TPU model's consumption
* TPU_training.ipynb  - Training and inference for the TPU model
