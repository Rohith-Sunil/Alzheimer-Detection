# CogniCare - Alzheimer's Detection Platform

## Overview
CogniCare is a web-based application that helps in the early detection of Alzheimer's disease by analyzing speech patterns. It utilizes machine learning models to assess speech input and provide diagnostic predictions.

## Features
- **Audio Recording & Transcription**: Users can record their speech, which is then transcribed using AssemblyAI.
- **Text Preprocessing**: The transcribed text undergoes natural language processing for feature extraction.
- **Machine Learning Prediction**: The processed text is analyzed by ML models to predict Alzheimer's likelihood.
- **Frontend Dashboard**: An interactive UI for users to record, view results, and navigate through information about Alzheimer's.

## Tech Stack
### Backend:
- Flask (API and ML model hosting)
- Scikit-learn (Machine Learning)
- SpaCy (Natural Language Processing)
- Pandas, NumPy
- Pickle & Dill (Model persistence)

### Frontend:
- React.js (User Interface)
- React Router (Navigation)
- Axios (API communication)
- Mic-recorder-to-mp3 (Audio Recording)
- AssemblyAI API (Speech-to-Text Processing)

## Installation & Setup
### Backend Setup
1. Clone the repository:
   ```sh
   git clone https://github.com/Rohith-Sunil/cognicare.git
   cd cognicare/backend
   ```
2. Create a virtual environment and install dependencies:
   ```sh
   python -m venv venv
   source venv/bin/activate  # On Windows use 'venv\\Scripts\\activate'
   pip install -r requirements.txt
   ```
3. Run the Flask app:
   ```sh
   python app.py
   ```

### Frontend Setup
1. Navigate to the frontend directory:
   ```sh
   cd ../frontend
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Start the development server:
   ```sh
   npm start
   ```

## API Endpoints
| Method | Endpoint      | Description                        |
|--------|-------------|--------------------------------|
| GET    | `/`         | Check API status               |
| POST   | `/predict`  | Predict Alzheimer's likelihood |

## Usage
1. Open the web application.
2. Record and submit speech input.
3. View the Alzheimer's prediction results.
4. Refer to the dashboard for insights and community support.
