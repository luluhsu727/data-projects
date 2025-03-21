# Sleep Health and Lifestyle

## Project Overview
This project explores the relationships between sleep, cardiovascular health, and lifestyle factors. Using a synthetic dataset containing sleep metrics, physical activity levels, and cardiovascular indicators, we aim to identify patterns that contribute to sleep disorders and overall well-being.

## Project Structure
- `data/` → Contains `data.csv`, the dataset used for analysis
- `notebooks/` → Jupyter notebooks with exploratory data analysis (EDA) and model building
- `scripts/` → Python scripts for data preprocessing and machine learning
- `models/` → Saved machine learning models
- `outputs/` → Visualizations, reports, and final results

## Dataset Details
- **Source:** Kaggle
- **Number of records:** ~400 fictive persons
- **Columns:**
  - `Person ID`
  - `Gender`
  - `Age`
  - `Occupation`
  - `Sleep Duration` (hours per day)
  - `Quality of Sleep` (1-10 subjective rating)
  - `Physical Activity Level` (minutes per day)
  - `Stress Level` (1-10 subjective rating)
  - `BMI Category`
  - `Blood Pressure` (systolic/diastolic)
  - `Heart Rate` (beats per minute)
  - `Daily Steps`
  - `Sleep Disorder` (None, Insomnia, Sleep Apnea)

## Questions to Explore
- Which factors contribute to a sleep disorder?
- Does increased physical activity improve sleep quality?
- How does a sleep disorder affect subjective sleep quality?

## Visualisation
- **Boxplot**: Show the distribution of sleep duration or sleep quality by occupation.
- **Scatterplot**: Analyze the relationship between age and sleep duration, incorporating sleep disorder information.

## Project Scenario: Predicting Sleep Disorders
### Background
A health insurance company wants to assess the likelihood of potential clients having a sleep disorder. This information could influence premium pricing decisions.

### Objective
Build a **classifier** to predict the presence of a sleep disorder using other features in the dataset.

## How to Run This Project
1. Clone this repository:
   ```bash
   git clone https://github.com/luluhsu727/data-science-portfolio.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the notebook or script:
   ```bash
   jupyter notebook notebooks/exploratory_analysis.ipynb
   ```
   or
   ```bash
   python scripts/train_model.py
   ```

## Technologies Used
- Python
- Pandas, NumPy, Matplotlib, Seaborn
- Scikit-learn (for machine learning models)
- Jupyter Notebook

## Credits & Acknowledgments
- Dataset Source: Kaggle
- Inspired by real-world applications in health analytics

