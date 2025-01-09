# Arda Cabaroglu Project for DSA 210 

## Motivation

Hello, my name is Arda Cabaroglu (32270). For this project, I want to explore how different aspects of my physical activity levels, such as daily calorie expenditure and step counts, change based on my academic workload. I will analyze the available data for periods such as midterm weeks, previous semesters, and the current semester to find patterns that show how schoolwork affects my activity levels. This will help me understand how academic stress impacts my health and daily habits.

## What is Active Energy?

Active energy is the calories burned through physical activities like walking, exercising, or other movements during the day. It is different from resting energy, which is the calories burned to keep the body functioning at rest. Active energy focuses on the energy used during intentional physical activity.

## Data Source

I will use data collected from my Apple Watch, focusing on:

1. **Active Energy:** Calories burned daily during different periods, such as midterm weeks, previous semesters, and the current semester.
2. **Step Count:** Daily step counts collected over time to see how activity levels change with academic workload.
3. **Floors Climbed:** Data on the number of floors climbed each day to assess physical activity related to elevation.
4. **Standing Hours:** Data on daily standing hours to evaluate how much time is spent standing throughout the day.

The data is automatically recorded by my Apple Watch and synced with the Health app on my iPhone. I will export this data as XML files from the Health app and use Python tools like Pandas and Beautiful Soup to process and analyze it.

## Data Analysis Plan

1. **Import the XML File:**

   - Load the data exported from the Health app.

2. **Data Parsing:**

   - Use the Python library "Beautiful Soup" to read the XML file and get the calorie, step count, floors climbed, and standing hours data.

3. **Exploratory Data Analysis (EDA):**

   - Use Pandas to clean and organize the data.
   - Check the patterns in calories burned, step counts, floors climbed, and standing hours.
   - Look for trends or unusual changes during midterm weeks and other periods.

4. **Visualization:**

   - Use Matplotlib to create charts showing changes in calories burned, step counts, floors climbed, and standing hours over time and across different periods.

5. **Statistical Analysis:**

   - Check if there is a connection between academic workload and physical activity levels.
   - Compare step counts, calorie data, floors climbed, and standing hours between periods to see how academic demands affect activity levels.
     
6. **Hypothesis**
Null Hypothesis (H₀): There is no significant difference in average step counts between the current semester (Sophomore 2) and previous semesters (Prep, Freshman 1, Freshman 2, and Sophomore 1).

Alternative Hypothesis (H₁): The average step counts in the current semester (Sophomore 2) are significantly lower than in previous semesters.

## Goal

The main goal is to understand how different aspects of my physical activity levels, such as calories burned, step counts, floors climbed, and standing hours, change with my academic workload. By studying available data from midterm weeks, previous semesters, and the current semester, I want to find patterns and connections between school stress and physical activity.



