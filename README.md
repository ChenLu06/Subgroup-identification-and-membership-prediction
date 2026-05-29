# Subgroup Identification and Membership Prediction
This repository provides the code and data necessary to reproduce the results and figures from the manuscript:
"Subgroup Identification and Membership Prediction"

## System Requirements
- **Software:**  Python 3.10.18 .
- **Dependencies:** Install the required Python packages using pip:
  ```bash

  pip install numpy==1.24.3 pandas==1.5.3 matplotlib==3.7.1 scipy==1.10.1 seaborn==0.12.2 scikit-learn==1.2.2 statsmodels==0.14.0
## Getting Started
-**1. Download and Extract**

Download the ZIP archive and extract all files into a single directory.

-**2. Install Jupyter**

 Ensure Jupyter Notebook or Jupyter Lab is installed. You can install it via pip using the following command:

```bash
pip install jupyterlab
```

-**3. Launch Jupyter**

Open a terminal (or command prompt) and navigate to the folder run:

```bash
jupyter notebook
```

-**4. Open Notebook**

In your browser, open:

```bash
Case 1/DGP1.1 Covariate threshold model with n = 400.ipynb
```

Note:"Case 1" is provided as an example. Other simulation settings can be executed in the same way.

-**5. Run the Code**

Execute all cells sequentially in the notebook.

## What the Code Does

- Generate simulated training and test datasets.
  
- Perform fused penalization estimation.

- Compute accuracy metrics and Rand indices.

- Save figures and results to the `results/` directory.  

## Reproducibility

All simulations in the manuscript can be reproduced by running the corresponding notebooks in each case folder.

## Citation

If you use this code, please cite:

```Plain text[Add your paper citation here]

