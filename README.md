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
plant-disease-detection/<br>
│
├── model/<br>
│   └── plant_disease_model.keras   # Trained ML model<br>
│<br>
├── app.py                          # Streamlit frontend application<br>
├── requirements.txt                 # Python dependencies<br>
├── README.md                        # Project documentation<br>
└── utils/<br>
    └── preprocessing.py             # Image preprocessing functions<br>