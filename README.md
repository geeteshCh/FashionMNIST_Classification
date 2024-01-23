# Fashion MNIST classification using Deep learning

## Overview
In this project, both Convolutional Neural Network (CNN) and Dense Neural Network (DNN) models are developed and assessed for their effectiveness in image recognition task on Fashion MNIST dataset for classifying articles of clothing. Principal Component Analysis (PCA) and t-SNE is employed to analyse the data and assess correlations between dimensions information. PCA is also used to reduce dataset dimensions while preserving key information before feeding the data into the DNN. The utilization of these models on the Fashion MNIST dataset showcases their capabilities in handling complex image recognition tasks.

A more detailed analysis of this study can be found in the report attached to the repository.

**Blog link :** https://medium.com/@ksaraswat_97923/fashion-mnist-image-classification-deep-learning-using-dnn-and-cnn-675f786d1b0d

## Team
* Geetesh challur
*  Karan Saraswat
*  Venkat Pitta


## Requirements
* python 3.6+

## Installation
To install the required packages, run the following code inside the project folder
```bash
pip install torch torchvision matplotlib torchsummary scikit-learn numpy seaborn pandas 
```
## Usage
To execute the program, run the file 'Code.ipynb' in Jupyter Notebook or Google Collab or other editors.
To run the code file in Jupyter Notebook or JupyterLab:
```bash
jupyter notebook Code.ipynb
```
## Results

##### Deep Neural Network
The tuned DNN model attained a competitive accuracy of **89%** when tested on the unseen test set of 10,000 images, demonstrating effective generalization. The model performed very well in categories like T-shirt, Pullover, Dress and Shirt with F1 scores above 0.9, aided by large training samples.

##### Convolutional Neural Network
The best-performing CNN model based on validation accuracy was evaluated on the unseen test set. It achieved an accuracy of **90%**, outperforming many previous models in this domain.
## Business insights
The high accuracy achieved by the CNN model holds promising implications for a clothing company. The superior performance in image classification using CNNs suggests that such models can play a crucial role in automating the categorization of clothing items. This automation, driven by accurate and efficient algorithms, could streamline inventory management, enhance product recommendation systems, and ultimately contribute to an improved customer experience. The deployment of robust image classification models, as demonstrated in our study, has the potential to revolutionize various aspects of the clothing industry, offering efficiency gains and valuable insights for business decision-making.






