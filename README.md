# EEG-Based Attention State Classification

This repository contains the code and resources for **Project COGS 189: EEG-Based Attention State Classification Using Machine Learning**. The aim of this project is to analyze EEG signals to detect and classify cognitive attention states—specifically, distinguishing between focused, distracted, and overstimulated conditions—using machine learning techniques.

## Project Overview

The project focuses on processing preprocessed EEG datasets (e.g., the DEAP dataset) to extract key frequency band features. By analyzing Theta, Alpha, Beta, and Gamma bands, the project leverages machine learning algorithms such as Support Vector Machines (SVM), Long Short-Term Memory (LSTM) networks, and Convolutional Neural Networks (CNN) to classify the cognitive states of subjects.

### Key Components

- **EEG Frequency Band Analysis:**  
  - Extracts and analyzes EEG signals divided into frequency bands:
    - *Theta (4–8 Hz)* – Associated with drowsiness and meditation.
    - *Alpha (8–13 Hz)* – Linked to relaxation and light focus.
    - *Beta (13–30 Hz)* – Indicates active thinking and concentration.
    - *Gamma (30–45 Hz)* – Correlated with high-level cognitive processing.
    
- **Machine Learning Classification:**  
  - Implements models such as SVM, LSTM, and CNN to classify EEG data.
  - Trains and evaluates models on identifying `Focused`, `Distracted`, and `Overstimulated` states.

- **Data Source:**  
  - Utilizes publicly available EEG datasets (e.g., the [DEAP dataset](https://www.eecs.qmul.ac.uk/mmv/datasets/deap/download.html)).
  - Focuses on preprocessed data to streamline feature extraction and model training.

## Getting Started

### Prerequisites

- Python 3.x
- Recommended libraries: NumPy, SciPy, scikit-learn, TensorFlow/Keras or PyTorch, and matplotlib.

### Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/xavierxdl/cogs189project.git
   cd cogs189project
