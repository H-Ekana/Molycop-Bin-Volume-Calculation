# Grinding Media Volume Estimation System

A system to estimate the volume, mass, and count of grinding media (steel balls) within industrial bins using LiDAR-generated point cloud data. This project leverages Python's scientific libraries to process 3D point cloud data, calculate volumes, and provide actionable metrics.

---

## Description

This project automates the estimation of grinding media volume and count within bins. The system processes point cloud data to create a smoothed digital elevation model (DEM), calculates the volume under the surface, adjusts for porosity, and estimates the mass and number of grinding media. It includes robust visualization tools for inspecting point cloud data, grid cells, and the interpolated surface.

The system is designed to assist with inventory management and operational optimization by providing accurate estimates of bin contents. It uses assumed parameters like porosity and ball volume in the absence of precise ground truth measurements, offering a scalable framework for future enhancements.

---

## Getting Started

### Dependencies

Ensure you have the following installed before running the project:

* **Python 3.8 or higher**
* Required Python libraries:
  - `numpy`
  - `open3d`
  - `scipy`
  - `plotly`
* Compatible OS: Windows 10, macOS, or Linux

Install the libraries via pip:
```bash
pip install numpy open3d scipy plotly
```
---

### Installing

1. Clone the repository:

2. Ensure that your `.pcd` file (point cloud data) is available in the appropriate directory.

3. Open the Python script or Jupyter Notebook provided in the repository to begin processing.

---

### Executing program

To run the program, follow these steps:

1. Place your `.pcd` file in the project directory.
2. Modify the file path in the script or notebook to point to your `.pcd` file:
3. Run the Python script: `python grinding_media_volume.py`
4. Alternatively, execute the Jupyter Notebook:
5. View the 3D visualizations and estimated results in the output.

---
