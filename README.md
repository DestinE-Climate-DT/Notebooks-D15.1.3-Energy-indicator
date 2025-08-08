# Scientific Assessment and Uncertainty Quantification (UQ) for the Energy Indicator Application (DE340.15.1.3)

This repository provides Jupyter notebooks for assessing the scientific robustness and quantifying the uncertainty of wind energy indicators derived from Climate Digital Twin (Climate DT) simulations. These notebooks form part of Deliverable **D15.1.3** within the DestinE project.

---

## 🌍 Objective

To evaluate how well the climate variables and indicators tailored to the wind energy sector from the Climate DT simulations capture the **spatio-temporal characteristics** of wind patterns, compared to reference data from **ERA5**.

---

## 🌀 Climate DT Simulations Used

1. **Freeze run + Historical Ensembles**
   - **Simulations**: Freeze run (`a24r`) and 3-member historical ensemble
   - **Period**: 1990–2014 (25 years)
   - **Model**: IFS-NEMO
   - **Resolution**: Global, 10 km horizontal

2. **Freeze Run Control**
   - **Simulation**: Control run (`a267`)
   - **Period**: 1990–2019 (30 years)
   - **Model**: IFS-NEMO
   - **Resolution**: Global, 10 km horizontal

---

## 📈 Scientific Assessment and UQ Components

- 📊 **Comparison with ERA5**
- 📉 **Mean Bias (MB)**
- 📐 **Root Mean Square Error (RMSE)**
- 🔄 **Pairwise differences between each ensemble member and the freeze run**

---

## 🛠️ Methodology

- Climate DT simulations are **regridded** to the ERA5 grid using a **conservative regridding** technique to ensure compatibility.
- Primary variable of interest: **wind speed at 100m** and **capacity factor**

**Reference**:  
Ramon et al. (2019), *Conservative regridding technique for climate fields*  
🔗 [https://doi.org/10.1002/qj.3616](https://doi.org/10.1002/qj.3616)

---

## 📁 Repository Contents

- `Energy_indicator_UQ_global_ws_DE34015_1_3_Notebook_1.ipynb`  
  → Global wind speed UQ and comparison across members

- `Energy_indicator_UQ_north_sea_cf_s_DE340_D15_1_3_Notebook_2.ipynb`  
  → North Sea capacity factor assessment and diagnostics

---

## 📬 Contact

- **Email**: [energy-destine@bsc.es](mailto:energy-destine@bsc.es)  
- **Responsible**: *Sushovan Ghosh* (Barcelona Supercomputing Center)

---

## 📝 License

To be added — choose based on BSC/DestinE policy (e.g., MIT, Apache 2.0).

---

A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A

A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A
A

