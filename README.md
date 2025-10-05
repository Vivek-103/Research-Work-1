# CNN vs. Transfer Learning for Image Classification on CIFAR-10

This repository contains the source code and results for a research project comparing a custom-built Convolutional Neural Network (CNN) against a pre-trained VGG16 model using transfer learning. The task is image classification on the CIFAR-10 dataset. The project explores the effectiveness of data augmentation and provides a detailed performance analysis, culminating in a research paper in IEEE format.

## 🚀 Key Features

* **Custom CNN Model:** A simple CNN built from scratch with data augmentation layers.
* **Transfer Learning Model:** VGG16 pre-trained on ImageNet, adapted for CIFAR-10 with data augmentation.
* **Performance Analysis:** The script automatically generates:
    * A comparison graph of training and validation accuracies.
    * A detailed classification report (Precision, Recall, F1-Score).
    * A confusion matrix heatmap for the best-performing model.
* **Research Paper:** Includes the final, complete research paper in LaTeX format (`ieee_paper.tex`).

## 🛠️ Technologies Used

* **TensorFlow / Keras:** For building and training the deep learning models.
* **Scikit-learn:** For generating the classification report and confusion matrix.
* **Matplotlib & Seaborn:** For creating all data visualizations.
* **NumPy:** For numerical operations.

## ⚙️ Setup and Installation

To run this project locally, follow these steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/your-repo-name.git](https://github.com/your-username/your-repo-name.git)
    cd your-repo-name
    ```

2.  **Create and activate a virtual environment (recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install the required dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    *(Note: If you don't have a `requirements.txt` file, you can create one with `pip freeze > requirements.txt` after installing the libraries manually).*

## ▶️ How to Run

Execute the main script from the terminal to run the entire pipeline—from data loading to generating the final graphs:

```bash
python main_script.py
