# Enhanced-Breast-Cancer-Diagnosis-via-SVM-and-Image-Processing
Our project enhances breast cancer diagnosis with a robust classification system using advanced image processing and SVM. Utilizing the BreaKHis dataset, we achieve high accuracy in distinguishing benign and malignant tissues across various magnifications, while reducing computational time, thus improving early detection and treatment efficiency.

# BreaKHis Dataset Description

The BreaKHis (Breast Cancer Histopathological Image) dataset is designed for use in machine learning tasks focused on breast cancer diagnosis. This dataset contains a collection of microscopic images of breast tumor tissues collected from 82 patients. The images are captured at different magnification levels (40X, 100X, 200X, and 400X) and are classified into two main groups: benign and malignant tumors.

## Key Features:
- **Total Images:** 7,909
  - **Benign:** 2,480
  - **Malignant:** 5,429
- **Magnification Levels:** 40X, 100X, 200X, 400X
- **Image Format:** PNG, 3-channel RGB, 700x460 pixels

## Tumor Types:
### Benign Tumors:
- Adenosis (A)
- Fibroadenoma (F)
- Phyllodes Tumor (PT)
- Tubular Adenoma (TA)

### Malignant Tumors:
- Ductal Carcinoma (DC)
- Lobular Carcinoma (LC)
- Mucinous Carcinoma (MC)
- Papillary Carcinoma (PC)

## Image Naming Convention:
Each image file name provides detailed information about the biopsy procedure, tumor class, tumor type, patient ID, magnification factor, and sequence number. For example, `SOB_B_TA-14-4659-40-001.png` indicates:
- **SOB:** Biopsy procedure
- **B:** Benign tumor
- **TA:** Tubular adenoma
- **14-4659:** Slide ID
- **40:** Magnification factor (40X)
- **001:** Image sequence number

## Usage:
The BreaKHis dataset is widely used for training and evaluating machine learning models in tasks such as binary and multiclass classification of breast cancer. It supports research in enhancing the accuracy and efficiency of automated cancer diagnosis systems.

## Download Links:
- [Mendeley Data](https://data.mendeley.com/datasets/jxwvdwhpc2/1)
