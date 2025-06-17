# Retinal OCT Disease Classification

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![TensorFlow](https://img.shields.io/badge/TensorFlow-2.6%2B-orange)
![Accuracy](https://img.shields.io/badge/Accuracy-92.13%25-brightgreen)

Deep learning system for classifying retinal diseases (CNV, DME, DRUSEN, Normal) from OCT scans using Custom CNN and VGG19 models.

## Key Features
- 🏥 **Clinical-grade performance**: 92.13% test accuracy
- 🔍 **Explainable AI**: Grad-CAM visualization
- ⚖️ **Class balancing**: Automatic weight calculation
- 🛠️ **Preprocessing pipeline**: Denoising, CLAHE, ROI extraction
- 🤖 **Two model variants**: Lightweight CNN (91.28%) and VGG19 (92.13%)

## Quick Start
```bash
git clone https://github.com/yourusername/retinal-oct-classification.git
cd retinal-oct-classification
pip install -r requirements.txt

# Train and evaluate
python train.py --model vgg19 
python evaluate.py --model_path models/vgg19.h5
