# AI Plant Disease Detection

## Overview
This project uses deep learning to classify plant diseases from leaf images.  
The model is trained on the PlantVillage dataset and achieves approximately 95% validation accuracy.

## Features
- Image-based disease classification
- 38 plant disease categories
- Confidence score predictions
- CNN / MobileNetV2 model

## Dataset
- PlantVillage dataset (~54,000 images)
- 38 classes
- Images resized to 224x224
- 80% training / 20% validation split

## Model
We used a convolutional neural network and experimented with transfer learning (MobileNetV2) to improve performance.

The model detects:
- leaf discoloration
- spots and patterns
- texture changes

## Results
- Validation Accuracy: ~95%
- Strong performance across most classes
- Minor confusion between visually similar diseases

## How to Run
1. Clone the repository  
2. Install dependencies:  
   pip install -r requirements.txt  

3. Download dataset:  
   https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset  

4. Update dataset path in notebook:  
   path = "path_to_dataset"  

5. Run the notebook  

## Presentation
(Add your video link here)

## Contributors
- Walther Aragon  
- Justin Cabrera  
- Austin Nailor  
- Katiana Newbold  
- Daunte Williams  
