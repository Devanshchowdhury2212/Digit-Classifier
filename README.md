# Digit-Classifier with CNN along with different Image Processing Techniques

## Description

Standard Nueral Networks require large amount of time and nuerons for processing image related data . CNN which stands for Convolutional Nueral Network is aimed to overcome these boundary
and giving state of art results with huge reduction in time for modeling .Ofcourse we can do better using various preprocessing techniques as each improvement counts .


## Main features

- Detect the digit in the image and give predictions with more than 99% Accuracy.		

## Tech Stack and concepts used

- Python
- Keras
- Matplotlib
- Convolution Neural Network


## Thought behind the project

Exploring Computer vision fundamentals thorugh CNN and various Image Processing Technique .

# Setup
- Open Terminal or Command Prompt
- Input > git clone git@github.com:Devanshchowdhury2212/Digit-Classifier.git
  to download the repository
 

## Results

| Model                                             				| Training Set Accuracy | Validation Set Accuracy | Testing Set Accuracy |
| -----------------------------------------------------				| --------------------- | ----------------------- | -------------------- |
| Basic CNN model                                   				| 99.90 %               | 99.95 %                 | 99.100 %              |
| CNN model with Data Augmentation                  				| 99.87 %               | 99.82 %                 | 98.928 %              |
| CNN model with Data Augmentation(Hyperparamter Tweaks{Batch sizing , steps}) 	| 99.95 %               | 99.94 %                 | 98.596 %              |
| CNN model with Data Augmentation (Hyperparamter Tweaks{Splits,Augmentation})	| 99.96 %               | 99.55 %                 | 99.271 %              |
| CNN model (Architecture like VGG)						| 98.76 %               | 98.63 %                 | 99.064 %              |
| CNN model with Data Augmentation (Image generator new features)          	| 99.20 %               | 98.37 %                 | 99.300 %              |
| CNN model with Data Augmentation (Regularazation)                         	| 99.42 %               | 98.98 %                 | 99.350 %              |
| CNN model with Data Augmentation (Tweaking Regularazation) 			| 99.54 %               | 98.93 %                 | 99.389 %              |
| CNN model with Data Augmentation (Dense Layers Addition)			| 99.49 %               | 99.31 %                 | 99.428 %              |
| CNN model with Data Augmentation (Final Hyperparameters tweak)			| 99.57 %               | 99.06 %                 | 98.935 %              |
| STACKED PREDICITONS								| -                     | -			 | 99.589 %		|

## Link to Kaggle Notebook
https://www.kaggle.com/devanshchowdhury/digit-classfier-acc-99?scriptVersionId=65573189
## Link to Kaggle Competetion
https://www.kaggle.com/c/digit-recognizer
