# Turbine-Flow-Analysis
# 🌪️ ANSYS Fluent Turbine Flow Simulation  

## 📌 Project Overview  
This repository contains an **ANSYS Fluent CFD simulation** of a turbine flow field. The project focuses on analyzing **pressure distribution, velocity profiles, and streamline patterns** within a fluid domain. The simulation includes two contact regions (source and target) with detailed boundary conditions and mesh statistics.

---

## 📊 Simulation Details  

### 🏗️ **Geometry & Mesh**  
- **Domains:**  
  - `contact_region src` → 3,492 nodes | 1,584 elements  
  - `contact_region trg` → 77,348 nodes | 38,250 elements  
- **Mesh Type:** Structured/Unstructured (as per ANSYS Fluent)  

### ⚙️ **Physics & Boundary Conditions**  
| Boundary Name | Type | Location |
|--------------|------|----------|
| inlet | Velocity Inlet | inlet |
| outlet | Pressure Outlet | outlet |
| symmetry 1/2 | Symmetry | symmetry planes |
| turbine | Interface | turbine |
| wall | Wall | wall surfaces |

### 🔬 **Models & Solvers**  
- **Solver:** Pressure-Based  
- **Turbulence Model:** Not specified (default RANS/κ-ε possible)  
- **Fluid:** Air (assumed)  

---

## 📈 Results & Visualizations  

### 1. **Pressure Contour** (`contour1.png`, `Pressure.png`)  
- Shows static pressure distribution across the domain.  
- Range: `-1.416e+01 Pa` to `5.717e+00 Pa` (Contour 1).  

### 2. **Velocity Streamlines** (`streamline.png`, `Velocity.png`)  
- Illustrates flow pathlines and velocity magnitude.  
- Max velocity: `1.687e+01 m/s` in main flow region.  

### 3. **Velocity Vectors** (`vector of velocity.png`)  
- Displays direction and magnitude of velocity vectors.  
- Scale: `0.000e+00` to `4.864e+00 m/s`.  

### 4. **Simulation Report** (`report turbine 1.png`, `report turbine 2.png`)  
- Contains mesh statistics, boundary conditions, and solver settings.  

---

## 🛠️ How to Use  

### 🔍 **Viewing Results**  
1. Open the `.png` files in any image viewer to see contours and plots.  
2. Refer to the report images for simulation setup details.  

### 🔁 **Reproducing the Simulation**  
1. Import the provided mesh into ANSYS Fluent.  
2. Apply the same boundary conditions as listed in the report.  
3. Run the simulation with pressure-based solver and appropriate turbulence models.  


## 👨‍💻 Author  
**Yazan Alzyuod**  
- **Mechanical Engineer**  
- 📧 Email: [yqlasem@gmail.com](mailto:yqlasem@gmail.com)  
- 🔗 LinkedIn: [Yazan Alzyuod](https://www.linkedin.com/in/yazan-alzyuod)  
- 💻 GitHub: [Yazan-Alzyuod](https://github.com/Yazan-Alzyuod)  
- 📞 Phone: +962 775 327 776  

This project is shared for educational and portfolio purposes. All ANSYS-related files are generated from academic/student software licenses.
