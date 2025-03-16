# EEG-Based Attention State Classification

This repository contains the code and resources for **Project COGS 189: EEG-Based Attention State Classification Using Machine Learning**. The aim of this project is to analyze EEG signals to detect and classify cognitive attention states—specifically, distinguishing between **focused**, **distracted**, and **overstimulated** conditions—using machine learning techniques.

## Project Overview

The project focuses on processing preprocessed EEG datasets (e.g., the DEAP dataset) to extract key frequency band features. By analyzing Theta, Alpha, Beta, and Gamma bands, the project leverages machine learning algorithms such as Support Vector Machines (SVM), Long Short-Term Memory (LSTM) networks, and Convolutional Neural Networks (CNN) to classify the cognitive states of subjects.

## Key Components

### EEG Frequency Band Analysis
- **Theta (4–8 Hz):** Associated with drowsiness and meditation.
- **Alpha (8–13 Hz):** Linked to relaxation and light focus.
- **Beta (13–30 Hz):** Indicates active thinking and concentration.
- **Gamma (30–45 Hz):** Correlated with high-level cognitive processing.

### Machine Learning Classification
- **SVM, LSTM, and CNN Models:**  
  The project implements various models:
  - **SVM:** A baseline classifier using engineered features.
  - **LSTM:** To capture temporal dynamics in EEG signals.
  - **CNN:** For extracting features from raw time-series EEG data.
- These models are trained and evaluated to classify EEG data into **Focused**, **Distracted**, and **Overstimulated** states.

## Data Source and Preprocessing

- **DEAP Dataset:**  
  The project utilizes publicly available EEG datasets such as the [DEAP dataset](https://www.eecs.qmul.ac.uk/mmv/datasets/deap/download.html) for collecting EEG data.
  
- **Preprocessed Data:**
  - **metadata_csv:** Contains metadata related to the EEG recordings and labels.
  - **data_preprocessed_python:** Contains preprocessed EEG data files used for feature extraction and model training.
  
  **Note:** The `data_preprocessed_python` folder is added to the `.gitignore` file to prevent large binary files from being tracked in the repository.

## Getting Started

### Prerequisites
- **Python 3.x**
- Recommended libraries: NumPy, SciPy, scikit-learn, TensorFlow/Keras or PyTorch, and matplotlib.

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/xavierxdl/cogs189project.git
   cd cogs189project

