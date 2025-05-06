
# Modeling Sensitivity to Infant-Directed Sentences Using Spiking Neural Networks: A Neuromorphic AI Approach to Early Language Learning
**Valentina Simon**

## Overview

This project explores how spiking neural networks (SNNs) can model early phoneme and sentence sensitivity using infant-directed speech. The approach draws on neuromorphic AI principles and leverages real-world data from the CHILDES corpus (Brent dataset) to simulate early language acquisition patterns.

The main implementation is in the file `CompLingFINAL.ipynb`, which includes all experiments, figures, and analyses referenced in the accompanying research PDF. The additional folders contain Brent datasets from CHILDES, included for convenience.

---

## Getting Started

### Requirements

Please install the following dependencies before running the notebook:

- `numpy`
- `matplotlib`
- `brian2`
- `scikit-learn`
- `pylangacq`
- `glob2`
- `pandas`
- `plotly`

Install them using `pip`:

```bash
pip install numpy matplotlib brian2 scikit-learn pylangacq glob2 pandas plotly
```

> Note: `collections` and `os` are part of the Python standard library and do not require installation.

---

## File Structure

```text
.
├── CompLingFINAL.ipynb                                           # Main notebook with code and experiments
├── CompLingFINAL.html                                            # Exported HTML version of the notebook with outputs
├── brent/                                                        # Folder containing Brent corpus files from CHILDES
└── README.md                                                     # This file
└── Computational_Psycholinguistics_Final_Project_Report.pdf      # Report
```

---

## Usage

To run the notebook:

1. Launch Jupyter:

   ```bash
   jupyter notebook CompLingFINAL.ipynb
   ```

2. Execute the cells in order to:

   - Preprocess infant-directed speech data  
   - Encode sentence structures into spike trains  
   - Run Brian2 simulations of spiking neural networks  
   - Visualize and interpret output spike responses to linguistic patterns

---

## Citation

If referencing this work, please use the following citation:

**Simon, V.** (2025). *Modeling Sensitivity to Infant-Directed Sentences Using Spiking Neural Networks: A Neuromorphic AI Approach to Early Language Learning*.

---

## Contact

For questions or collaboration inquiries, please contact:

**Valentina Simon**  
✉️ valentina.simon@yale.edu
