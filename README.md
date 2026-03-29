# Health-Insurance-Cost-Predict

# 1. Project Title & Brief Overview
I am currently a penultimate statiatics major student.
My LinkedIn: www.linkedin.com/in/heidi-u-9282a3292. Welcome to connect me!
This is my first project: *Medical Cost Analysis: Predicting Insurance Premiums*
It is mainly a GLM-based health insurance pricing model with premium calculator.
In here, my goal is to explore how factors including age, sex, bmi, number of children, smoking, residential area affects individual medical costs.

# 2. Dataset Source
Medical Cost Personal Dataset from https://www.kaggle.com/datasets/mirichoi0218/insurance

Columns:
- age: age of primary beneficiary
- sex: insurance contractor gender, female, male
- bmi: Body mass index, providing an understanding of body, weights that are relatively high or low relative to height, objective index of body weight (kg / m ^ 2) using the ratio of height to weight, ideally 18.5 to 24.9
- children: Number of children covered by health insurance / Number of dependents
- smoker: Smoking
- region: the beneficiary's residential area in the US, northeast, southeast, southwest, northwest.
- charges: Individual medical costs billed by health insurance

# 3. Key questions
a) How to calculate the premium for each individual?
b) What is the premiums for each individual?

# 4. Tools & Liabraries
Language: Python
Liabraries: Pandas, NumPy, Matplotlib.pyplot, Seaborn, Sklearn

# 5. Method
- Create and train GLM (Gamma with Log Link)

# 6.  Key Insights & Visualizations
- MAE: $4155; RMSE: $7307
- Mean Actual Charges: $12968; Mean Predicted Premium: $14015
- Training-Test ratio: 8:2
-<img width="1026" height="491" alt="download" src="https://github.com/user-attachments/assets/ceb97ee5-a25d-4e8e-a67e-f71230f8d673" />
- How factors affect premium?
• Age:      +2.9% per year 
• BMI:      +1.4% per unit 
• Children: +7.7% per child 
• Gender:   Male pays -6.2% more than female 
• Smoking:  Smoker pays 4.44x more than non-smoker 
• Region:   northwest pays 5.0% less than Northeast 
• Region:   southeast pays 10.8% less than Northeast 
• Region:   southwest pays 13.9% less than Northeast
- Smoking is the strongest predictor

Assume Expense loading = 20%, Profit loading = 5%, Risk loading =5%
- Pure Premium: $5565
- Gross Premium: $7234

More details to be updated.
