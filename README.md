# Clustering Multi-Dimensional Dataset: Proof of Concept

## Overview
This repository contains a Jupyter notebook demonstrating a proof of concept for integrating and jointly analyzing datasets of vastly different dimensionalities. The test case combines high-dimensional NMR spectra with low-dimensional biochemical activities of samples from a G-quadruplex mutational library. The dimensionality of the high-dimensional part of the dataset is reduced by PCA, merged with the low-dimensional part of the dataset, and clustered by HDBSCAN. Comparison of results with previously published analyses demonstrates that this approach is viable.

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/rachel-sg/Clustering.git
   ```
2. Download the datasets from links provided below. Save them in the formats used in the notebook, unzip the NMR data, and place all data in the same directory as the notebook or adjust the data paths in the notebook accordingly.
3. Open the Jupyter notebook and ensure that all required libraries (listed in cell 2) are installed, install any missing libraries.
4. Run all cells step-by-step.

## Data Sources and Licensing
This project’s code is licensed under the MIT License. Users must not claim authorship or original creation of this code. Data is licensed under a combination of CC BY-NC 4.0, CC BY 4.0, and custom non-commercial terms. See below for details.

This project uses a dataset compiled from three sources:

1. Volek, Martin, et al. "Overlapping but distinct: a new model for G-quadruplex biochemical specificity." *Nucleic acids research* 49.4 (2021): 1816-1827
   - [Link](https://doi.org/10.1093/nar/gkab037) (valid 9.8.2025)
   - Licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/).  
   - Non-commercial use only.

2. Sgallová, Ráchel, et al. "NMR Screen Reveals the Diverse Structural Landscape of a G‐Quadruplex Library." *Chemistry–A European Journal* 30.67 (2024): e202401437
   - [Link](https://doi.org/10.1002/chem.202401437) (valid 9.8.2025)
   - [NMR spectra repository](https://doi.org/10.5281/zenodo.13838248) (valid 9.8.2025)
   - Licensed under [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/).  
   - Commercial and non-commercial use permitted with attribution.

3. PhD Dissertation by Rachel Sgallova 
   - [Link](https://dspace.cuni.cz/handle/20.500.11956/197989) (valid 9.8.2025)
   - Licence: As per the original publication notice:  
   > "Any retrieved information shall not be used for any commercial purposes or claimed as results of studying, scientific or any other creative activities of any person other than the author."

   This dataset is provided for non-commercial, educational, and research purposes only, attribution is required.

As such, the dataset in this repository is restricted to non-commercial use. The code is licensed separately.


## Contact

Created by Rachel Sgallova  
rachel.sgallova@centrum.cz  
[LinkedIn](https://www.linkedin.com/in/r%C3%A1chel-sgallov%C3%A1-042183334/)


## Acknowledgements

Portions of the text in this notebook were edited with assistance from OpenAI's ChatGPT, subsequently reviewed and revised by the author. ChatGPT was also consulted for programming related questions and clarifications, however all code was written, tested, and validated by the author.
