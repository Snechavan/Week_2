Multi-Class Animal Classification
This project demonstrates how to classify images of 90 different animal species using a deep learning model built with TensorFlow and Keras. The model is based on the pre-trained MobileNetV2 architecture, which is fine-tuned to classify 90 animal species.

Dataset Overview
Number of classes: 90 different animal species.

Number of images: Approximately 5400 images (4860 for training, 540 for validation).

Image Dimensions: The images are resized to 224x224 pixels for model training.

Animal Classes
The dataset consists of 90 animal species, with each species representing a unique class. The animals span a variety of groups, including mammals, birds, reptiles, amphibians, and insects.


Multi_Class_Animal_Classification.ipynb: The Jupyter Notebook that contains the code to preprocess the dataset, build the model, and train it using the MobileNetV2 architecture.

How to Run the Project
1. Clone the Repository
To get started, clone the repository:

bash
Copy
git clone https://github.com/your-username/Multi_Class_Animal_Classification.git
cd Multi_Class_Animal_Classification
2. Install Dependencies
Install the required libraries using pip:

bash
Copy
pip install -r requirements.txt
3. Download the Dataset
The dataset can be downloaded from Kaggle or using Kaggle's API.

4. Running the Notebook
Once you have the dataset downloaded, open the Multi_Class_Animal_Classification.ipynb file in Jupyter Notebook or Google Colab. Run the cells sequentially to preprocess the data, build the model, and train it.

5. GPU Support
Ensure that you are using a GPU for faster model training. The notebook is set up to automatically detect and use a GPU if available.

Model
The model uses a MobileNetV2 architecture, pre-trained on ImageNet, and fine-tuned for animal classification. The model is further improved using data augmentation techniques to enhance its generalization ability.

Results
The model is trained to classify images into 90 animal categories. It outputs the predicted class label for each image, and the performance can be evaluated using metrics like accuracy and classification reports.

License
This project is licensed under the MIT License - see the LICENSE file for details.
