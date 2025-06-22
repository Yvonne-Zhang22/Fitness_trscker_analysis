# 🏋️‍♀️ Gym Data Exploratory Data Analysis (EDA)

In this project, we perform an exploratory data analysis (EDA) on a gym-related dataset. Our objective is to uncover insights into customer behavior, gym attendance patterns, and potential business opportunities.

## 📌 Objectives

We aim to answer the following key questions:

- Is there any correlation between workout_frequency and BMI?
- How do average weight, BMI, calories burned, and fat percentage differ between male and female gym members?
- What's the real relationship between age and fitness decline?
- Do water intake patterns correlate with workout performance and recovery?
- Are there gender-specific patterns in workout preferences and outcomes?

## 🛠️ Technologies Used

- **Python**  
- **Pandas**, **NumPy** — for data manipulation  
- **Matplotlib**, **Seaborn** — for visualization  
- **Jupyter Notebook / Google Colab** — for interactive analysis  

## 📊 Project Workflow

1. **Import libraries** and load dataset  
2. **Clean and preprocess** the data  
3. Perform **univariate and bivariate analysis**  
4. Visualize **trends** over time and different categories
5. Summarize **business insights** and potential actions  

## 📁 Repository Structure

```
.
├── Project_1_EDA_gym_data_.ipynb    # Main notebook with EDA analysis
├── README.md                        # Project documentation
├── /data                            # Folder for any dataset files (if added later)
```

## Q1: Is there any correlation between workout_frequency and BMI?
<img width="867" alt="image" src="https://github.com/user-attachments/assets/402ff5e2-0c9a-4a1d-900c-4892f04055cd" />

As we can see from the bar chart, there is no significant drop in average BMI as workout frequency increases between 2 to 5 per weeks, which suggests that simply work out more days doesn't dramatistically affect the BMI. Meanwhile, there might be other factors who play bigger role like diet, intensity and body composition etc.

## Q2: How do average weight, BMI, calories burned, and fat percentage differ between male and female gym members?

<img width="867" alt="image" src="https://github.com/user-attachments/assets/b1b2ef8c-c84e-45a3-b5f4-7d28db7eb511" />

Average weight: From age 40 and above, females consistently weigh more than males on average across all age brackets.

<img width="874" alt="image" src="https://github.com/user-attachments/assets/004bd000-87ea-4659-8737-1749c947fcb6" />

Average BM： 
Across all age groups, males consistently have a slightly higher average BMI than females.
The BMI for both genders gradually increases with age, peaking in the 50+ group.

<img width="874" alt="image" src="https://github.com/user-attachments/assets/d0fe761b-a2b9-4a22-a7ba-98ec05454159" />

Average Calories: 
Males aged 1–20 and 20–30 burn significantly more calories on average than females in the same age groups.
In the 50+ age group, females surpass males slightly in average calories burned

<img width="874" alt="image" src="https://github.com/user-attachments/assets/fca1d8cb-d6f4-4176-a62d-bd56b6f773af" />

Average Fat Percentage: Across all age groups of gymrats, fat percentage stays relatively stable for both genders, hovering around 23–24%

<img width="874" alt="image" src="https://github.com/user-attachments/assets/5e87a4ef-3926-4722-b9b2-57b2c77d408e" />

Average Workout Frequency: Females slightly outperform males in workout frequency across most age brackets, particularly from 30–50+

## Q3: What's the real relationship between age and fitness decline?

<img width="1317" alt="image" src="https://github.com/user-attachments/assets/884d5318-1f2c-4902-969d-6f3ef9786148" />

1. Max Heart Rate Shows Clear Age Decline 📉
    Max heart rate drops from ~182-185 BPM at age 20 to ~172 BPM at age 60
2. Calorie Burn Capacity Remains Surprisingly Stable 🔥,stays relatively consistent (900-1200) across all ages
3. Fat Percentage Shows Minimal Age Effect, which contradicts common belief that fat percentage always increases with age. The author thinks it is because the gymrats have established great metablism through consistent workout and relatively clean diet for years, the steady fat percentage makes sense.
4. All age groups maintain 3-4 workouts per week on average
5. Cardiovascular fitness (Max-Resting HR) drops from ~118 to ~114
6. Age has minimal effect on fitness performance, 50-year-old advanced athletes perform similarly to 20-year-old advanced athletes.


## Q4: Do water intake patterns correlate with workout performance and recovery?

<img width="1323" alt="image" src="https://github.com/user-attachments/assets/45ed9f20-455c-4648-9eef-e39a636cf1e2" />
<img width="1326" alt="image" src="https://github.com/user-attachments/assets/ee01ce79-cd6d-4a37-9113-74e66cecf3dd" />

To my surprise, all the variables here show week correlation with water intakes. I have a few guesses:
1.Hydration level might be overhyped for performance.
2.Everyone is already adequately hydrated: The "low" group (2L) might still be sufficient.


## Q5: Are there gender-specific patterns in workout preferences and outcomes?

<img width="1332" alt="image" src="https://github.com/user-attachments/assets/7fad02e7-0f48-4a24-99f5-5efb65f4619e" />

Males prefer Strength (28%) and Cardio (28%), Yoga and HIIT are more popular among females than males.




## 📬 Contact

For any questions or feedback, feel free to reach out via yvonnezhang2244@gmail.com
