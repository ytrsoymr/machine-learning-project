# Machine Learning Prediction Flask App

This project demonstrates a Flask-based web application that predicts outcomes using a machine learning pipeline. The app takes user input via a web form, processes the data, and returns predictions based on a trained model.

---

## Features
- **Home Page:** Displays an introduction to the application.
- **Prediction Page:** Allows users to input data and receive predictions.
- **Modular Code Structure:** Includes a pipeline for data preprocessing and prediction.
- **User-Friendly Interface:** Designed using HTML templates (`index.html` and `home.html`).

---

## Prerequisites

Ensure you have the following installed:
- Python (>= 3.8)
- Flask
- NumPy
- Pandas
- scikit-learn

Install all required dependencies:
```bash
pip install -r requirements.txt
```

---

## Project Structure
```
project/
├── app.py                    # Main Flask application
├── templates/
│   ├── index.html            # Home page template
│   ├── home.html             # Prediction page template
├── src/
│   ├── pipeline/
│       ├── __init__.py       # Module initializer
│       ├── predict_pipeline.py  # Prediction pipeline implementation
├── requirements.txt          # Python dependencies
└── README.md                 # Project documentation
```

---

## How to Run

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd project
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the Flask application:
   ```bash
   python app.py
   ```

4. Open the app in your browser:
   ```
   http://127.0.0.1:5000/
   ```

---

## Usage

1. Access the home page (`index.html`) for an introduction.
2. Navigate to the prediction page (`home.html`).
3. Input the required fields:
   - Gender
   - Race/Ethnicity
   - Parental Level of Education
   - Lunch
   - Test Preparation Course
   - Reading Score
   - Writing Score
4. Submit the form to view the prediction results.

---

## Custom Modules

### `CustomData`
- Collects user input and converts it into a pandas DataFrame for prediction.

### `PredictPipeline`
- Loads the pre-trained model and predicts outcomes based on input data.

---

## Deployment

To deploy the application, use platforms like:
- [Heroku](https://www.heroku.com/)
- [AWS](https://aws.amazon.com/)
- [Azure](https://azure.microsoft.com/)

---

## Future Enhancements
- Add more features and validations for user input.
- Improve the user interface.
- Deploy the app for public use.
- Include model evaluation metrics and explainability features.

---

## Author
**Thirupathirao**

---

## License
This project is licensed under the MIT License. See the LICENSE file for details.

