#  Flood Rescue AI System

An intelligent **Flood Rescue AI System** that utilizes **Artificial Intelligence (AI), Deep Learning, and Computer Vision** to assist in flood disaster management. The system analyzes flood-related images to detect flood severity, identify stranded individuals, and provide decision support for emergency rescue operations. By integrating advanced AI models with an interactive web interface, the project aims to improve response time, enhance situational awareness, and support efficient disaster management.

---

#  Overview

Floods are one of the most destructive natural disasters, affecting millions of people worldwide every year. Rapid identification of flood severity and timely rescue operations are critical for minimizing loss of life and property. However, traditional monitoring methods often rely on manual observations, making the response process slower and less efficient.

The **Flood Rescue AI System** addresses these challenges by leveraging machine learning and deep learning techniques to automatically analyze flood-related images. The system can classify flood conditions, detect rescue resources and affected individuals, and provide visual insights through an easy-to-use dashboard. This project demonstrates how Artificial Intelligence can contribute to smarter and faster disaster response systems.

---

#  Key Features

*  AI-powered flood image classification.
*  Identification of stranded people in flood-affected areas.
*  Flood severity analysis and visualization.
*  Upload and analyze flood images through a user-friendly interface.
*  Fast and accurate predictions using trained deep learning models.
*  Interactive web application for displaying prediction results.
*  Organized output for better decision-making during rescue operations.

---

#  Technologies Used

### Programming Language

* Python

### Artificial Intelligence & Deep Learning

* TensorFlow
* Keras
* YOLOv8
* RT-DETR

### Data Processing

* NumPy
* Pandas

### Data Visualization

* Matplotlib

### Computer Vision

* OpenCV

### Web Development

* Flask
* HTML
* CSS
* JavaScript

### Development Environment

* Jupyter Notebook

---

#  Project Structure

```text
Flood-Rescue-System/
│
├── FloodRescueSystem_final.ipynb      # Main project notebook
├── app.py                             # Flask application
├── requirements.txt                   # Required Python packages
├── README.md                          # Project documentation
│
├── dataset/                           # Dataset used for training
├── models/                            # Trained AI models
├── static/                            # CSS, JavaScript, Images
├── templates/                         # HTML templates
├── uploads/                           # Uploaded images
├── outputs/                           # Prediction results
└── screenshots/                       # Project screenshots
```

---

#  Installation

Follow these steps to set up and run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/Flood-Rescue-System.git
```

### 2. Navigate to the Project Folder

```bash
cd Flood-Rescue-System
```

### 3. Install Required Dependencies

```bash
pip install -r requirements.txt
```

### 4. Launch the Application

```bash
python app.py
```

Or open the Jupyter Notebook and execute all cells to test the models.

---

#  Usage

1. Start the application.
2. Open the web interface in your browser.
3. Upload a flood-related image.
4. The AI model processes the image.
5. The system predicts flood severity.
6. Rescue boats and affected people are detected.
7. Results are displayed with visual outputs and analysis.

---

#  System Workflow

1. Collect flood image data.
2. Preprocess and clean the dataset.
3. Train deep learning models.
4. Perform image classification.
5. Detect rescue objects using object detection models.
6. Generate prediction results.
7. Display results through the web dashboard.

---

#  Project Objectives

* Develop an AI-powered flood analysis system.
* Improve the speed and accuracy of flood assessment.
* Assist emergency rescue teams with intelligent decision support.
* Detect stranded individuals and rescue boats automatically.
* Demonstrate the practical application of Artificial Intelligence in disaster management.

---

#  Applications

* Disaster Management Authorities
* Emergency Rescue Teams
* Government Organizations
* Smart City Monitoring Systems
* Environmental Research
* Academic Research Projects

---

#  Future Scope

* Integration with live CCTV surveillance.
* Drone-based flood monitoring.
* GPS-enabled rescue navigation.
* IoT sensor integration for real-time flood detection.
* Mobile application for field rescue teams.
* Cloud deployment for large-scale disaster monitoring.
* Real-time weather and satellite data integration.

---

##  Project Screenshots

### 1. Dashboard Overview
Displays the main dashboard where users can upload flood images, monitor processing progress, and view overall statistics such as total processed images, flood detections, priority levels, and people detected.



---

### 2. Case Cards
Shows AI-generated case cards for each uploaded image, including flood severity, detected people, rescue boats, flood percentage, risk level, and available actions such as Approve, Dispatch, Edit, and Reject.



---

### 3. Dispatch Order
Displays the prioritized rescue dispatch list generated by the AI system, helping authorities allocate rescue resources based on flood severity, risk score, and the number of affected people.




---

#  Team Members

* Y Geyasri
* Varshita Chauhan
* Chinmayee V
* Vrinda M

---

#  Acknowledgements

We express our sincere gratitude to our project guide, faculty members, and institution for their continuous guidance, encouragement, and support throughout the development of this project. Their valuable suggestions and feedback played a significant role in the successful completion of this work.

---

#  License

This project was developed as part of our **Minor Project** for academic purposes. It is intended for educational, learning, and research use.
