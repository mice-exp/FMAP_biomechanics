# FMAP_biomechanics

## Biomechanical Analysis – FMA-P Protocol

This repository provides Python code to extract and calculate various biomechanical parameters from functional tasks performed during the **Functional Mobility Assessment in Parkinson’s** protocol.

DOI: 10.5281/zenodo.15175531

> 📝 **Note**: The **marker nomenclature** used throughout these analyses is documented in `marker_setup.pdf`.

## 📁 Data Formats
- **Motion capture files**: `.tsv` format (Tab-separated values)
- **Center of Pressure (COP) files**: `.txt` format (GaitMat outputs)

---

## 📚 Notebooks Overview

### 1. `FLE_detection_on_FMAP.ipynb`
- **Purpose**: Detect **Freeze-Like Events (FLE)** during locomotion.
- **Key outputs**: Quantity and duration of FLEs based on a velocity threshold.
---

### 2. `Stand_to_sit.ipynb`
- **Purpose**: Analyze the **stand-to-sit** transition in terms of segment displacement and smoothness.
- **Key outputs**: Peak trunk acceleration, pelvis and trunk flexion, peak trunk inclination in Anteroposterior (AP) and mediolateral (ML) directions.
---

### 3. `COP_FMAP.ipynb`
- **Purpose**: Process **Center of Pressure (COP)** data from PKMAS Gait Mat.
- **Key outputs**: AP and ML sway metrics: Peak, mean, and SD of COP displacement
---

### 4. `Functional_reach.ipynb`
- **Purpose**: Analyze **fine motor control** during the fucntional reach task.
- **Key outputs**: Upper/Lower body flexion, reaching arm-body alignment
---

### 5. `Turning.ipynb`
- **Purpose**: Identify **turning strategy** and coordination between segments (e.g., head–pelvis).
- **Key outputs**: Yaw angles, body segments onset times, turn duration.
---

### 6. `Sit_to_stand.ipynb`
- **Purpose**: Analyze **sit-to-stand** transitions.
- **Key outputs**: Peak trunk acceleration, pelvis and trunk flexion, peak trunk inclination in AP and ML directions.
---

### 7. `Standing_upright.ipynb`
- **Purpose**: Measure **postural sway** during upright quiet standing.
- **Key outputs**: Peak trunk inclination in AP and ML, trunk acceleration and jerk.
---

## 🛠 Setup 
Python version used: 3.10.9
Requirements available in: requirements.txt
