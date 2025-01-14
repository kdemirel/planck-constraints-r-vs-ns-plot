# Planck constraints: 
# tensor-to-scalar ratio ($r$) vs spectral index ($n_s$) Plot

This repository provides tools to visualize constraints on the spectral index ($n_s$) and tensor-to-scalar ratio ($r$) using data derived from the Planck collaboration's publication: *"Planck 2018 results. X. Constraints on inflation."*

## Overview

The repository includes:
- **`PLANCK Data.csv`**: Contains the extracted boundary data for 68% and 95% confidence level (CL) regions from the Planck2018_BK14_120mm.pdf plot.
- **`Planck Constraints Plot.nb`**: A Wolfram Mathematica notebook to visualize the Planck data constraints and compare with your model.
- **`Planck Constraints Plot.py`**: A python script to visualize the Planck data constraints.
- **`plot.pdf`**: Example output plot generated by the notebook.
- **`Planck2018_BK14_120mm.pdf`**: The original $r$ vs $n_s$ graph from the Planck 2018 paper.

## Features

1. **Data Extraction**:
   - The `PLANCK Data.csv` file contains the extracted boundaries for the 68% and 95% CL regions from the Planck constraints plot.

2. **Visualization**:
   - The Mathematica notebook, `Planck Constraints Plot.nb`, generates a plot showing the constraints on $r$ and $n_s$ based on Planck data.

3. **Comparison with Models**:
   - If you have a theoretical model that predicts the relationship between $n_s$ and $r$, or their dependencies on the number of e-folds ($N$), you can overlay these predictions on the Planck constraints.
   - The notebook produces a plot (`plot.pdf`) that compares your model's predictions with observational data.

## How to Use

1. **Prepare Your Data**:
   - If you want to overlay your model's predictions, determine the $n_s$ and $r$ values (or their dependence on $N$).
   
2. **Run the Notebook**:
   - Open `Planck Constraints Plot.nb` in Mathematica.
   - Follow the instructions within the notebook to load `PLANCK Data.csv` and add your model's predictions.

3. **Generate the Plot**:
   - Execute the notebook to produce a comparison plot. The resulting visualization will highlight how well your model aligns with observational constraints.

## Files

| File Name                  | Description                                                                 |
|----------------------------|-----------------------------------------------------------------------------|
| `PLANCK Data.csv`          | Extracted boundary data for 68% and 95% CL regions from Planck constraints. |
| `Planck Constraints Plot.nb` | Mathematica notebook for data visualization and comparison with models.      |
| `Planck Constraints Plot.py` | Do the same thing with mathematica notebook but in python      |
| `plot.pdf`                 | Example output plot comparing constraints with a sample model.              |
| `Planck2018_BK14_120mm.pdf`| Original $r$ vs $n_s$ constraints plot from the Planck 2018 publication.    |
| `README.md`                | This documentation file.                                                   |

## Prerequisites

- **Software**: Mathematica (to run the notebook).
- **Knowledge**: Familiarity with inflationary models and the $r$ vs $n_s$ parameter space.

## References

- Planck Collaboration (2018). *Planck 2018 results. X. Constraints on inflation.*

## License

This project is open-source and released under the MIT License. Refer to the `LICENSE` file for details.

---
For any questions or issues, feel free to create an issue or contribute to the repository!
