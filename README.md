# 🚶‍♂️ StepLock - Gait Authentication System

AI-powered biometric authentication using human walking patterns.

## Features
- **Video-based gait analysis** using MediaPipe pose detection
- **Machine Learning authentication** with Random Forest classifier  
- **Modern React frontend** with premium dark theme
- **Flask REST API** backend with feature extraction
- **Real-time confidence scoring** and user feedback

## Tech Stack
- **Frontend**: React.js, Modern CSS animations
- **Backend**: Python Flask, MediaPipe, scikit-learn
- **ML**: Pose estimation, feature extraction, Random Forest
- **Security**: CORS, data encryption (planned)

## Setup & Installation

### Backend
cd backend
pip install flask flask-cors opencv-python mediapipe scikit-learn numpy
python app.py

### Frontend
cd frontend
npm install
npm start


## Usage
1. **Register**: Upload walking video with user ID
2. **Authenticate**: Upload video to verify identity
3. **View Results**: See confidence score and matched user

## Project Structure
steplock-gait-auth/
├── backend/
│ ├── app.py
│ ├── ml_auth.py
│ ├── calculate_gait_features.py
│ └── extract_gait.py
├── frontend/
│ ├── src/App.js
│ └── package.json
└── README.md


Built with ❤️ using AI and computer vision

