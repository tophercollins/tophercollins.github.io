## Portfolio

### Projects
**Data Analysis & Data Science**
- [Red Card / Goal Exploratory Data Analysis](/#red-card-goal-analysis)
- [EIFO Data Extraction](/#eifo-data-extraction)
- [Handwritten Character Recognition/Automated Scorecard Processing](/#handwritten-character-recognition)
- [Smoker vs. Non-Smoker Classification](/#smoker-classification)
- [Fine-tuning LLM for RPG Statblocks](/#rpg-statblock-generator)
- [Electric Vehicle kWh Consumption Forecasting](#ev-kwh-consumption-forecasting)
- [Bitcoin Price Forecasting](#bitcoin-price-forecasting)
- [Structured Medical Text Classification with NLP](#medical-text-classification)
- [Transfer Learning in Food Image Classification](#food-image-classification)


**Other**
- [DnDwithToph.com](/#dndwithtoph)
- [DnDwithToph Exploratory Data Analysis](/#dndwithtoph-eda)
- [Dungeons & Dragons Race Classification using Scikit-learn](/#dnd-race-classification)
- [Zombie Survival Game](/#zombie)

<div id='red-card-goal-analysis'></div>

---

[Red Card / Goal Exploratory Data Analysis](/red-card-goal-analysis.md)

- Processed and analyzed data across 20,000 European Football matches, using Pandas for data cleaning, feature engineering and data analysis.
- Conducted hypothesis testing with statistical models, including Poisson Means Tests and Linear Regression, to assess the relationship between red cards and goal-scoring.
- Visualized distribution patterns and event correlations using Matplotlib and Seaborn.

<img src="images/rcg_red_card_frequency.png?raw=true"/>
<img src="images/rcd_per_minute.png?raw=true"/>
<img src="images/rcg_linear_regression.png?raw=true"/>
<img src="images/rcg_goal_vs_poisson.png?raw=true"/>

<div id='eifo-data-extraction'></div>

---

[EIFO Data Extraction/Web Scraping](/eifo-data-extraction.md)

- Built a Python script to extract country risk and cover polcies from EIFO website.
- Used BeautifulSoup and Selenium (for dynamic website features) for data selection and extraction.
- Cleaned and transformed data in Pandas.
- Exported data to Excel output sheet.

<div id='handwritten-character-recognition'></div>

---

[Handwritten Character Recognition/Automated Scorecard Processing](/handwritten-character-recognition.md)

- Created a Convolutional Neural Network in TensorFlow to predict the class of a handwritten character.
- Artificially constructured characters with a strikethrough.
<img src="images/character-display-grid-normal.png?raw=true"/>
<img src="images/character-display-grid-strikethrough.png?raw=true"/>

- Used measures to avoid overfitting a Computer Vison task, such as Dropout, Batch Normalization, Kernal Regulization, and Data Augmentation.
- Achieved a 99% prediction accuracy on the test data.
- Model deployed for real world application of Education Scoresheet recogniton.

<div id='smoker-classification'></div>

---

[Smoker vs. Non-Smoker Classification](/smoker-classification.md)

- Created a Neural Network Stacking Classifier using Scikeras KerasClassifier and Scikit-learn's StackingClassifier.
- Used analysis of feature outliers and distrubtion to improve feature engineering.
<img src="images/smoker-outlier-distribution.png?raw=true"/>
<img src="images/smoker-outlier-distribution-2.png?raw=true"/>

- Combined Catboost, XGBoost, LightGBM and Random Forest Classifier models to create a balanced ensemble model.
- Utilized Tensorflow 2.0 Sequential Neural Network for improved ensemble weights.
- Achieved a final score of 0.87583 (compared with best of 0.87946), placing 283 out of 1910 submisions.

<div id='rpg-statblock-generator'></div>

---

[Fine-tuning LLM for RPG Statblocks](/rpg-statblock-generator.md)

- Created a **Fine-tuned** task specific model using Llama3 and Unsloth to create Dungeons & Dragons statblocks and game elements.
- Deployed on Hugging Face for accesible Training Dataset and LoRA Fine-tuned Adaptors.
<img src="images/dnd-statblock-generator-1.png"/>

<div id='ev-kwh-consumption-forecasting'></div>

---

[Electric Vehicle kWh Consumption Forecasting](/ev-kwh-consumption-forecasting.md)

- Explored forecasting daily kWh consumption for a workplace EV charging program and implemented naive, neural network, and LightGBM prediction models.

<div id='bitcoin-price-forecasting'></div>

---

Bitcoin Price Forecasting

- Implemented time series models (Conv1D, Bidirectional LSTM, GRU) for Bitcoin price forecasting, using metrics (Loss, MAE, MSE) to assess performance.


<div id='medical-text-classification'></div>

---

Structured Medical Text Classification with NLP

- Developed a multi-class NLP model utilizing Universal Sentence Encoder, Conv1D character embedding, and text position features to classify medical literature sentences, enhancing readability with structured paragraphs based on classification headings.

<div id='food-image-classification'></div>

---

Transfer Learning in Food Image Classification

- Developed computer vision model on Food101 dataset utilizing EfficientNetV2 transfer learning to achieve over 80% accuracy in categorizing 101 types of food images.

---

<div id='dndwithtoph'></div>

### Other

[DnDwithToph.com](https://dev.dndwithtoph.com/)
- **Flask** framework with **SQLAlchemy** database management
- User Authentication and Session Managment
- User-Generated Content following **CRUD** principles
- Production Server Deployment with **Gunicorn** and **Git** Version Control
  
<img src="images/dndwithtoph.png?raw=true"/>

<div id='eda'></div>

---

[DnD with Toph Exploratory Data Analysis](/dndwithtoph-eda.md)
- A financial assessment and report for 'DnD with Toph', an online Dungeons & Dragons adventure service, using Python and **Pandas** to clean, transform, and analyze the data.
- Used data to observe growth and profit trends to optimise future scheduling and projects.
- Skills include **Data Manipulation & Analysis** using Python & Pandas and **Data Visualization** with **Matplotlib**.

<img src="images/eda-optimal-timeslot.png?raw=true"/>

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

<div id='zombie'></div>

---

[Zombie Survival Game](/zombie-survival.md/)
- Developed a Python-based Zombie Survival Game, the mechanics involve managing resources, mission outcomes, and end-of-day round Zombie attacks.
- **Object-oriented programming** in Python to create Class Models for Camp, Locations, and Players.
- Utilized smaller functions for specific game mechanics and larger functions to implement and run game flow, mission outcomes, and end-of-round events.
- Employed **random library** and computer decision logic trees for computer-controlled players.

---
