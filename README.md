# LiDAR Vegetation Metrics

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![GitHub issues](https://img.shields.io/github/issues/Jinhu-Wang/LiDAR_Vegetation_Metrics)](https://github.com/Jinhu-Wang/LiDAR_Vegetation_Metrics/issues)
[![GitHub forks](https://img.shields.io/github/forks/Jinhu-Wang/LiDAR_Vegetation_Metrics)](https://github.com/Jinhu-Wang/LiDAR_Vegetation_Metrics/network)
[![GitHub stars](https://img.shields.io/github/stars/Jinhu-Wang/LiDAR_Vegetation_Metrics)](https://github.com/Jinhu-Wang/LiDAR_Vegetation_Metrics/stargazers)

## Table of Contents
- [Overview](#overview)
- [File Structure](#file-structure)
- [Requirements](#requirements)
- [Usage Instructions](#usage-instructions)
- [Resource](#resources)
- [License](#license)
- [Contact](#contact)

---

## Overview

**LiDAR_Vegetation_Metrics** provides a set of lightweight, easy-to-use Jupyter Notebooks designed to compute key vegetation metrics using 3D point clouds obtained by Airborne Laser Scanning (ALS). 

This repository is built to assist researchers, ecologists, and geospatial analysts in processing LiDAR data to extract structural information about forestry and vegetation. To maximize accessibility, the repository provides notebook versions optimized for both **Local** execution and cloud-based execution via **Google Colab**.

---

## File Structure

The repository is organized as follows:

```text
LiDAR_Vegetation_Metrics/
│
├── Colab/                     # Jupyter Notebooks optimized for Google Colab execution
│   └── ...                    
│
├── Local/                     # Jupyter Notebooks optimized for local Python environments
│   └── ...                    
│
├── .gitignore                 # Files to be ignored by Git
├── LICENSE                    # MIT License file
└── README.md                  # Project documentation (this file)
```

---

## Requirements

Depending on how you choose to run the notebooks, the requirements vary slightly.

### For Local Execution:
You will need a working Python environment (Python 3.7+ recommended). Required Python libraries typically include:
* `numpy`
* `pandas`
* `matplotlib` / `seaborn` (for visualization)
* `laspy` (for reading/writing `.las` and `.laz` point cloud files)
* `scipy`
* `jupyterlab` or `notebook`

You can install the primary dependencies using `pip`:
```bash
pip install numpy pandas matplotlib laspy scipy jupyterlab
```

### For Google Colab:
No local installation is required. A Google account is needed to run the notebooks in Google Drive/Colab. The notebooks in the `Colab/` folder include cells at the beginning to automatically `!pip install` any necessary external packages in the cloud environment.

---

## Usage Instructions

### Option 1: Running Locally
1. **Clone the repository:**
   ```bash
   git clone [https://github.com/Jinhu-Wang/LiDAR_Vegetation_Metrics.git](https://github.com/Jinhu-Wang/LiDAR_Vegetation_Metrics.git)
   cd LiDAR_Vegetation_Metrics
   ```
   #Using Git as a tool to download and clone the repository.#
   #Or download directly from GitHub repository# 
   
3. **Launch Jupyter Notebook or JupyterLab:**
   ```bash
   jupyter notebook
   # OR
   jupyter lab
   ```
4. Navigate to the `Local/` directory in the Jupyter interface.
5. Open the notebook of your choice, adjust the input file paths to point to your local `.las` or `.laz` LiDAR datasets, and run the cells sequentially.

### Option 2: Running via Google Colab
1. Navigate to the `Colab/` folder in this GitHub repository.
2. Click on the notebook you wish to use.
3. Click the **"Open in Colab"** badge (if available) or simply head to [Google Colab](https://colab.research.google.com/), select the "GitHub" tab, and paste the URL of the notebook.
4. Mount your Google Drive (if your LiDAR datasets are stored there) or upload your `.las`/`.laz` files directly to the Colab temporary storage (Upload to your own GoogleDrive).
5. Run the cells sequentially. Ensure you run the dependency installation cells first.

---

## License

This project is licensed under the **MIT License**. 

You are free to use, modify, and distribute this software, provided that the original copyright notice and permission notice are included in all copies or substantial portions of the software. See the `LICENSE` file for more details.

---

## Contact

**Author:** Jinhu Wang  
**GitHub:** [@Jinhu-Wang](https://github.com/Jinhu-Wang)  

If you encounter any issues, have questions, or want to contribute to the project, please feel free to [open an issue](https://github.com/Jinhu-Wang/LiDAR_Vegetation_Metrics/issues) or submit a pull request!
