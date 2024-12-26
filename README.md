# Cookie Cats Mobile Games: A/B Testing & Player Retention Analysis

![Cookie Cats Banner](path_to_your_image.jpg)

---

## 📖 Introduction

[**Cookie Cats**](https://www.google.com/url?q=https%3A%2F%2Fwww.facebook.com%2Fcookiecatsgame) is a widely popular mobile puzzle game developed by [Tactile Entertainment](https://www.google.com/url?q=http%3A%2F%2Ftactile.dk%2F). The goal of this analysis is to evaluate the impact of moving the first gate in the game from level 30 to level 40 through an A/B testing approach.

As players progress through the game, gates occasionally require them to wait a non-trivial amount of time or make an in-app purchase to proceed. These gates serve dual purposes: encouraging purchases and enhancing player enjoyment by enforcing breaks.

---

## 💡 Problem Statement

The initial placement of the gate was at level 30. A change was proposed to move the gate to level 40, raising the question:

- **Does moving the gate affect player retention?**

---

## 🎯 Project Objectives

- Evaluate the impact of gate placement on **1-day retention** and **7-day retention**.
- Provide actionable insights for improving player retention.
- Explore potential reasons for the observed trends and propose recommendations.

---

## 📊 The Data

The dataset for this project includes player retention metrics collected during the A/B testing phase. The data is available in the repository under the file [cookie_cats.csv](link_to_dataset).

---

## 🛠️ Skills/Technologies Used

- **Languages**: Python
- **Libraries**: Pandas, Matplotlib
- **Methodologies**: A/B Testing, Bootstrapping, Z-tests, Hypothesis testing

---

## 📐 Project Methodology

1. **Data Exploration**:
   - Overview of dataset structure and summary statistics.

2. **A/B Testing**:
   - Calculation of **1-day** and **7-day retention** for both groups.
   - Bootstrapping analysis for uncertainty estimation.
   - Z-tests to formally compare groups.

3. **Results Interpretation**:
   - Evaluation of retention differences and associated probabilities.

4. **Conclusions and Recommendations**:
   - Summarization of findings and actionable insights.

---

## 📈 Results

### 1-Day Retention
- **Gate at Level 30**: Retention = 19.0%
- **Gate at Level 40**: Retention = 18.2%
- **Insights**: Retention is higher when the gate is at level 30, with a 96% probability that the difference is significant.

### 7-Day Retention
- **Gate at Level 30**: Retention = 19.0%
- **Gate at Level 40**: Retention = 18.2%
- **Insights**: Retention remains higher at level 30, with a 99.8% probability of significance.

---

## 📌 Conclusion

The analysis provides strong evidence that **both 1-day and 7-day retention are higher when the gate is placed at level 30**. Based on the results:

- **Recommendation**: Keep the gate at level 30 to maximize retention.
- **Possible Explanation**: Hedonic adaptation suggests earlier gates prolong enjoyment and prevent boredom, enhancing player engagement.

---

## 🚀 Future Recommendations

1. Analyze additional metrics like **in-game purchases** or **game rounds played**.
2. Test alternative gate placements beyond levels 30 and 40.
3. Perform a cost-benefit analysis to evaluate the financial implications of gate placement.

---

## 📥 How to Use This Repository

1. Clone the repository:  
   ```bash
   git clone https://github.com/yourusername/cookie-cats-ab-testing.git
