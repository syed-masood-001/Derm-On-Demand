# Derm on Demand

## Overview

Derm On Demand is a web application that leverages deep learning to provide users with information about potential skin and hair conditions, as well as recommendations for dermatologists in their area.

## Key Features:

* **Skin and Hair Disease Identification:** Users can upload images of their skin or hair to receive a prediction of the potential condition.
* **Dermatologist Recommendation:** Based on the identified condition and the user's location, the app recommends highly-rated dermatologists nearby.
* **User-Friendly Interface:** The web app provides a clear and intuitive interface for users to navigate and interact with its features.
  
## Installation and Setup:

1. Clone the repository from GitHub.
2. Install the required Python libraries: pip install -r requirements.txt
3. Ensure you have the following deep learning models and files in the specified directories:
   * **Hair model:** hair_model.h5
   * **Hair labels:** hair_disease_label.txt
   * **Skin model:** skin_model.h5
   * **Skin labels:** skin_label.txt
   * **Dermatologist data:** doctordata.csv
4. **Run the Flask server:** python server.py
   
## Usage:
1. Access the web app at http://127.0.0.1:5000/ (or the specified port).
2. Navigate to the "Skin Disease" or "Hair Disease" section.
3. Upload an image of the affected area.
4. The app will display the predicted condition and confidence score.
5. Proceed to the "Find a Dermatologist" section to get recommendations.
## Project Structure:

* **Server Files:**
   * **server.py:** Main Flask application code
   * **model.py:** Functions for image processing and prediction
   * **findDoc.py:** Functions for dermatologist recommendation
   * Directories for models and labels
* **Web App Files:**
   * HTML templates for the web interface
   * CSS files for styling
   * JavaScript files for interactivity
## Contributing:

We welcome contributions to this project! Please review the contribution guidelines before submitting pull requests.

## Disclaimer:

This application is not intended to replace professional medical advice or diagnosis. Always consult a qualified dermatologist for accurate diagnosis and treatment of skin and hair conditions.
