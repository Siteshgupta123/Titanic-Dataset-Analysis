![Titanic Logo](https://github.com/user-attachments/assets/61399680-62b1-4a50-a7ae-00a21fa0a54b)

# 🚢 Titanic Dataset Dashboard — Power BI Analysis
### 📊Overview:
To perform exploratory data analysis (EDA) on the Titanic dataset and build an interactive Power BI dashboard that uncovers survival patterns based on demographic, socioeconomic, and boarding-related factors.

------------------------
### 🎯Objective
To analyze the Titanic dataset and highlight key passenger demographics, fare distributions, and survival rates through dynamic, filter-driven visuals in Power BI. The goal is to identify patterns that influenced survival, while creating a dashboard that is both informative and presentation-ready.

---------------------------------
🖼️Dashboard Preview :
![Dashboard Preview](https://github.com/user-attachments/assets/523a80cf-55b3-47cb-aa98-330d3ece8df1)

-------------------------------------
# 📁 Dataset Description:
- Source: [Titanic Dataset (Cleaned CSV)](https://github.com/Siteshgupta123/Titanic-Dataset-Analysis/blob/main/Titanic%20Dataset%20Cleaned.csv)
- Rows: 1309 passengers
- Key Fields:
  - Survived: 0 = No, 1 = Yes
  - Sex: 0 = Male, 1 = Female
  - Pclass: 1 = First, 2 = Second, 3 = Third
  - Embarked: 0 = Cherbourg, 1 = Queenstown, 2 = Southampton
  - Fare, Age, sibsp, Parch
>**All categorical fields were numerically encoded. Additional columns were derived for interpretation (e.g., Age_Group, Gender_Label, Pclass_Label).**

----------------------------

## 🔍 Steps Taken (Cleaning, Analysis)
- Removed null values and corrected data types
- Encoded binary categories (Survived, Sex, Embarked) with readable labels
- Created new calculated columns:
  - Age_Group: For demographic segmentation
  - Gender_Label, Pclass_Label, Not_Survived
- Developed DAX measures for:
  - Total counts (e.g. passengers, survivors by group)
  - Survival rates by gender, class, and age group
- Designed slicer-friendly fields (Age slider, Class, Embarked, Sex.
## 🔄 Interactive Filters (Slicers)
- Age Slider
- Sex (Male/Female)
- Pclass (First/Second/Third)
- Embarked Port
- Age Group

----------------------------------------------------
## 📈 Key Insights from the Dashboard:
 - Total Passengers: 1309
   - Non-Survivors: 809 (62%)
   - Survivors: 500 (38%)
> **The tragedy led to more than half the passengers perishing.** 
- Survival Rate by Gender:
  - Female: 74.1% survived
  - Male: 18.1% survived
> **Dramatically higher survival among women, aligning with “women and children first.**
- Survival Rate by Class:
  - First Class: 62.4%
  - Second Class: 47.3%
  - Third Class: 24.2%
>**Survival clearly favored higher socioeconomic status.**
- Fare Distribution:
  - Average Fare (First Class): ₹84.15
  - Average Fare (Third Class): ₹13.15
>**Strong gap in fare pricing—mirrored by survival outcomes.**
- Age Group Breakdown:
  - 0–17: 112 passengers, 49.1% survived
  - 18–40: 675 passengers, 36.9% survived
  - 41–60: 276 passengers, 38.4% survived
  - 60+: 83 passengers, 26.5% survived
- 🚢 Embarked From:
  - Southampton: 914 passengers (70%)
  - Cherbourg: 270 passengers(20.6%)
  - Queenstown: 123 passengers(9.3%)
>**Most passengers boarded at Southampton.**

 ### Interesting Observations
- Women had dramatically higher survival rates due to evacuation priority
- Children under 12 fared better than most adult males in Third Class
- Socioeconomic status played a major role—1st Class passengers were more than twice as likely to survive as those in 3rd
- Over 70% of all passengers boarded at Southampton, many of whom were from lower economic backgrounds

----------------------------
## 🛠 Tech Stack
- Power BI Desktop
- DAX (Data Analysis Expressions)
- CSV Data Source (Cleaned)

-------------------------
## Thank You! 💙
Thanks for checking out my project! If you found it useful, please consider:  
[![GitHub stars](https://github.com/Siteshgupta123](https://github.com/Siteshgupta123/Titanic-Dataset-Analysis))  
⭐ **Starring** the repo  
🐛 **Reporting** issues  
🛠 **Contributing** improvements  

Crreated with❤️ by **Sitesh Gupta**  
🔗 www.linkedin.com/in/guptasitesh | 💌 Email-guptasitesh05@email.com

------------------------------------------
