# Python for Astrophysics: Astropy, Numpy, SciPy, and AstroData Analysis

## Description
This repository offers tutorials and practical applications of Python for astrophysics, focusing on the libraries Astropy, Numpy, and SciPy. It includes data handling techniques, astronomical visualization, celestial mechanics, and tools for analyzing datasets from Gaia, TESS, and other astrophysical sources. This resource is ideal for researchers and students aiming to use Python for scientific computing in astronomy.

## Table of Contents
- [Project Overview](#project-overview)
- [Dependencies](#dependencies)
- [Installation Instructions](#installation-instructions)
- [Running the Notebooks](#running-the-notebooks)
- [Repository Structure](#repository-structure)
- [Additional Information](#additional-information)
- [License](#license)
- [Author](#author)

## Project Overview
This repository provides step-by-step tutorials across various topics in astrophysics and scientific computing, covering:
- Basics of **Numpy** for array processing.
- Using **SciPy** for scientific computations.
- **Astropy** functions for astronomical data handling, including coordinate transformations, unit conversions, and more.
- Accessing and analyzing datasets from astronomical missions like Gaia and TESS.

## Dependencies
The following libraries are required:
- **Python 3.x**
- **Jupyter Notebook** (to view and run `.ipynb` files)
- **NumPy**
- **SciPy**
- **Astropy**
- **Matplotlib** (for visualizations)

To install dependencies, run:
```bash
pip install numpy scipy astropy matplotlib
```

## Installation Instructions
1. **Install Python 3.x** if you haven’t already.
2. **Install Jupyter Notebook** by running:
   ```bash
   pip install notebook
   ```
3. **Clone the repository**:
   ```bash
   git clone https://github.com/astroAnjani/Astropy.git
   cd Astropy
   ```
4. **Install dependencies** as listed above.

## Running the Notebooks
1. **Open Jupyter Notebook**:
   ```bash
   jupyter notebook
   ```
2. Navigate to the repository folder within Jupyter and open the desired notebook file.
3. **Recommended Order**: It’s best to run the foundational notebooks (e.g., `Numpy.ipynb`, `SciPy.ipynb`) first, as they cover basics used in later astrophysics-focused notebooks.

## Repository Structure
- **AstroPy.ipynb**: Introduction to the Astropy library for astronomy-specific tasks like unit conversions and handling celestial coordinates.
- **GaiaTutorialAssignment.ipynb**: A tutorial on accessing and analyzing data from the Gaia mission.
- **Introduction_to_TESS.ipynb**: A guide to working with TESS data for exoplanet research.
- **Numpy.ipynb**: Covers array operations, data manipulation, and foundational NumPy functions.
- **SciPy.ipynb**: Demonstrates scientific and statistical functions, useful for astronomy and physics applications.
- **example_data.fits** & **s0002.fits**: Sample FITS files to practice data loading and manipulation in Astropy.
- **franck_hertz.xlsx**: Data file containing results from a Franck-Hertz experiment.
- **nasa_exoplanet_archive_tutorial.ipynb**: A tutorial on accessing and analyzing data from the NASA Exoplanet Archive.

## Additional Information
- **Data Files**: Ensure `.fits` and `.xlsx` files are in the same directory as the notebooks, or update paths as necessary.
- **Notebooks with External Data**: Some notebooks may reference external datasets (like Gaia and TESS), so users may need to ensure internet access or download links as specified in the notebook.

## License
This repository is publicly available under an open license for educational and research purposes. Feel free to explore, fork, and contribute.

## Author
- **Anjani Pachauri**  
  Aspiring astrophysicist and Python enthusiast
```
