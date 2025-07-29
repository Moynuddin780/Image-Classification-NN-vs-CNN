# Image-Classification-NN-vs-CNN


Welcome to my **Iris Image Classification Project**! This repository showcases two machine learning models—**Neural Network (NN)** and **Convolutional Neural Network (CNN)**—built to classify Iris flower images into their respective species using the famous Iris dataset. The project includes detailed implementation, training, and evaluation processes for both models.

---

##  Project Overview

This project aims to classify Iris flower images into three species:
- **Iris Setosa**
- **Iris Versicolor**
- **Iris Virginica**

Both an NN and a CNN have been trained and evaluated to compare their performance. The code, results, and visualizations for both models are available here for you to explore!

---

##  Features

- Implementation of both NN and CNN models using TensorFlow/Keras.
- Data preprocessing and augmentation for enhanced model performance.
- Visualization of training accuracy, loss, ROC curves, and more for both models.
- Detailed evaluation metrics including confusion matrices and precision-recall curves.
- Hosted on GitHub for open access and collaboration.

---

##  Results

Both models demonstrate strong performance! Here are some key highlights:
- **NN Test Accuracy**: Achieved a competitive accuracy score 88.90%.
- **CNN Test Accuracy**: Achieved a high accuracy score 91.06%.
- **ROC AUC**: Strong discriminative power across classes for both models.

Check out the stunning visualizations below:

![NN ROC Curve](https://github.com/Moynuddin780/Image-Classification-NN-vs-CNN/blob/main/NN%20ROC%20Curve.png)  
![CNN ROC Curve](https://github.com/Moynuddin780/Image-Classification-NN-vs-CNN/blob/main/CNN%20ROC%20Curve.png)  
![Accuracy Comparison (NN vs CNN)](https://github.com/Moynuddin780/Image-Classification-NN-vs-CNN/blob/main/Model%20Accuracy%20Comparison.png)  
![Accuracy Loss Curve NN](https://github.com/Moynuddin780/Image-Classification-NN-vs-CNN/blob/main/Training%20History%20NN%20vs%20CNN.png)
![Accuracy Loss Curve CNN](https://github.com/Moynuddin780/Image-Classification-NN-vs-CNN/blob/main/Accuracy%20Loss%20Curve%20CNN.png)
![Model Performance Difference](https://github.com/Moynuddin780/Image-Classification-NN-vs-CNN/blob/main/Model%20Performance%20Difference.png)




---

##  How to Run

1. **Clone the Repository**  
   ```bash
   [git clone https://github.com/your-username/iris-classification.git](https://github.com/Moynuddin780/Image-Classification-NN-vs-CNN)
   ```

2. **Install Dependencies**  
   Ensure you have Python 3.x and the following libraries:
   - TensorFlow
   - NumPy
   - Matplotlib
   - Seaborn
   - Scikit-learn  
   Install them using:
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Script**  
   Execute the main Python file to train both models and generate results:
   ```bash
   python main.py
   ```

---

##  Project Structure

```
iris-classification/
│
├── data/              # Dataset and preprocessed files
├── models/            # Saved model weights for NN and CNN
├── images/            # Result images (ROC curves, accuracy plots, etc.)
├── main.py            # Main script to run the project
├── requirements.txt   # List of dependencies
└── README.md          # This file!
```

---

##  Contributions

Feel free to fork this repository, submit issues, or create pull requests. Your feedback and improvements are highly appreciated!

---

##  Acknowledgments

- Thanks to the Iris dataset creators for providing valuable data.
- Inspired by the TensorFlow and Keras communities for their amazing resources.

---

*Created with Love by Moynuddin Al Masum*
