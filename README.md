📝 Project Overview: Personality Analysis Using ML Models
🎯 Objective
This study investigated whether behavioral features like social activity, time spent alone, and event participation could:
Predict personality type (Introvert or Extrovert)

Estimate friend circle size

Group individuals into personality-like clusters

🛠️ Steps Performed
1. Data Understanding & Cleaning
Loaded a dataset with 2900 records and 8 behavioral attributes.

Target variable: Personality (Introvert / Extrovert).

Categorical features (Stage_fear, Drained_after_socializing, Personality) were encoded numerically.

Verified there were no missing values.

2. Exploratory Data Analysis (EDA)
Visualized distributions of all numerical features using histograms.

Created a correlation heatmap to understand how features relate to personality.

Time_spent_Alone and Drained_after_socializing showed positive correlation with Introverts.

Social_event_attendance, Going_outside, and Friends_circle_size aligned more with Extroverts.

🤖 Modeling
✅ 1. Logistic Regression (Classification)
Target: Predict Personality

Achieved:

Accuracy: 92.4%

Precision (Introvert): 91.5%

Recall (Introvert): 92.8%

Highly accurate classification using behavioral data.

📈 2. Linear Regression (Regression)
Target: Predict Friends_circle_size

Results:

R² Score: 0.67

Mean Squared Error: ~6.02

Indicates moderately good performance. Behavioral features can explain ~67% of variance in social circle size.

🔍 3. KMeans Clustering (Unsupervised Learning)
Applied KMeans with k=2 to group users into clusters based on behavior.

Used PCA for 2D visualization.

Found clear separation that aligns closely with personality traits (Introvert-like vs Extrovert-like behavior).

✅ Conclusion
This analysis confirms that personality traits can be effectively modeled using behavioral features.

Logistic Regression gave high classification accuracy with simple features.

Linear Regression showed we can moderately estimate social connectivity using habits.

KMeans clustering offered insight into natural groupings in behavior without labeled data.

📊 Implication
Such models can be used in:

Social psychology research

Mental health apps for personality assessment

Educational and workplace recommendations
