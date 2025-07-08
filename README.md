**Psoriasis Skin Disease Classification**


This project focuses on building a machine learning model to classify skin images as either Normal or Diseased (Psoriasis). The model was developed using a Convolutional Neural Network (CNN) implemented in Python with TensorFlow and Keras, and trained using Google Colab.

**📁 Dataset**  
The dataset consists of images categorized into two folders:  

normal_skin/:   Contains images of healthy skin.

diseased_skin/:   Contains images showing signs of psoriasis.

Each image is resized and normalized for consistent training.

**🧠 Model Architecture**  
The CNN architecture used includes:  

Convolutional layers with ReLU activation

MaxPooling layers

Dropout for regularization

Dense layers for classification

The final layer uses a sigmoid activation function to output a binary classification (0 for normal, 1 for diseased).

**🚀 How to Run**  
**Clone the repository:**  

bash
Copy
Edit
git clone https://github.com/gayatrisrija1/skin-disease-prediction.git
cd psoriasis-classification
Open the psoriasis_classification.ipynb notebook in Google Colab.

Upload the dataset in the appropriate directory structure:  

dataset/  
  ├── normal_skin/  
  └── diseased_skin/  
Run the notebook cells sequentially to:  

Preprocess the data

Build and train the CNN model

Evaluate the model's accuracy

Save and test predictions

**📈 Results**  
The model achieves high accuracy in distinguishing between normal and diseased skin images, showing potential for aiding in early detection of psoriasis.

**🛠️ Tech Stack**  
Python

TensorFlow / Keras

Google Colab

NumPy

Matplotlib

**📌 Future Work**  
Integrate with a web or mobile interface for real-time diagnosis

Expand the dataset with more skin diseases

Deploy using TensorFlow Lite or Flask

**🤝 Contribution**  
Feel free to fork the repo, raise issues, or submit pull requests to enhance the model or its deployment.

**📄 License**  
This project is open source under the MIT License.

