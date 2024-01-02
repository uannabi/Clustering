# Clustering
Welcome to the Wheat Kernel Variety Clustering project! This repository is dedicated to the analysis and clustering of wheat kernels from three different varieties - Kama, Rosa, and Canadian - using the K-means algorithm.

## About This Project
In this study, we explore a dataset comprising kernels from three wheat varieties. The data was obtained using a non-destructive soft X-ray technique, providing high-quality visualization of the internal kernel structure. This method is cost-effective compared to other advanced imaging techniques, making it an excellent choice for agricultural research.

## Dataset Overview
The dataset consists of kernels from three wheat varieties: Kama, Rosa, and Canadian, with 70 elements from each variety. These were harvested from experimental fields at the Institute of Agrophysics of the Polish Academy of Sciences in Lublin.

## Attribute Information
The dataset includes seven geometric parameters of wheat kernels, all real-valued and continuous:

- Area (A)
- Perimeter (P)
- Compactness (C = 4 * pi * A / P^2)
- Length of Kernel
- Width of Kernel
- Asymmetry Coefficient
- Length of Kernel Groove

## Objective
The aim is to apply the K-means clustering algorithm to this dataset and investigate whether the kernels can be effectively grouped into their respective varieties based solely on these geometric features.

## Getting Started
Prerequisites
- Python 3.x
- Libraries: pandas, matplotlib, scikit-learn
- Running the Analysis
Clone the Repository

```
git clone https://github.com/uannabi/Clustering.git
```

```
cd Clustering
```
Install Required Libraries
```
pip install -r requirements.txt
```
Run the Jupyter Notebooks

Open the Jupyter notebooks provided to see the analysis and clustering process.

## Contributing
Contributions to enhance the analysis, improve the methodology, or refine the clustering approach are welcome. Feel free to fork the repository and submit your pull requests.
