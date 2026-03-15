# ChangeSentinel: Intelligent Satellite Monitoring for a Changing Planet

ChangeSentinel is an AI-powered environmental monitoring system designed to detect and forecast geographical changes using satellite imagery. The system
analyses multi-temporal satellite images to monitor environmental transformations such as deforestation, water body changes, soil exposure, and urban expansion.
It integrates deep learning, remote sensing, and data analytics to provide automated change detection and real-time alerts.
The goal of this project is to make advanced satellite monitoring accessible for governments, researchers, environmental agencies, and urban planners.

---

## Key Features

- Real-time satellite change detection
- AI-based land cover segmentation using U-Net
- Vegetation monitoring using NDVI
- Water body analysis using NDWI
- Soil exposure detection using BSI
- Time-series forecasting using Prophet and XGBoost
- Real-time alert system (Email / SMS)
- Interactive dashboard for visualization

---

## Technologies Used

### Backend
- Python
- TensorFlow / PyTorch
- Google Earth Engine
- MongoDB / Firebase

### Machine Learning
- U-Net Deep Learning Architecture
- Prophet Time-Series Forecasting
- XGBoost Prediction Model

### Frontend
- Streamlit / Flask Dashboard

### Satellite Data
- Sentinel-2 Imagery
- LISS-4 Satellite Data

---

## System Architecture

The system consists of multiple components:

1. Satellite Image Acquisition using Google Earth Engine
2. Image Preprocessing (Cloud Masking & Atmospheric Correction)
3. Feature Extraction (NDVI, NDWI, BSI)
4. Land Classification using U-Net Deep Learning Model
5. Change Detection using Multi-temporal Analysis
6. Forecasting Future Changes using Time-Series Models
7. Dashboard Visualization and Alert System

---

## Methodology

1. User selects an Area of Interest (AOI).
2. The system retrieves satellite imagery for different time periods.
3. Preprocessing techniques remove clouds and atmospheric distortions.
4. Spectral indices such as NDVI, NDWI, and BSI are calculated.
5. The U-Net model performs pixel-level land classification.
6. Change detection identifies environmental transformations.
7. Forecasting models predict future environmental trends.
8. Results are displayed through an interactive dashboard.

---

## Results

The system achieved:

- 91.3% accuracy in change detection
- 99.2% system uptime
- 12-second alert delivery time

These results demonstrate the effectiveness of AI-driven environmental monitoring.

---

## Applications

- Deforestation monitoring
- Water resource management
- Urban expansion monitoring
- Disaster management
- Climate change analysis
- Agricultural land monitoring

---

## Future Improvements

- Integration with drone imagery
- SAR satellite data integration
- Mobile application for real-time monitoring
- Advanced AI predictive models
- Government environmental monitoring integration

---

## Authors
- S.L Shree Hari
- R. Shyam Sundar
- K. Thamizharasan
- Project Team Members

Guide: Mr. M Balaji
Department of Artificial Intelligence and Data Science
Vel Tech High Tech Dr.Rangarajan Dr.Sakunthala Engineering College.
