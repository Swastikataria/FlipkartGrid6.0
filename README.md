# ***Flipkart GRID 6.0 Robotics Challenge***

**Welcome to our innovative solution for Smart Vision Technology Quality Control!**  
This project, developed as part of the Flipkart GRID 6.0 Robotics Challenge, combines hardware, machine learning, and intelligent design to automate and optimize inventory and quality management. Deployed on *Vercel* with ML models running on *Streamlit*, this solution is aimed at achieving seamless, accurate, and real-time results.

![Screenshot 2024-12-16 093232](https://github.com/user-attachments/assets/8e0dfa16-cc80-4c20-9979-2aefb0645540)


# Key Features

### 1. Item Counting
- **Model:** Trained using YOLOv8 for object detection.
- **Dataset:** Labeled via Roboflow.
- **Functionality:** Accurately determines the number of products in an image or live video feed, handling **overlapping cases** efficiently.
- **Database:** Managed with **CSV files** for ease of integration and updates.
- **Use Case:** Automates inventory counting and reduces manual intervention.

### 2. Freshness Detection
- **Model:** Built with TensorFlow and MobileNetV2 for image classification.
- **Purpose:** Determines the freshness of perishable products accurately.
- **Database:** Uses **MongoDB** to store and update freshness data.
- **Use Case:** Reduces food wastage and improves store shelf management.

### 3. Brand Label Detection
- **Model:** Optical Character Recognition (OCR) model for label detection and categorization.
- **Functionality:** Extracts brand names from product packaging and updates a regularly maintained **CSV table**.
- **Use Case:** Enhances inventory organization for quick and reliable categorization.

### 4. Expiry Date Detection
- **Model:** OCR-based system for detecting expiry-related information like `Expiry Date`, `Best Before`, or direct date values.
- **Functionality:** Extracts expiry dates from packaging and updates CSV records automatically.
- **Use Case:** Timely tracking of product shelf life for inventory management.


## Hardware and UI Design
- **Hardware:** A custom-designed image acquisition system ensures precise data collection for all models.
- **Frontend:** UI built with **HTML** and **CSS** for a clean and intuitive experience.
- **Backend Deployment:** Vercel handles the deployment of the main site, while ML models run individually on Streamlit for scalability and modularity.


## Smart Chatbot for Easy Navigation
To enhance user experience, we've integrated a chatbot called **GridBot** built using *Dialogflow*. The chatbot:
- Assists in navigating the website.
- Provides guidance on using different features.
- Ensures a seamless and interactive user experience.

![Screenshot 2024-12-16 093303](https://github.com/user-attachments/assets/65ff790c-141f-4766-b2c8-bec1349c83e0)


## How It Works
1. **Image Acquisition:** Real-time feed or images are captured via the hardware system.
2. **ML Processing:** Models process images to detect:
   - Product counts (YOLOv8).
   - Freshness levels (TensorFlow, MobileNetV2).
   - Expiry details and brand labels (OCR-based models).
3. **Data Management:** Results are stored and updated in **MongoDB** or CSV files.
4. **UI Interaction:** Users can view and manage results through an intuitive interface.
5. **Chatbot Support:** Dialogflow chatbot provides real-time assistance.


## Deployment
- **Main Site:** Deployed on [Vercel] https://flipkart-grid6-0.vercel.app/.
- **ML Models:** Hosted individually on *Streamlit* for flexible and independent access.


This project offers a **reliable, efficient, and scalable** solution for quality control and inventory management using state-of-the-art **Machine Learning** and hardware integration. By automating tedious tasks like product counting, freshness detection, and expiry tracking, we aim to:
- Reduce manual labor.
- Prevent food wastage.
- Improve store efficiency.


**Team:** `ishitaporwal15`  
**Challenge:** Flipkart GRID 6.0 Robotics Challenge  
**Technologies Used:** YOLOv8, TensorFlow, MobileNetV2, OCR, MongoDB, HTML/CSS, Streamlit, Vercel, Dialogflow.

