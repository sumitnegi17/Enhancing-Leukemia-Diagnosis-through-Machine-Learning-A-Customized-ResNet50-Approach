# 🩸 Enhancing Leukemia Diagnosis with Machine Learning: A Custom ResNet50 Approach

## Overview

This repository contains the implementation of the paper "Enhancing Leukemia Diagnosis through Machine Learning: A Customized ResNet50 Approach," presented at the **2024 International Conference on Advancement in Computation & Computer Technologies (InCACCT)**.

🔗 **DOI:** [10.1109/InCACCT.2024.10551130](https://ieeexplore.ieee.org/document/10551130)

## Abstract

Leukemia diagnosis, particularly for **Acute Lymphoblastic Leukemia (ALL)**, is challenging due to its complex classification process. This study introduces a custom **ResNet50** CNN model combined with **Lazy Predict** for automated model selection, achieving a significant improvement in accuracy and efficiency for leukemia classification.

### 🧠 Key Features:
- **Custom ResNet50**: Tailored for leukemia image analysis, achieving 87% accuracy and 83% balanced accuracy.
- **Lazy Predict Integration**: Automates the evaluation of various classifiers, streamlining the model selection process.
- **Real-time Capable**: Optimized for fast inference, making it ideal for real-time leukemia diagnosis in clinical settings.

## Methodology

### Dataset
Utilized the **C-NMC leukemia dataset** with 10,661 images, focusing on acute lymphoblastic leukemia and normal cell differentiation.

### Workflow:
1. **Preprocessing**: 
   - Otsu’s Thresholding for segmentation.
   - Binary thresholding and black area removal for enhanced feature isolation.
   - Data augmentation to tackle class imbalance.
  
2. **Feature Extraction**:
   - Modified **ResNet50** with additional custom layers.
   - Lazy Predict used to evaluate multiple classifiers for optimal performance.

###Experimental Results
The customized ResNet50 model demonstrated superior performance over traditional models, achieving high accuracy and balanced accuracy. Key classifiers tested include:

-Support Vector Classifier (SVC)
-XGBoost Classifier (XGBClassifier)
-LightGBM Classifier (LGBMClassifier)

## Results

🚀 **Accuracy**: 87%  
⚖️ **Balanced Accuracy**: 83%  
⏱️ **Inference Time**: Fast, making it suitable for real-time applications.

## Authors

- **Modigari Narendra**  
  Assistant Professor Senior Grade 1, VIT Chennai  
  [modigari.narendra@vit.ac.in](mailto:modigari.narendra@vit.ac.in)

- **Sumit Negi**  
  Post Graduate Student, VIT Chennai  
  [sumit.negi2022@vitstudent.ac.in](mailto:sumit.negi2022@vitstudent.ac.in)

## Citation

If you use this work, please cite it:

```plaintext
@inproceedings{modigari2024enhancing,
  title={Enhancing Leukemia Diagnosis through Machine Learning: A Customized ResNet50 Approach},
  author={Modigari Narendra and Sumit Negi},
  booktitle={2024 International Conference on Advancement in Computation & Computer Technologies (InCACCT)},
  year={2024},
  organization={IEEE},
  doi={10.1109/InCACCT.2024.10551130}
}
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---
