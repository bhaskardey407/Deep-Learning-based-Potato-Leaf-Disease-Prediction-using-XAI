# Potato Leaf Disease Detection Project

## Introduction
This repository contains the code and resources for a project aimed at detecting diseases in potato leaves using image classification techniques. The project employs Convolutional Neural Networks (CNNs) to classify the images of potato leaves into different disease categories. Additionally, it utilizes eXplainable Artificial Intelligence (XAI) techniques, specifically LIME (Local Interpretable Model-agnostic Explanations), to provide insights into the areas of the leaf responsible for particular predictions.

## Dataset
The dataset used for this project is sourced from Kaggle and consists of images of potato leaves affected by various diseases. The dataset can be accessed via the following link: [Potato Dataset](https://www.kaggle.com/datasets/arajmishra/potato-dataset)

## Model Development
Initially, a custom CNN model was developed, achieving an impressive accuracy of 99.85% in classifying potato leaf diseases. The model was trained on the provided dataset, enabling it to effectively differentiate between different disease states of potato leaves based on their images.

## eXplainable AI (XAI) with LIME
To enhance interpretability and provide insights into the model's decision-making process, eXplainable AI techniques were employed. LIME, a model-agnostic approach, was utilized to highlight the regions of the potato leaf images responsible for specific predictions made by the model. This helps in understanding the features or patterns within the images that contribute most significantly to the classification outcomes.

## Pre-trained CNN Models
In addition to the custom CNN model, several pre-trained CNN models were also utilized for training and classification purposes. The following pre-trained models were employed, along with their respective accuracies:

- ResNet50 Model: 99.27%
- ResNet152 Model: 99.51%
- InceptionV3 Model: 88.70%
- VGG16 Model: 95.43%
- VGG19 Model: 97.35%

These pre-trained models were fine-tuned on the potato leaf dataset to adapt them to the specific task of disease classification.

## Repository Structure
The repository is structured as follows:

- `code/`: Contains the source code for model development, training, and evaluation.
- `data/`: Directory for storing the dataset.
- `results/`: Stores the output and results obtained from model training and evaluation.
- `README.md`: Detailed information about the project, including setup instructions, usage guidelines, and results summary.

## Usage
To utilize the code and reproduce the results, follow these steps:
1. Clone the repository to your local machine.
2. Download the potato leaf dataset from the provided Kaggle link and place it in the `data/` directory.
3. Navigate to the `code/` directory and run the appropriate scripts for model training, evaluation, and XAI analysis.
4. Refer to the `README.md` file for detailed instructions on running the code and interpreting the results.

## Conclusion
The Potato Leaf Disease Detection Project demonstrates the effectiveness of CNNs in classifying diseases in potato leaves based on image data. By combining custom model development, pre-trained models, and eXplainable AI techniques, the project not only achieves high classification accuracy but also provides valuable insights into the decision-making process of the models. This can aid researchers and farmers in early disease detection and management, ultimately contributing to improved crop yield and agricultural sustainability.

For any inquiries or suggestions, please feel free to contact the project contributor.

## Contributor
- Bhaskar Dey

