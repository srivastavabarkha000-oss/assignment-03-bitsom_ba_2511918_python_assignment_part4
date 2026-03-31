# assignment-03-bitsom_ba_2511918_python_assignment_part4
Part 4: Data Visualization &amp; Machine Learning
Theme: Student Performance Analysis & Prediction
Analyse a student performance dataset, produce meaningful visualizations, and build a machine learning model to predict whether a student will pass or fail — end to end.
Task 1: Data Exploration with Pandas
Task 2: Data Visualization with Matplotlib
Produce the following 5 plots. Each must have a descriptive title, labelled axes, and a legend where applicable. Save each plot as a .png file and display it inline.
1. Bar Chart: Average score per subject 
2. Histogram: Distribution of Math scores
3. Scatter Plot: Study Hours vs Avg Score
4. Box Plot: Attendance (Pass vs Fail)
5. Line Plot — Math & Science Scores per Student
Task 3: Data Visualization with Seaborn
1. Bar Plot — Math & Science vs Passed
2. Scatter Plot — Attendance vs Avg Score + Regression Lines
Task 4: Machine Learning with scikit-learn
Build a classifier to predict whether a student will pass or fail.
Step 1 — Prepare Data: Separate features and target. Split into train (80%) and test (20%) sets. Scale features using StandardScaler — fit on training data only, then transform both sets.
Step 2 — Train the Model: Train a LogisticRegression model on the scaled training data. Print the model's training accuracy.
Step 3 — Evaluate the Model: Predict on the test set and print the test accuracy.
Step 4 — Feature Importance: Extract the model coefficients. Pair each coefficient with its feature name and print them, sorted by absolute value (largest first).
Create a horizontal bar chart using Matplotlib showing all feature coefficients.
Step 5 — Predict for a New Student: Define a new student with values of your choice, scale it using scaler.transform(new_student) and predict using model.predict().
Print whether the model predicts Pass or Fail, and display the probability using model.predict_proba().
