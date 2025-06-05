# stroke_prediction_journal
My ML learning journey through the stroke prediction competition
🧠 Stroke Risk Prediction Challenge – Level 0

Welcome to my first attempt at solving a medical machine learning problem: predicting the likelihood of a stroke based on patient data. This marks Level 0 of my ML learning journey — focusing on understanding the complete end-to-end process manually before moving on to advanced or automated tools.

    🛠️ Workflow

This is my approach for Level 0 using Python:

Data Loading

Imported the dataset using pandas

Explored structure, null values, and statistical properties

Preprocessing

Handled missing values (bmi)

Encoded categorical variables using LabelEncoder

Selected important features for modeling

Model Selection

Chose a RandomForestClassifier for its robustness and simplicity

Trained the model on 80% of the data, tested on 20%

Evaluation

Used accuracy_score to evaluate performance

Generated a CSV of predictions (id, stroke) for final submission

   🛠️ Techniques & Tools Used

Languages: Python

Libraries:

pandas, numpy for data handling

sklearn for model training, evaluation, and preprocessing

Model: RandomForestClassifier from scikit-learn

Categorical Encoding: Used LabelEncoder (not one-hot encoding)

Assistance: Code was partially written and debugged with the help of ChatGPT

    🚧 Challenges Faced & How I Addressed Them
Understanding the ML pipeline from scratch: I broke down the problem into small, manageable steps and explored each one independently.

Preprocessing categorical variables: I used LabelEncoder to convert text-based categories into numerical format without introducing extra complexity.

Handling missing data in bmi: I checked the distribution and replaced missing values with the median to maintain consistency.

Knowing how to evaluate a classifier: I learned and applied accuracy_score as a simple and effective way to evaluate my model's predictions.

    🦮🏻 Reflections & Learnings

Machine learning isn't just about throwing data into a model — the data preprocessing stage was just as important as model selection.

Even a basic model like Random Forest can perform decently with minimal tuning.

I now understand how to build a model from raw data to prediction submission — something that seemed scary before!

I used ChatGPT as a learning partner to understand and write code snippets — a huge help in bridging my theory and practice.
