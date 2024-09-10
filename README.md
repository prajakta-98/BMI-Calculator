BMI Calculator

 Description
This is a **Body Mass Index (BMI) Calculator** built using **HTML**, **CSS**, and **JavaScript**. It allows users to input their age, height, weight, and gender, and calculates their BMI based on these inputs. The app also classifies the BMI result into different categories (Underweight, Healthy, Overweight, Obese, Extremely obese).

Features
- Accepts **age**, **height (in cm)**, **weight (in kg)**, and **gender** as input.
- Validates the form to ensure all fields are filled before performing the calculation.
- Calculates the BMI using the formula: `BMI = weight / (height in meters)^2`
- Displays the calculated BMI along with a classification:
  - Underweight
  - Healthy
  - Overweight
  - Obese
  - Extremely obese

Technologies Used
- **HTML**: To create the structure of the form.
- **CSS**: For styling the form and the result display (linked via `style.css`).
- **JavaScript**: For form validation and BMI calculation logic.

How It Works
1. The user enters their age, height, and weight, and selects their gender.
2. On clicking the "Submit" button:
   - If all fields are filled, the BMI is calculated and displayed.
   - If any field is left empty, an alert prompts the user to fill in all the fields.
3. The BMI is calculated and displayed along with the classification.

Usage
1. Clone the repository and open the `index.html` file in your browser.
2. Input your details (age, gender, height, weight) and click **Submit** to view your BMI and classification.

