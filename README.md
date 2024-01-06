<h1 align="center">Welcome to the CNN-CT-BRAIN Project! 🧠</h1>

<ul align="center">		
  <a href="https://www.kaggle.com/datasets/trainingdatapro/computed-tomography-ct-of-the-brain" target="_blank">
    <img width="200px"  src="https://github.com/AlejandroDavidArzolaSaavedra/CNN-CT-BRAIN/assets/90756437/0bed01b8-49fc-40de-bbfa-982a38e50ea1">
  </a>
</ul>

## 👩‍🔬 Cancer, Tumor, and Aneurysm Classification and Detection

<img align="left" width="250" height="180" src="https://i.imgur.com/RsmO2hP.gif?raw=true"></a>
This repository contains the implementation of <strong>VGG16</strong> and <strong>ResNet-50</strong> models, techniques such as <strong>fine-tuning</strong> with layer <strong>freezing and unfreezing</strong> were applied. 

<strong>Regularization</strong> methods like L1 and L2, <strong>dropout</strong>, and <strong>early stopping</strong> were employed to prevent overfitting. 

Strategies such as <strong>data augmentation</strong>, <strong>transfer learning</strong> and <strong>one-hot encoding</strong> were integrated, and optimization was carried out using algorithms like <strong>Adam</strong>. 

<br>

# 👥 Development Team (Ctrl + Click to view profiles)

[![GitHub](https://img.shields.io/badge/GitHub-Andrea%20Santana%20Lopez-purple?style=flat-square&logo=github)](https://github.com/AndreaSantalos)

[![GitHub](https://img.shields.io/badge/GitHub-Alejandro%20David%20Arzola%20Saavedra-blue?style=flat-square&logo=github)](https://github.com/AlejandroDavidArzolaSaavedra)

## 🕵🏻 Dataset Overview
<p color="blue">
This project focuses on developing a classification model to detect brain diseases, such as cancer, tumors, and aneurysms, from CT brain scans.
</p>

<br>
<table align="center">
  <tr>
  <td width="50%">
    <h3 align="center"> Scan of a person with aneurysm, cancer, and tumor</h3>
    <div align="center">
      <a href="https://github.com/AlejandroDavidArzolaSaavedra/CNN-CT-BRAIN" target="_blank"><img width="800" src="https://github.com/AlejandroDavidArzolaSaavedra/CNN-CT-BRAIN/assets/90756437/645c003c-fd45-4f31-9152-0ef1f7c3f0dc" width="400" alt="Scan of a person with aneurysm, cancer, and tumor"></a>
      <p>Our focus on image processing allows us to provide accurate diagnosis 🩺</p>
    </div>
  </td>                                                    
</table> 
<br>

## 📖 CNN-CT-BRAIN Libraries 

[![TensorFlow](https://img.shields.io/badge/TensorFlow-black?style=for-the-badge&logo=tensorflow)](Link_To_Your_TensorFlow_Page)
[![NumPy](https://img.shields.io/badge/NumPy-%23013243?style=for-the-badge&logo=numpy)](Link_To_Your_NumPy_Page)
[![tqdm](https://img.shields.io/badge/tqdm-%23000000?style=for-the-badge&logo=tqdm)](Link_To_Your_tqdm_Page)
[![scikit-learn](https://img.shields.io/badge/scikit_learn-%23191919?style=for-the-badge&logo=scikit-learn)](Link_To_Your_scikit_learn_Page)
[![OpenCV](https://img.shields.io/badge/OpenCV-%23FD8C00?style=for-the-badge&logo=opencv)](Link_To_Your_OpenCV_Page)
[![Matplotlib](https://img.shields.io/badge/Matplotlib-%23FF6400?style=for-the-badge&logo=matplotlib&logoColor=white)](Link_To_Your_Matplotlib_Page)
[![Pandas](https://img.shields.io/badge/Pandas-%23150458?style=for-the-badge&logo=pandas)](Link_To_Your_Pandas_Page)

## 📊 Dataset Structure

The dataset is organized into two main folders:

1. **JPEG Images (.jpg) 📷**: Contains CT brain scan images in JPEG format.
2. **DICOM Files (.dcm) 📁**: Contains the same CT scans but in Digital Imaging and Communications in Medicine (DICOM) format.

## Requirements

To run this project, please follow these steps:

1. **Download the dataset:**
   - Visit the dataset page on Kaggle: [CT Scan Images of the Brain](https://www.kaggle.com/datasets/trainingdatapro/computed-tomography-ct-of-the-brain) and download it.

2. **Unzip and overwrite the "archive" file:**
   - Unzip the downloaded ZIP file.
   - Locate the file named "archive" 🗃️ and overwrite this project's file.

### For Local Execution:
   - If running locally, ensure the dataset is in the project directory.

### For Google Colab:
   - If using Google Colab, upload the dataset to your Google Drive.
   - Modify the `base_dir` in the code to point to the Colab Notebooks📂 directory:

     ```python
     base_dir = "/content/drive/MyDrive/Colab Notebooks/"
     ```
     
## Getting Started

1. Clone this repository:

   ```bash
     git clone https://github.com/AlejandroDavidArzolaSaavedra/CNN-CT-BRAIN.git
   ```

2. Explore the dataset folders to understand the structure.

3. Use the data to train and test your models and contribute to advancing medical image analysis.

# 🤝 Contributions
<img align="left" width="200" height="180" src="https://github.com/AlejandroDavidArzolaSaavedra/CNN-CT-BRAIN/assets/90756437/3bf833fa-828e-467c-89b8-0ea4a077d3ea"></a>
If you wish to contribute to this project, feel free to do so. You can open issues or send pull requests to improve the code. Your collaboration is welcome! 🚀
