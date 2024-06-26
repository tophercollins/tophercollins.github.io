## Portfolio

### Projects
**Data Science & Machine Learning**
- [Llama 3 Fine-tuning for Dungeons & Dragons Statblock Generator](/#dnd-statblock-generator)
- [Smoker Status Classification with Gradient Boosting Trees and Ensemble Stacking](/#smoker)
- [Handwritten Character Recognition Computer Vision](/#handwritten-character-recognition)
- [Dungeons & Dragons Race Classification using Scikit-learn](/#dnd-race-classification)

**Other**
- [DnDwithToph Exploratory Data Analysis](/#eda)
- [DnDwithToph.com](/#dndwithtoph)
- [Zombie Survival Game](/#zombie)

---

<div id='dnd-statblock-generator'></div>

---

[Llama 3 Fine-tuning for Dungeons & Dragons Statblock Generator](/dnd-statblock-generator.md)

- Created a **Fine-tuned** task specific model using Llama3 and Unsloth to create Dungeons & Dragons Statblocks.
- Implented online usability through Hugging Face for Training Dataset and LoRA Fine-tuned Adaptors.
<img src="images/dnd-statblock-generator-1.png"/>

---

<div id='smoker'></div>

---

[Smoker Status Binary Classification with Gradient Boosting Trees and Ensemble Stacking](/smoker-binary-classification.md)

- Created a Neural Network Stacking Classifier using Scikeras KerasClassifier and Scikit-learn's StackingClassifier.
- Used analysis of feature outliers and distrubtion to improve feature engineering.
<img src="images/smoker-outlier-distribution.png?raw=true"/>
<img src="images/smoker-outlier-distribution-2.png?raw=true"/>

- Combined Catboost, XGBoost, LightGBM and Random Forest Classifier models to create a balanced ensemble model.
- Utilized Tensorflow 2.0 Sequential Neural Network for improved ensemble weights.
- Achieved a final score of 0.87583 (compared with best of 0.87946), placing 283 out of 1910 submisions.
  
<div id='handwritten-character-recognition'></div>

---

[Handwritten Character Recognition Computer Vision](/handwritten-character-recognition.md)

- Created a Convolutional Neural Network in TensorFlow to predict the class of a handwritten character.
- Artificially constructured characters with a strikethrough.
<img src="images/character-display-grid-normal.png?raw=true"/>
<img src="images/character-display-grid-strikethrough.png?raw=true"/>

- Used measures to avoid overfitting a Computer Vison task, such as Dropout, Batch Normalization, Kernal Regulization, and Data Augmentation.
- Achieved a 99% prediction accuracy on the test data.
- Model deployed for real world application of Education Scoresheet recogniton.

<div id='dnd-race-classification'></div>

---

[Dungeons & Dragons Race Classification](/dnd-race-classification.md)

- Utilized **Machine Learning** techniques with **Scikit-learn** to predict character races based on ability scores and features from a Dungeons & Dragons dataset.
- Explored various models for selection, **Random Forest**, **Logistic Regression**, **Support Vector Classifier (SVC)**, **K-Nearest Neighbors (KNN)**, and **AdaBoost Classifier**.
<img src="images/dnd-model-baseline-comparison.png?raw=true"/>

- Conducted in-depth **feature analysis** and **model evaluation**.
- Fine-tuned hyperparameters of the best performing classfier through manual tuning, **RandomizedSearchCV** and **GridSearchCV**.
- Achieved an **accuracy of 67.25%** in predicting character races, improving on **51.8%** from the initial dataset.
<img src="images/dnd-rf-n-estimators.png?raw=true"/>
<img src="images/dnd-rf-cv-metrics.png?raw=true"/>

---

<div id='eda'></div>

### Other

[DnD with Toph Exploratory Data Analysis](/dndwithtoph-eda.md)
- A financial assessment and report for 'DnD with Toph', an online Dungeons & Dragons adventure service, using Python and **Pandas** to clean, transform, and analyze the data.
- Used data to observe growth and profit trends to optimise future scheduling and projects.
- Skills include **Data Manipulation & Analysis** using Python & Pandas and **Data Visualization** with **Matplotlib**.

<img src="images/eda-optimal-timeslot.png?raw=true"/>
<div id='dndwithtoph'></div>

---

[DnDwithToph.com](https://dev.dndwithtoph.com/)
- **Flask** framework with **SQLAlchemy** database management
- User Authentication and Session Managment
- User-Generated Content following **CRUD** principles
- Production Server Deployment with **Gunicorn** and **Git** Version Control
  
<img src="images/dndwithtoph.png?raw=true"/>
<div id='zombie'></div>

---

[Zombie Survival Game](/zombie-survival.md/)
- Developed a Python-based Zombie Survival Game, the mechanics involve managing resources, mission outcomes, and end-of-day round Zombie attacks.
- **Object-oriented programming** in Python to create Class Models for Camp, Locations, and Players.
- Utilized smaller functions for specific game mechanics and larger functions to implement and run game flow, mission outcomes, and end-of-round events.
- Employed **random library** and computer decision logic trees for computer-controlled players.

---
