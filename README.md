# AquaIntel 🌊🧠

**AquaIntel** is an AI-powered flood risk assessment system using satellite image segmentation and unsupervised clustering.

## 🔍 Project Overview
- Performed **flood segmentation** using DeepLabV3+ with a ResNet50 encoder.
- Extracted binary masks for flooded buildings and water bodies.
- Engineered features like:
  - `Flooded Building Ratio`
  - `Total Flood Ratio`
- Applied **Gaussian Mixture Models (GMM)** to classify regions into:
  - Low Risk
  - Moderate Risk
  - Severe Risk

## 📂 File Included
- `aquaintel_ml_project(1).py`: Main ML pipeline.
- `AquaIntel_ML_Report.pdf`: Project report with methodology and results.

## 🛠️ Tools & Libraries
- Python, OpenCV, PyTorch
- DeepLabV3+, GMM (Scikit-Learn)

---

⚠️ Work in progress. Deployment coming soon via Hugging Face Spaces.
