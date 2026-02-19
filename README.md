# Weather App

A modern, responsive weather application built with React, Vite, and Material UI.

## Features
- **Real-time Weather Data**: Fetches current weather information using the OpenWeatherMap API.
- **Dynamic UI**: Display changes based on weather conditions (Hot, Cold, Rainy).
- **Responsive Design**: Optimized for both desktop and mobile devices.
- **Glassmorphism Affect**: Modern, sleek user interface.

## Tech Stack
- React
- Vite
- Material UI (@mui/material, @mui/icons-material)
- CSS3 (Flexbox/Grid, gradients, glassmorphism)

## improved Search Box
- Search for any city worldwide.
- Error handling for invalid city names.

## Setup Instructions

1.  **Clone the repository:**
    ```bash
    git clone <repository-url>
    cd mini-project
    ```

2.  **Install dependencies:**
    ```bash
    npm install
    ```

3.  **Environment Variables:**
    Create a `.env` file in the root directory and add your OpenWeatherMap API key:
    ```env
    VITE_API_URL=https://api.openweathermap.org/data/2.5/weather
    VITE_API_KEY=your_api_key_here
    ```
    *(Refer to `.env.example`)*

4.  **Run the application:**
    ```bash
    npm run dev
    ```

The application will start at `http://localhost:5173`.
