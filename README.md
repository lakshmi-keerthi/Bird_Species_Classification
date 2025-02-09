# **Leveraging Deep Learning Models for Bird Species Classification**

## **Overview**
This project focuses on classifying bird species from images using various deep learning models. We explore the effectiveness of **Convolutional Neural Networks (CNN)**, **ResNet**, **DenseNet**, and **Vision Transformer (ViT)** models, as well as an **ensemble method** to enhance the classification performance. The project uses a Kaggle dataset containing images of 20 bird species, with the aim of automating bird species recognition for ecological research and conservation efforts.

## **Key Objectives**
- Classify bird species using deep learning models, including **CNN**, **ResNet**, **DenseNet**, and **ViT**.
- Apply **data augmentation** and **image transformations** to improve model generalization.
- Compare the performance of different models and enhance results using an **ensemble method**.

## **Tools & Technologies**
- **Python**: For data manipulation and model development.
- **PyTorch**: Deep learning framework used for building and training the models.
- **Kaggle Dataset**: Contains images of 20 bird species for training and testing.
- **OpenCV & PIL**: Libraries for image processing.
- **Matplotlib & Seaborn**: Data visualization libraries to display training results.

## **Workflow**
1. **Data Collection**: Used a Kaggle dataset of 3408 images across 20 bird species.
2. **Data Preprocessing**: Applied **data augmentation** and resized images to 224x224 for training.
3. **Model Selection**: Trained and evaluated **CNN**, **ResNet**, **DenseNet**, and **Vision Transformer (ViT)** models.
4. **Model Optimization**: Used an **ensemble method** combining the predictions of the best-performing models for enhanced accuracy.
5. **Model Evaluation**: Tested models on unseen data and compared accuracies to identify the best approach.

## **Model Performance**
- **CNN**: Achieved 78% accuracy.
- **ResNet**: Achieved 89% accuracy.
- **DenseNet**: Achieved 92% accuracy.
- **Vision Transformer (ViT)**: Achieved 74% accuracy.
- **Ensemble Model**: Combined predictions from **CNN**, **ResNet**, and **DenseNet** for a final accuracy of 93%.

## **How to Run the Code**
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/bird-species-classification.git
