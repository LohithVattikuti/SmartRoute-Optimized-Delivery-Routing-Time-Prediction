# SmartRoute - Optimized Delivery Routing & Time Prediction

SmartRoute is a comprehensive logistics optimization system designed to streamline delivery operations. It provides tools for optimizing vehicle routes, predicting delivery times, and offering real-time operational insights. The system leverages OpenStreetMap data, machine learning models, and a dynamic dashboard for efficient fleet management.

## Key Features

### 1. Optimized Route Planning
- Utilizes shortest path algorithms and Traveling Salesman Problem (TSP) solutions to determine the most efficient delivery routes.
- Integrates with OpenStreetMap for accurate road network data.

### 2. Predictive Delivery Time Estimation
- Employs machine learning models to predict delivery times based on factors such as distance, traffic, and weather conditions.
- Continuously improves predictions with real-time data.

### 3. Dynamic Vehicle Assignment
- Assigns orders to vehicles dynamically based on capacity, priority, and weight.
- Ensures optimal utilization of fleet resources.

### 4. Interactive Dashboard
- Displays real-time route visualizations and delivery metrics.
- Provides operational insights to help managers make informed decisions.

### 5. Scalable and Containerized
- Fully Dockerized deployment with a FastAPI backend and React frontend.
- Scalable architecture to handle growing business needs.

## Installation & Setup

### Prerequisites
- Docker and Docker Compose installed on your system.
- Node.js and npm installed for frontend development.

### Steps to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/LohithVattikuti/SmartRoute-Optimized-Delivery-Routing-Time-Prediction.git
   cd SmartRoute-Optimized-Delivery-Routing-and-Time-Prediction
   ```

2. Start the backend and frontend services using Docker Compose:
   ```bash
   docker-compose up --build
   ```

3. Access the application:
   - Backend API: `http://localhost:8000`
   - Frontend Dashboard: `http://localhost:3000`

## Tech Stack

### Backend
- **Framework**: FastAPI (Python)
- **Libraries**: OpenStreetMap (OSMnx), NetworkX
- **Database**: PostgreSQL

### Frontend
- **Framework**: React (JavaScript)
- **Libraries**: Google Maps API, Tailwind CSS

### Machine Learning
- **Libraries**: Scikit-learn, RandomForest, Pandas, NumPy
- **Models**: Delivery time prediction using regression algorithms

### Deployment
- **Tools**: Docker, Docker Compose

## How It Works

1. **Route Optimization**:
   - The system calculates the shortest and most efficient delivery routes using advanced algorithms.
   - Routes are visualized on an interactive map.

2. **Delivery Time Prediction**:
   - Machine learning models predict delivery times based on real-world factors like traffic and weather.
   - Predictions are displayed on the dashboard for better planning.

3. **Dynamic Dashboard**:
   - A user-friendly dashboard provides real-time insights into delivery operations.
   - Managers can monitor vehicle locations, delivery statuses, and overall performance.

## Future Enhancements

- Integration with third-party logistics APIs for real-time traffic and weather updates.
- Support for multi-city delivery operations.
- Enhanced machine learning models for better predictions.
- Mobile app for drivers to receive real-time updates and instructions.

## License

This project is licensed under the MIT License. Feel free to use and modify it as needed.

