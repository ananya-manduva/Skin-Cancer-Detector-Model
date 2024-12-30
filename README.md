# Melanoma Detection using Deep Learning

A Convolutional Neural Network (CNN) model for automated classification of skin lesions, focusing on early melanoma detection. This project aims to assist dermatologists in diagnosis, potentially reducing manual effort while maintaining high diagnostic accuracy.

## Problem Overview
Melanoma accounts for 75% of skin cancer deaths, making early detection crucial. Traditional manual visual inspection by dermatologists can be time-consuming and subject to human error. This project provides an automated solution using deep learning to classify nine types of skin lesions.

## Key Features
- Multi-class classification of 9 distinct types of skin lesions
- Implemented data augmentation techniques to address class imbalance
- Dropout layers for preventing overfitting
- Achieved ~84% training accuracy and ~79% validation accuracy
- Optimized for high sensitivity and specificity in melanoma detection

## Technical Highlights
- **Architecture**: Custom CNN model optimized for skin lesion classification
- **Data Augmentation**: Random flips, rotations, and zooms using the Augmentor package
- **Performance**: Successfully reduced the gap between training (84%) and validation (79%) accuracy
- **Class Balancing**: Specialized handling of imbalanced dataset, particularly for underrepresented classes like seborrheic keratosis (3.44%)

## Results
- Improved model generalization through data augmentation and dropout
- Successfully addressed initial overfitting issues (reduced from 35% gap to 5% gap between training and validation accuracy)
- Achieved target accuracy of approximately 80% on unseen data
- Note: Batch normalization was excluded due to underfitting tendencies

## Potential Impact
- Potential 50% reduction in diagnosis time for dermatologists
- Enhanced early detection capabilities
- Improved patient outcomes through timely intervention
- Scalable solution for efficient skin cancer screening

## Future Work
- Further optimization of model architecture
- Enhanced handling of class imbalance
- Integration with clinical workflows
- Extended validation on diverse patient populations

## Project Status
This project is part of ongoing research in automated melanoma detection. Contributions and feedback are welcome.
