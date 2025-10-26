# Wildfire-Detection-Transfer-Learning
A PyTorch project to detect wildfires from satellite imagery using ResNet18 and transfer learning. Achieves 96.10% accuracy on the unseen test set.

# 🔥 Wildfire Detection with Transfer Learning

A deep learning project to detect wildfires from satellite imagery using PyTorch and Transfer Learning with ResNet18. This model achieves **96.10% accuracy** on the unseen test set.

*(A Grad-CAM visualization will be added here to show model interpretability)*

---

## 🚀 The Goal

The goal of this project was to move beyond a simple baseline model and build a high-performance, deep learning classifier. The project demonstrates a full end-to-end machine learning workflow:
* Exploratory Data Analysis (EDA)
* A simple baseline model (Logistic Regression)
* A powerful deep learning model (ResNet18)
* A full training and validation pipeline to prevent overfitting
* Final, unbiased evaluation on a test set

## 🛠️ Tech Stack
* **Python 3**
* **PyTorch:** For building and training the deep learning model.
* **Torchvision:** For loading the pre-trained ResNet18 model and image transforms.
* **Scikit-learn (sklearn):** For the baseline model and performance metrics.
* **Pillow (PIL):** For loading and processing images.
* **Git LFS:** For versioning the large model file.

## 📊 Results: Baseline vs. Final Model

The transfer learning approach provided a massive **37.6% improvement in accuracy** over the simple baseline, demonstrating the power of deep learning for computer vision tasks.

| Model | Test Accuracy |
| :--- | :---: |
| Baseline (Logistic Regression) | 58.50% |
| **Final Model (ResNet18)** | **96.10%** |

---

## 🏃‍♀️ How to Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/Dhumra/Wildfire-Detection-Transfer-Learning.git](https://github.com/Dhumra/Wildfire-Detection-Transfer-Learning.git)
    cd Wildfire-Detection-Transfer-Learning
    ```
2.  **Install Git LFS** to pull the model file:
    ```bash
    git lfs install
    git lfs pull
    ```
3.  **Create a Python environment** and install the required packages (a `requirements.txt` file can be added later).

4.  **Run the Jupyter Notebook:**
    Open and run the cells in `Wildfire_Detection_Pipeline.ipynb`.

## 🔮 Future Work

* **[✅] Model Interpretability:** Implement Grad-CAM to create heatmaps and understand *why* the model is making its predictions.
* **[ ] Real-Time Deployment:** Build a real-time data stream project (e.g., monitoring the Twitter API) that uses this model to send alerts for newly-spotted wildfires.
