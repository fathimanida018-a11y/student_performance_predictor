Student Performance Predictor

About the Project:
The Student Performance Predictor is a beginner-friendly machine learning project that predicts a student's target CGPA (out of 10) using study hours, attendance, and previous CGPA.

Features:
- Uses student data to train a machine learning model.
- Predicts target CGPA using Linear Regression.
- Accepts student details through user input.
- Includes input validation for study hours, attendance, and CGPA.
- Provides basic feedback based on the predicted CGPA.

Technologies Used:
- Python
- Pandas
- NumPy
- Jupyter Notebook
- Linear Regression using NumPy's least-squares method

How It Works:
1. Creates a sample student performance dataset.
2. Organizes and processes the data using Pandas.
3. Separates input features from the target CGPA.
4. Splits the data into training and testing sets.
5. Trains a Linear Regression model using NumPy.
6. Evaluates the model using R² score and Mean Absolute Error (MAE).
7. Accepts new student details and predicts their target CGPA.

Input Features:
- Study Hours:Average hours spent studying per day.
- Attendance:Attendance percentage.
- Previous CGPA:Student's previous CGPA out of 10.

Target Variable
Target CGPA:The CGPA the model aims to predict, out of 10.

Dataset
The project currently uses 10 sample student records. The target CGPA values are illustrative and are intended for learning and testing the model.

Limitations
- The dataset is very small.
- The sample data is illustrative and does not represent verified real-world student outcomes.
- Predictions may not be accurate enough for real academic decisions.
- More realistic data and additional testing are needed to improve reliability.

Future Improvements
- Use a larger dataset with actual student performance outcomes.
- Improve model accuracy and evaluation.
- Add more relevant student performance features.
- Build a simple user interface for easier use.

## Project Status
Beginner-level machine learning prototype — under development.
