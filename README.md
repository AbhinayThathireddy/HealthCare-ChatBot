## Overview
The **Healthcare Chatbot System** is an AI-powered solution designed to enhance healthcare accessibility by providing real-time assistance in diagnosing health-related issues and offering location-based recommendations for nearby healthcare facilities. Developed using Python and deep learning, the chatbot ensures quick, accurate, and user-friendly interaction for improved health management.

## Features
- **Interactive Chatbot**: Natural language processing for real-time symptom analysis and response generation.
- **Disease Prediction**: Utilizes a CNN-based algorithm for accurate disease prediction based on symptoms.
- **Location-Based Services**: Integration with Google Places API to locate nearby doctors, clinics, and hospitals.
- **User and Admin Modules**:
  - **User Module**: Register, log in, manage profiles, and chat with the bot.
  - **Admin Module**: Manage questions, retrain the model, and oversee user details.
- **24/7 Accessibility**: Provides healthcare support anytime, anywhere.

## Technologies Used
- **Programming Language**: Python
- **Libraries**: TensorFlow, Keras, OpenCV, NLTK, Flask
- **APIs**: Google Places API
- **Frameworks**: Flask for the web interface

## System Architecture
![image](https://github.com/user-attachments/assets/1910fbc6-e953-48a9-8120-48582e035d25)


1. **User Interaction**: Users interact via a chatbot interface.
2. **Symptom Analysis**: Preprocessed inputs are analyzed using NLP and CNN.
3. **Disease Prediction**: Outputs tailored responses or healthcare advice.
4. **Location Integration**: Fetches nearby facilities using Google Places API.

## Installation and Setup
1. Clone the repository:
   ```bash
   git clone https://github.com/username/healthcare-chatbot.git
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Obtain a Google Places API key and update the configuration file.
4. Run the application:
   ```bash
   python app.py
   ```

## Screenshots
### User Interface
![Screenshot 2025-01-21 150730](https://github.com/user-attachments/assets/d79f04e3-0c66-4d15-9221-3c8e097cd106)

### Login page 
![Screenshot 2025-01-21 150746](https://github.com/user-attachments/assets/ef8c0b9f-fdb6-4142-8722-97c257d67d8c)

### ChatBot
![Screenshot 2025-01-21 150828](https://github.com/user-attachments/assets/6ede0cd8-4b57-4fd0-abbe-58ca98a468b2)

## Results
- **Efficiency**: The system provides accurate responses with a user-friendly interface.
- **Impact**: Enhanced accessibility for rural and underserved areas.
- **Accuracy**: High accuracy in disease prediction using CNN algorithms.

## Future Enhancements
- **Multilingual Support**: Expand chatbot capabilities to support multiple languages.
- **Audio and Face Recognition**: Enable voice commands and user authentication through facial recognition.
- **Dynamic Data Integration**: Use real-time health datasets for improved accuracy.
- **Emergency Features**: Direct communication with healthcare providers during emergencies.

