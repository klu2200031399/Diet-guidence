

# Diet Planning with BMI Calculator

## Overview

This project provides a comprehensive solution for users to calculate their Body Mass Index (BMI) and receive personalized diet plans based on their BMI results. It is built using JSP, Servlets, MySQL, and runs in either CodeReady Studio or Eclipse IDE. The application helps users maintain a healthy lifestyle by recommending diet plans based on their weight and height measurements.

## Features

- **User Login & Signup:** Secure user authentication to personalize diet plans.
- **BMI Calculator:** Enter weight and height to compute BMI.
- **Personalized Diet Plans:** Based on BMI categories (Underweight, Normal, Overweight, Obese).
- **Navigation via Sidebar:** Smooth and intuitive navigation with sidebar buttons.
- **Responsive Design:** A user-friendly interface styled similar to a real calculator.
  
## Technologies Used

- Java Servlets & JSP
- MySQL for data storage
- JBoss Server (CodeReady Studio)
- HTML/CSS for the frontend

## Setup Instructions

### Prerequisites

- CodeReady Studio or Eclipse IDE
- JBoss or any servlet container
- MySQL Database

### Steps to Run the Project

1. **Clone the Repository:**
   ```bash
   git clone <repository-url>
   ```

2. **Import Project into CodeReady Studio / Eclipse IDE:**
   - Open CodeReady Studio or Eclipse.
   - Click on `File -> Import -> Maven -> Existing Maven Projects`.
   - Select the cloned project folder.
   
3. **Ensure Maven Dependencies Are Set:**
   - Check that all necessary packages from the `pom.xml` are resolved. If not, update the project with Maven (`Right-click -> Maven -> Update Project`).

4. **Set up the Database:**
   - Create a MySQL database using the `diet_plan.sql` file included in the repository.
   - Configure the database connection in the `config.properties` file.

5. **Run the Application:**
   - Deploy the project using JBoss Server.
   - Access the application at `http://localhost:8080/diet-planner`.

## Usage

1. **Login / Signup:** Users need to create an account or log in to access the BMI calculator.
2. **BMI Calculation:** After entering the weight and height, the BMI is calculated and displayed.
3. **Diet Plan Suggestions:** Based on the BMI result, a customized diet plan will be recommended.

## BMI Categories & Diet Plan Recommendations

- **Underweight:** High-protein, calorie-dense diet suggestions.
- **Normal:** Balanced diet with adequate nutrients.
- **Overweight:** Low-calorie, high-fiber diet recommendations.
- **Obese:** Strict, low-fat, and high-fiber diet plans with exercise recommendations.

## Future Enhancements

- Integration with API for more dynamic diet plan recommendations.
- Enhanced UI/UX for better user experience.
- Additional features like exercise suggestions based on user goals.


Feel free to modify this according to the specific details of your project!
