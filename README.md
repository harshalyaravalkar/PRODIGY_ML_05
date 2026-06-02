# PRODIGY_ML_05

# Food Recognition and Calorie Estimation using Deep Learning

## Internship Details

* Company: Prodigy InfoTech
* Track Code: ML
* Task Number: 05
* Intern Name: Harshal Laxman Yaravalkar
* Domain: Machine Learning
* Duration: 1 Month
* Mentor: Prodigy InfoTech Team

---

## LinkedIn Post

As part of the internship requirements, I documented this task and the knowledge gained throughout the implementation process on LinkedIn.

🔗 LinkedIn Post:

[View LinkedIn Post](https://www.linkedin.com/posts/your-post-link-here)

---

## Task Objective

The objective of this task was to develop a Food Recognition and Calorie Estimation system using Deep Learning and Computer Vision techniques.

The model was trained to recognize different food items from images and estimate their approximate calorie content. Food recognition systems are widely used in health monitoring applications, diet tracking platforms, nutrition analysis tools, and smart healthcare systems.

This project demonstrates how image classification models can be applied to identify food categories and provide nutritional insights based on the predicted food item.

---

## Dataset

Dataset Source:

https://www.kaggle.com/datasets/kmader/food41

For this project, a custom subset was created from the Food-101 dataset to make training more efficient and focused.

Food Categories Used:

* Pizza
* Samosa
* Ice Cream
* Fried Rice
* French Fries
* Strawberry Shortcake
* Chicken Wings
* Donuts
* Pancakes
* Chicken Curry

Each category contained approximately 1000 images, resulting in a dataset of around 10,000 food images.

Dataset Structure:

```text
Food_subset/
│
├── pizza/
├── samosa/
├── ice_cream/
├── fried_rice/
├── french_fries/
├── strawberry_shortcake/
├── chicken_wings/
├── donuts/
├── pancakes/
└── chicken_curry/
```

---

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Scikit-Learn
* Jupyter Notebook

---

## Project Workflow

### 1. Data Collection

A subset of food images was selected from the Food-101 dataset and organized into separate folders based on food categories.

### 2. Data Preprocessing

Several preprocessing techniques were applied:

* Image loading
* Image resizing
* Normalization
* Dataset batching
* Label generation

These preprocessing steps ensured that the images were suitable for deep learning model training.

### 3. Dataset Preparation

The dataset was automatically split into:

* Training Dataset
* Validation Dataset

This allowed the model to be evaluated on unseen images during training.

### 4. Model Development

A Deep Learning image classification model was implemented using TensorFlow and Keras.

The model was trained to learn visual patterns from food images and classify them into one of the predefined food categories.

The architecture included:

* Data Augmentation Layers
* Feature Extraction Layers
* Dense Layers
* Softmax Output Layer

### 5. Model Training

The model was trained on thousands of food images over multiple epochs.

The Adam optimizer was used for optimization, while Sparse Categorical Crossentropy was used as the loss function.

### 6. Food Recognition

After training, the model was able to classify food images and predict the most likely food category.

### 7. Calorie Estimation

A calorie mapping system was implemented where each food category was associated with an estimated calorie value.

Example:

| Food Item            | Estimated Calories |
| -------------------- | ------------------ |
| Pizza                | 285 kcal           |
| Samosa               | 262 kcal           |
| Ice Cream            | 207 kcal           |
| Fried Rice           | 330 kcal           |
| French Fries         | 312 kcal           |
| Strawberry Shortcake | 250 kcal           |
| Chicken Wings        | 290 kcal           |
| Donuts               | 452 kcal           |
| Pancakes             | 227 kcal           |
| Chicken Curry        | 240 kcal           |

### 8. Visualization

Prediction results were visualized using sample food images, displaying both the predicted food category and estimated calorie content.

---

## Results

The model successfully classified food images into multiple categories and generated calorie estimates based on the predicted class.

This project demonstrated how deep learning and computer vision techniques can be combined to build intelligent food recognition systems capable of supporting nutrition-related applications.

---

## Key Learnings

During this task, I gained practical experience in:

* Deep Learning
* Computer Vision
* Image Classification
* TensorFlow and Keras
* Data Augmentation
* Food Recognition Systems
* Model Evaluation
* Nutrition and Calorie Estimation Applications

---

## Screenshots

### Dataset Loading

<img width="1165" height="134" alt="Screenshot 2026-06-02 175004" src="https://github.com/user-attachments/assets/edc81e48-9a3e-4239-8a74-ec6130c4cd7d" />


### Model Training Progress

<img width="1025" height="560" alt="Screenshot 2026-06-02 175116" src="https://github.com/user-attachments/assets/5327a302-797c-44f9-b884-85d22d14c937" />


### Accuracy Graph

<img width="631" height="191" alt="Screenshot 2026-06-02 175124" src="https://github.com/user-attachments/assets/ce79b85c-78d7-4894-ad93-af8295b3feb3" />

<img width="826" height="521" alt="Screenshot 2026-06-02 175133" src="https://github.com/user-attachments/assets/0998a74c-8fa3-4863-9325-1bc8b58d28dc" />



### Food Recognition Results

<img width="836" height="619" alt="Screenshot 2026-06-02 175157" src="https://github.com/user-attachments/assets/6b5029b5-c0c6-448f-ab9e-9193b86a1f30" />

---

## Conclusion

This project provided hands-on experience in building an end-to-end food recognition system using deep learning. By combining image classification with calorie estimation, I learned how machine learning can be applied to real-world health and nutrition problems.

The project successfully demonstrated the use of computer vision techniques for recognizing food items and generating nutritional information, highlighting the practical applications of artificial intelligence in healthcare and lifestyle management.

```

## How to Run

1. Clone the repository

```bash
git clone https://github.com/your-username/PRODIGY_ML_05.git
```

2. Install dependencies

```bash
pip install -r requirements.txt
```

3. Open Jupyter Notebook

```bash
jupyter notebook
```

4. Run all cells to train the model and generate food predictions with calorie estimates.

---

## Requirements

```txt
tensorflow
numpy
matplotlib
scikit-learn
jupyter
```

---

#MachineLearning #DeepLearning #ComputerVision #FoodRecognition #ImageClassification #TensorFlow #Keras #Python #DataScience #ArtificialIntelligence #ProdigyInfoTech #Internship
