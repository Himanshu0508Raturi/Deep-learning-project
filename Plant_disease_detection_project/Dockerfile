# Use an official Python base image
FROM python:3.9

# Copy all project files into the container
COPY . /app

# Set the working directory inside the container
WORKDIR /app

# Install dependencies
RUN pip install -r requirements.txt

# Expose the port that Streamlit uses
EXPOSE 8501

# Run the Streamlit app
CMD ["streamlit", "run", "plant_disease_detection_app.py", "--server.port=8501", "--server.address=0.0.0.0"]
