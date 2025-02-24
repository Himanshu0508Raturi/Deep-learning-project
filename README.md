🌿 Plant Disease Detection System
An AI-powered web application that detects plant diseases from images using a deep learning model. The system helps farmers and agricultural experts diagnose plant diseases early, ensuring timely treatment and improved crop yield.

🚀 Features
🌱 Upload plant images to detect diseases.
🤖 Deep learning model trained on plant disease datasets.
📊 Provides disease details and recommended treatments.
💻 User-friendly web interface built with Streamlit.
☁️ Deployed on AWS EC2 for global accessibility.
🔒 Secure and scalable deployment.
⚙️ Tech Stack
Frontend: Streamlit
Backend: Python (TensorFlow/Keras)
ML Model: Pre-trained .keras model (stored using Git LFS)
Deployment: AWS EC2
<br>
Structure:-<br>
plant-disease-detection/
│
├── model/
│   └── plant_disease_model.keras   # Trained ML model
│
├── app.py                          # Streamlit frontend application
├── requirements.txt                 # Python dependencies
├── Dockerfile                       # For containerized deployment (Optional)
├── README.md                        # Project documentation
└── utils/
    └── preprocessing.py             # Image preprocessing functions