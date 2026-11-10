# AI-Based Outfit Recommendation System

## Overview

The AI-Based Outfit Recommendation System is an intelligent fashion recommendation platform that helps users discover suitable clothing combinations based on visual similarity, style compatibility, and occasion requirements. The system leverages computer vision and deep learning techniques to analyze clothing images and generate personalized outfit suggestions.

To enhance the user experience, the system also integrates a Virtual Try-On module, allowing users to visualize recommended outfits before making fashion decisions.

---

## Objectives

- Recommend fashion outfits based on clothing image features.
- Improve outfit selection through AI-driven recommendations.
- Provide personalized suggestions for different occasions.
- Enable users to visualize outfits using virtual try-on technology.
- Create an interactive and user-friendly fashion platform.

---

## Key Features

- Clothing Image Upload
- Deep Learning-Based Feature Extraction
- Similarity-Based Outfit Recommendation
- Occasion-Based Outfit Suggestions
- Personalized Fashion Recommendations
- Virtual Try-On Integration
- Interactive Web Interface

---

## Technologies Used

### Frontend
- React.js
- HTML5
- CSS3
- JavaScript

### Backend
- FastAPI
- Python

### Machine Learning & Deep Learning
- PyTorch
- ResNet50
- Scikit-Learn

### Image Processing
- OpenCV
- Pillow (PIL)
- Rembg

### Development Tools
- Git
- GitHub
- VS Code

---

## System Workflow

1. User uploads a clothing image.
2. Image preprocessing is performed.
3. Deep learning models extract visual features.
4. Similarity analysis identifies matching outfits.
5. Recommendations are generated based on compatibility.
6. Selected outfits are displayed.
7. Virtual Try-On generates visualization results.

---

## Project Structure

```text
Fashion_Design/
│
├── backend/
│   ├── api/
│   ├── models/
│   ├── data/
│   └── main.py
│
├── frontend/
│   ├── src/
│   ├── public/
│   └── package.json
│
├── README.md
└── requirements.txt
```

---

## Installation and Setup

### 1. Clone the Repository

```bash
git clone <repository-url>
cd Fashion_Design
```

### 2. Backend Setup

Navigate to the backend directory:

```bash
cd backend
```

Install the required Python dependencies:

```bash
pip install -r requirements.txt
```

Start the FastAPI backend server:

```bash
uvicorn main:app --reload
```

The backend server will be available at:

```text
http://127.0.0.1:8000
```

FastAPI API documentation:

```text
http://127.0.0.1:8000/docs
```

### 3. Frontend Setup

Open a new terminal and navigate to the frontend directory:

```bash
cd frontend
```

Install the required Node.js dependencies:

```bash
npm install
```

Start the frontend development server:

```bash
npm run dev
```

Open the local development URL displayed in the terminal to access the application.

---

## Future Enhancements

- AI-Based Personalized Styling
- Real-Time Fashion Trend Analysis
- Mobile Application Support
- Advanced Virtual Try-On Models
- Multi-Category Outfit Generation
- User Preference Learning

---

## Authors

**Project Team**

- **P. Jahnavi** — `1602-22-737-081`
- **R. Sharanya** — `1602-22-737-115`

---

## Academic Project

This project was developed as part of a Bachelor of Technology academic project in the field of **Artificial Intelligence, Machine Learning, and Computer Vision**.

---

## License

This project is intended for educational and research purposes.
