# Taillor AI: Fashion E-Commerce Store with Personalized Recommendation System

## Features

- **Full-Stack E-commerce Store**: Built with ReactJS for the frontend, providing a responsive and modern shopping experience.
- **Hyper-Personalized Recommendations**: Recommender system combines Collaborative Filtering, KNN, and transformer models for highly accurate product suggestions tailored to individual users.
- **Fashion Image Captioning**: The BLIP model, fine-tuned on the H&M 12K dataset, automatically generates descriptive captions for product images.
- **User Authentication**: Users can create accounts, log in, and view personalized product recommendations.
- **Cart and Checkout Functionality**: Users can add items to their cart and proceed through the checkout process.
- **Admin Dashboard**: Provides an interface to manage products, track orders, and analyze user behavior.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/en/) and npm
- [Python 3.8+](https://www.python.org/downloads/)
- MongoDB (or a MongoDB Atlas account for a cloud-based solution)

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/AtharvaMaskar26/Tailor-AI.git
   ```

2. **Install Frontend Dependencies**:
   ```bash
   cd client
   npm install
   ```

3. **Install Backend Dependencies**:
   ```bash
   cd ../backend
   pip install -r requirements.txt
   ```

### Running the Application

1. **Start the Backend**:
   ```bash
   cd backend
   uvicorn server:app --reload
   ```

2. **Start the Frontend**:
   ```bash
   cd ../frontend
   npm run dev
   ```

### Fine-Tuning the BLIP Model

The BLIP model has been fine-tuned on the H&M 12K dataset to generate accurate captions for fashion images.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you'd like to improve this project.
=======
