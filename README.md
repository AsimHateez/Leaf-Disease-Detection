#  Leaf Disease Detection using CNN (Google Colab)

A simple deep learning project for detecting and classifying plant leaf diseases using a Convolutional Neural Network (CNN). Built with Python, TensorFlow, Keras, and OpenCV, and implemented in Google Colab.

##  Objective
To classify leaf images as healthy or diseased, helping in early diagnosis and efficient crop management using AI.

##  Technologies Used
- Python
- TensorFlow / Keras
- OpenCV
- Google Colab

##  Dataset Structure
Organize your dataset like this:
dataset/
├── train/
│ ├── Class1/
│ ├── Class2/
│ └── ...
└── test/
├── Class1/
├── Class2/
└── ...


You can use any plant leaf dataset with labeled folders.

##  How to Use
1. Open the [Colab Notebook](https://colab.research.google.com/drive/1ibM09OdY0D62xUphfbwdN24_lnC-G98L?usp=sharing).
2. Upload your dataset to your Colab session.
3. Run all cells in order: preprocessing, training, evaluation.
4. Test the model with your own leaf images.

##  Model Summary
- Custom CNN architecture
- Image preprocessing (resizing, normalization)
- Accuracy and loss plots for training evaluation
- Achieves decent accuracy on small datasets

##  Sample Output
You’ll see:
- Accuracy/Loss graphs
- Model predictions on test images

##  Future Improvements
- Integrate transfer learning (e.g., MobileNet)
- Add real-time prediction with camera
- Deploy as a web or mobile app



© 2025 Muhammad Asim Hateez
