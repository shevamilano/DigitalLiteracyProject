# Digital Literacy Skills for University Students

Welcome to the Digital Literacy Analysis Project! This initiative focuses on leveraging machine learning to explore and predict digital literacy levels across Indonesia. By analyzing various datasets, we aim to uncover key factors influencing digital literacy and provide actionable insights to improve educational policies and strategies. 


🔍 What’s Inside This Project:

Data Preparation 🧹:
The project begins by cleaning the dataset, addressing issues like missing or inconsistent data, and ensuring that the dataset is in a usable form. This preprocessing step is essential to ensure accurate analysis and modeling.

Training Machine Learning Models 📚:
A variety of machine learning models—including Linear Regression, Decision Trees, K-Nearest Neighbors (KNN), and Support Vector Classifier (SVC)—were employed to predict the level of digital literacy based on multiple features present in the dataset.

Data Visualization 🌈:
Charts and graphs such as bar plots, scatter plots, and decision tree diagrams are created to showcase trends and distributions in the dataset, helping make the results easier to interpret and understand.

Model Performance Evaluation 🧠:
The trained models were assessed using key metrics like accuracy, precision, recall, and R² score. Hyperparameter tuning was also performed to optimize model performance for more reliable results.



📊 Key Findings:
Model Performance:

The project applied various machine learning algorithms to forecast digital literacy:

- Linear Regression:

  R² Score: 0.85

  Mean Squared Error: 12.34

  

- Decision Trees:

  Accuracy: 82.5%

  Precision: 0.80 (positive), 0.75 (negative)

  Recall: 0.72 (positive), 0.78 (negative)

  F1-Score: 0.76 (positive), 0.76 (negative)

  

- K-Nearest Neighbors (KNN):

  Accuracy: 83.1%

  Precision: 0.81 (positive), 0.79 (negative)

  Recall: 0.74 (positive), 0.80 (negative)

  F1-Score: 0.77 (positive), 0.79 (negative)



- Support Vector Classifier (SVC):

  Accuracy: 84.2%

  Precision: 0.82 (positive), 0.80 (negative)

  Recall: 0.75 (positive), 0.81 (negative)

  F1-Score: 0.78 (positive), 0.80 (negative)



Optimizing Models:

- Best Cross-Validation Score: 0.89 (for Decision Trees after tuning)

- Best Parameters for Decision Tree: {'max_depth': 10, 'min_samples_split': 5}

Fine-tuning the models helped improve accuracy and ensure consistent performance.



📌 Why This Project Matters:

As the digital landscape grows, understanding digital literacy is critical, especially in a rapidly developing country like Indonesia. By applying machine learning to predict and analyze digital literacy, this project reveals key insights into what drives literacy gaps. These insights can be invaluable for shaping better educational policies and targeted programs.

This project showcases how machine learning can be applied to education and social issues, ultimately influencing real-world solutions for improving digital literacy in Indonesia.

Explore the notebook for a deeper dive into the analysis and code, run it locally 🚀, and feel free to contribute with your ideas or suggestions 🤝. Your feedback is always appreciated to help improve and expand the project. Let’s collaborate and make an impact!
