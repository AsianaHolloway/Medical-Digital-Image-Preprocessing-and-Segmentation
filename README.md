# Medical-Digital-Image-Preprocessing-and-Segmentation
Exploring fundamental digital image preprocessing and segmentation techniques in the context of medical imaging.

[![Open In Colab](https://colab.research.google.com/drive/1OolAHUd9VIigYKEP5MUyQTczPJSswivk?usp=sharing)

## 🔎 Overview

This project demonstrates key preprocessing and segmentation techniques applied to medical images, with a focus on brain tumor detection. Preprocessing improves image clarity while segmentation isolates critical regions of interest, providing a foundation for AI-based diagnostic models.

## ⚙️ Methods

* **Grayscale conversion** – removes unnecessary color, simplifying image analysis.
* **Min–max normalization** – enhances contrast by scaling pixel intensities.
* **Thresholding segmentation** – separates regions of differing intensities, useful for tumor isolation.

## 📊 Results

* Enhanced contrast and visibility of brain structures.
* Segmentation successfully highlighted abnormal regions.
* Images show strong potential for AI model training.

<p align="center">
  <img src="visuals/figures/before_after_segmentation.png" width="600"/>
</p>

## 🌍 Real-World Applications

* **AI training data** for tumor detection models
* **Computer-aided diagnosis** in radiology
* **Clinical decision support** for faster, more accurate assessments

## 📁 Repository Structure

```
code/         # Jupyter notebooks and requirements
reports/      # project report, results
visuals/      # figures, workflow diagrams
data/         # data placeholder (not included)
```

## 🚀 Quickstart

```bash
# Clone repo
git clone https://github.com/AsianaHolloway/Medical-Digital-Image-Preprocessing-and-Segmentation.git
cd Medical-Digital-Image-Preprocessing-and-Segmentation

# Setup environment
python -m venv .venv && source .venv/bin/activate
pip install -r code/requirements.txt

# Open notebook
jupyter notebook code/notebooks/Medical_Image_Preprocessing_Segmentation.ipynb
```

## 📚 Requirements

```
numpy
matplotlib
opencv-python
scikit-image
```

