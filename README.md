# **Doodle Classifier (In Progress)**  
*Machine Learning-based Sketch Recognition*

## **Project Description**  
The **Doodle Classifier** is a machine learning model designed to classify hand-drawn doodles (e.g., **cats**) from the **QuickDraw dataset** provided by **Google Cloud Console**. The model is trained to recognize and predict user sketches by using a supervised learning approach, continuously improving its performance through iterative testing workflows.

### **Key Features**:
- **Supervised Machine Learning Model**: Trains on a large set of doodle images (800+ training samples and 200 test samples per class) to recognize common sketches.
- **Real-time Sketch Recognition**: Takes user doodles as input and provides live **predictions** and **visual feedback**.
- **Iterative Testing Workflows**: Continuously improves **model accuracy** and **feature learning**.

---

## **Technologies Used**:
- **Machine Learning**: Supervised learning techniques for sketch recognition.
- **Python**: Used for model training, data preprocessing, and API integration.
- **Google Cloud Console**: Accessing the **QuickDraw dataset** for training and testing.
- **TensorFlow** (optional): Framework for building the model.

---

## **Getting Started**:

### **Prerequisites**:
- **Python 3.x**: Install Python for running the training scripts and model code.
- **Libraries**: Make sure to install necessary Python libraries such as **TensorFlow**, **NumPy**, **Pandas**, and **Matplotlib** for data manipulation and visualization.

### **Installation**:
1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/yourusername/doodle-classifier.git
    ```

2. Navigate to the project directory:

   ```bash
   cd doodle-classifier
   ```

3. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```

4. Download the **QuickDraw dataset** from **Google Cloud Console** and place it in the project directory.

5. Run the training script to begin training the model:

   ```bash
   python train_model.py
   ```

---

## **Usage**:

1. **Input Doodle**: Draw a doodle in the provided input section.
2. **Real-time Prediction**: The model will predict your doodle and display the prediction with confidence.
3. **Model Testing**: Test the model's performance using the **200 test samples** that were set aside during training.
