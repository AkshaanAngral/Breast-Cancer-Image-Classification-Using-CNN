# Breast Cancer Image Classification Using CNN
## Project Overview
The goal of this project is to develop a CNN model that can accurately classify breast cancer images. The project involves the following steps:
**Data importation and preprocessing.**
**Building and training the CNN model.**
**Evaluating the model's performance.**
**Visualizing the results.**
## Installation
 To set up the project locally, follow these steps:
 
**Clone the repository:**

```
git clone https://github.com/AkshaanAngral/breast_cancer_image_classification_Using_CNN.git
cd breast_cancer_image_classification_Using_CNN
```

**Install the required packages:**
```
pip install -r requirements.txt
```

**Set up Google Drive for data access:**
```
from google.colab import drive
drive.mount('/content/drive', force_remount=True)
```

## Usage
1. **Data Importation:** Import the necessary libraries and define the path to the dataset stored in Google Drive.

2. **Get Class Names and Image Count:** Get the class names and count the number of images in each class.

3. **Prepare the Dataset:** Split the dataset into training and validation sets.

4. **Build the Model:** Define and compile the CNN model.

5. **Train the Model:** Train the model on the training dataset and validate it on the validation dataset.

6. **Evaluate the Model:** Evaluate the model's performance and visualize the results.

# Dataset
The dataset contains images of breast tissue classified into three categories: benign, malignant, and normal. Ensure that your dataset is organized into subdirectories named 'benign', 'malignant', and 'normal', each containing the respective images.
# Model Architecture
The model is a Convolutional Neural Network (CNN) with the following layers:
1. **Three convolutional layers, each followed by a max pooling layer.**
   
2. **A dropout layer to prevent overfitting.**
   
3. **A flatten layer to convert the 2D matrix data to a vector.**
  
4. **Two dense (fully connected) layers, with the final layer having three neurons (one for each class) and a softmax activation function.**
## Results
After training for 10 epochs, the model achieves a reasonable accuracy on both the training and validation datasets. You can increase the number of epochs and fine-tune the model for better performance.

