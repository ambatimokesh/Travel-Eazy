Travel Eazy – AI-Powered Personalized Travel Recommendation System

Smart, Inclusive, and Personalized Travel Planning using Python and Machine Learning

About the Project
Travel Eazy is a Python-based web application designed to revolutionize the way people plan travel in India. Integrating machine learning with a clean, responsive web interface, this project provides personalized travel recommendations based on user preferences, health conditions, and interests. Built with inclusivity in mind, it caters to a wide variety of users—from elderly travelers to adventure seekers—by tailoring suggestions that match unique needs and accessibility requirements.

The system features two core modules:

Admin Module: Manages data on tourist destinations, local cuisine, activities, and ensures content remains updated and relevant.

User Module: Allows users to input preferences, receive AI-generated suggestions, explore travel options, and seamlessly book trips—all within the platform.

Travel Eazy supports smarter tourism by considering health constraints (like mobility issues or allergies), lifestyle preferences, and promoting lesser-known destinations to support sustainable local tourism.

Features
✅ Personalized travel recommendations using machine learning algorithms

✅ User profile inputs: age, health conditions, interests, dietary preferences

✅ Admin panel to manage destinations, cuisines, and activities

✅ Interactive web interface using HTML, CSS, Flask, Bootstrap

✅ Intelligent backend with Random Forest, Gradient Boosting, KNN (Soft Voting Classifier)

✅ Destination filtering and booking cart functionality

✅ Secure login and authentication

✅ Scalable for future integration (real-time weather, dynamic pricing, multi-language support)

Layer	Technologies Used
Frontend	HTML5, CSS3, Bootstrap
Backend	Python 3.8+, Flask
Database	MySQL
ML Libraries	scikit-learn, Pandas, NumPy, Joblib
Other Tools	VS Code, XAMPP, Git

The application uses a hybrid ensemble method for destination recommendations. It combines:

Random Forest

Gradient Boosting

K-Nearest Neighbors (KNN)

These models are integrated using a Soft Voting Classifier to improve accuracy and handle diverse user inputs. The ML pipeline also includes data preprocessing (cleaning, normalization, encoding), feature selection, and model serialization using

Project Structure

Travel-Eazy/
├── static/
│   └── styles.css
├── templates/
│   ├── index.html
│   ├── login.html
│   ├── dashboard.html
│   └── recommendations.html
├── admin_module.py
├── user_module.py
├── app.py
├── model/
│   └── travel_model.pkl
├── data/
│   ├── destinations.csv
│   └── users.csv
├── README.md
└── requirements.txt

Testing
Various testing methods were used to ensure performance and reliability:

✅ Unit Testing – For individual modules

✅ Integration Testing – Between ML and web interface

✅ Functional Testing – On user workflows

✅ Usability Testing – With real users for feedback

✅ Performance Testing – Real-time response tracking under multiple inputs

Future Enhancements
🌐 Real-time weather and event API integration

🧾 Budget-aware and cost-based filtering

📱 Mobile app version for Android/iOS

🌎 Expansion to international destinations

🔐 Enhanced data privacy and encryption

📊 User behavior-based feedback loop to improve recommendations

Team Members
A.Mokesh Reddy
G. Uma Mahesh 
C. Mukunda
J. Narendra
M. Madhu Harsha 

Guided By:
Mrs. N. Nalini, Assistant Professor, Department of CSE
Mohan Babu University, Tirupati

License
This project is for educational purposes as part of BCA final year academic submission. Licensing terms will depend on institutional or open-source approval.
