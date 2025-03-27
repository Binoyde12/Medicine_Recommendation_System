# Medicine Recommendation System

## Overview
This project is a **Medicine Recommendation System** that uses machine learning models to suggest medicines based on symptoms provided by the user. It integrates a web interface to receive user input and return recommendations.

## Tech Stack
- **Backend:** Python, Flask
- **Frontend:** HTML, CSS
- **Modeling:** Jupyter Notebook
- **Deployment:** Flask-based server

## Features
- User symptom input and recommendation
- Pre-trained machine learning model for prediction
- Responsive web interface for user interaction

## Installation
```bash
# Clone the repository
git clone https://github.com/Binoyde12/Medicine_Recommendation_System.git

# Navigate to the project directory
cd Medicine_Recommendation_System

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate  # On Linux/Mac
venv\Scripts\activate    # On Windows

# Install dependencies
pip install -r requirements.txt

# Run the application
python app.py
```

## Project Structure
```
Medicine_Recommendation_System/
├── .venv/               # Virtual environment
├── Datasets/            # Dataset for model training
├── models/              # Pre-trained model files
├── templates/           # HTML templates for frontend
├── app.py               # Flask application
└── README.md
```

## Usage
1. Open the application in your browser at `http://localhost:5000`
2. Enter symptoms in the input field.
3. Receive medicine recommendations.

## Deployment
- Hosted using Flask locally.
- To deploy on cloud platforms, configure server and database.

## Contributing
Contributions are welcome! Submit a pull request or create an issue.

## License
This project is open-source and available under the [MIT License](LICENSE).


