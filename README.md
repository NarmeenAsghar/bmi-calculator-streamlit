# BMI Calculator 🏋️‍♀️

## Overview
A simple app to calculate your **Body Mass Index (BMI)** based on weight and height. It categorizes BMI as:
- Underweight
- Healthy Weight
- Overweight
- Obese


## Features
- **Input**: Enter weight (kg) and height (cm).
- **Calculation**: Click "Calculate BMI" to see the result.
- **Categories**: Displays BMI categories (Underweight, Healthy Weight, etc.).
- **Expandable Info**: Learn about BMI and its limitations.


## Usage
1. Install Streamlit:
   ```
   pip install streamlit
   ```
2. Run the app:
   ```
   streamlit run bmi_calculator.py
   ```
3. Input your weight and height, then click "Calculate BMI".


## BMI Formula
\[
BMI = \frac{weight (kg)}{height (m)^2}
\]


## BMI Categories

| Category       | BMI Range  |
|----------------|------------|
| **Underweight** | < 18.5     |
| **Healthy Weight** | 18.5 - 24.9 |
| **Overweight** | 25 - 29.9  |
| **Obese**      | ≥ 30       |


## Notes
- BMI doesn’t account for muscle mass or fat distribution.
- May not be accurate for children or elderly people.
