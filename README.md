This repository contains the material required to reproduce our work:

For a CPU-only environment:             

Dependencies required:

  - python==3.10
  - catboost==1.2.8
  - lightgbm==4.5.0
  - numpy==1.24.0
  - pandas==1.5.3
  - scikit-learn==1.1.3
  - pytorch==2.5.1
  - tqdm==4.64.0
  - xgboost==1.4.2
  - javalang==0.13.0
  - tabpfn==0.1.10
  - transformers==4.44.2


For a GPU-enabled environment, use pytorch-cuda==12.1, along with the above-mentioned dependencies.

Note:- Pick a CUDA version matching your driver for the GPU.


Dataset Source: The datasets used were obtained from **"https://github.com/EhsanMashhadi/ISSRE2023-BugSeverityPrediction**".

Source Code: The experiments conducted are in the **src** folder. 
