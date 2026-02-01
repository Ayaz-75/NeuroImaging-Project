# 🧠 Neuroimaging with Machine Learning & Deep Learning  
### Structural MRI (3D CNN) + fMRI (LSTM) | Research-Grade Pipeline

This project provides a **research-oriented, end-to-end neuroimaging pipeline** using **real MRI and fMRI data**, classical machine learning, and deep learning models.  
It is designed for **workshops, graduate courses, and early-stage research projects**.

---

## 📌 Project Highlights

- ✅ Population-level neuroimaging modeling
- ✅ Classical ML baseline (Logistic Regression)
- ✅ **3D CNN** for structural MRI
- ✅ **Real OpenNeuro fMRI loading**
- ✅ **LSTM-based temporal modeling for fMRI**
- ✅ Research best practices (train/validation split, baselines)
- ✅ Fully runnable in **Google Colab**

This is **not a toy demo** — the pipeline mirrors what is used in published neuroimaging research.

---

## 🧠 Neuroimaging Modalities Covered

### 1️⃣ Structural MRI
- 3D volumetric brain data
- Disease vs control classification
- Deep learning with **3D Convolutional Neural Networks**

### 2️⃣ Functional MRI (fMRI)
- 4D data (x, y, z, time)
- Regional time-series extraction
- Temporal modeling using **LSTM**

---

## 📂 Project Structure

```

├── README.md
├── neuroimaging_workshop.ipynb
│   ├── MRI data simulation
│   ├── Classical ML baseline
│   ├── 3D CNN (PyTorch)
│   ├── OpenNeuro fMRI loading
│   ├── Brain parcellation (Harvard-Oxford atlas)
│   └── fMRI + LSTM model

```

> ⚠️ For teaching purposes, MRI data is simulated.  
> fMRI data is **real** and fetched via `nilearn` from OpenNeuro-compatible sources.

---

## 🧪 Datasets

### Structural MRI
- Simulated 3D MRI volumes
- Shape: `(subjects, 32, 32, 32)`
- Labels: binary (Healthy vs Disease)

### Functional MRI
- Real fMRI data via **OpenNeuro**
- Downloaded using `nilearn.datasets`
- Brain regions defined using **Harvard-Oxford atlas**

---

## 🧰 Tech Stack

- **Python 3**
- **PyTorch** – Deep learning
- **scikit-learn** – Classical ML
- **NiBabel** – MRI/fMRI loading
- **Nilearn** – Neuroimaging utilities
- **NumPy / Matplotlib**

---

## 🚀 Running the Project (Google Colab)

1. Open **Google Colab**
2. Copy cells from the notebook (provided step-by-step)
3. Enable GPU:
```

Runtime → Change runtime type → GPU

```
4. Run cells sequentially

All dependencies are installed automatically inside Colab.

---

## 🧠 Methodology Overview

### Structural MRI Pipeline
1. Subject-level 3D MRI volumes
2. Train / validation split
3. Classical ML baseline (Logistic Regression)
4. 3D CNN for volumetric learning
5. Validation accuracy evaluation

### fMRI Pipeline
1. Load real fMRI data
2. Brain parcellation using atlas
3. Extract regional time-series
4. LSTM-based sequence modeling
5. Conceptual training demonstration

---

## 📊 Models Implemented

### Classical Machine Learning
- Logistic Regression (baseline)

### Deep Learning
- **3D CNN** for structural MRI
- **LSTM** for fMRI time-series

---

## 🎓 Intended Audience

This project is suitable for:
- Graduate students (MS / PhD)
- Neuroimaging workshops
- AI + neuroscience courses
- Early-stage neuroimaging research
- ML researchers entering neuroscience

---

## 🔬 Research Extensions

This project can be extended to:
- Real NIfTI MRI datasets (ADNI, OpenNeuro)
- fMRI Transformers
- Graph Neural Networks (connectomes)
- Explainable AI (Grad-CAM)
- Cross-site generalization
- Clinical prediction tasks

---

## 📚 References & Inspiration

- OpenNeuro: https://openneuro.org
- Nilearn documentation
- ADNI / HCP pipelines
- Neuroimaging deep learning literature

---

## 👤 Author

**Ayaz Ali**  
Prospective Graduate Researcher  
Interests: Neuroimaging, Machine Learning, Deep Learning, AI for Healthcare

---

## 📜 License

This project is intended for **educational and research use**.  
Please cite appropriately if used in academic work.



