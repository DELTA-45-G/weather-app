# 🌤️ Weather App

A modern, responsive weather application built with **React** and **Vite**. This app fetches real-time weather data, displays dynamic weather conditions, and provides a clean user interface.

## 🚀 Features
- **Real-time Weather Data:** Fetches current temperature, humidity, and wind speed using the OpenWeatherMap API.
- **Dynamic Date & Time:** formatted using `dayjs`.
- **Responsive Design:** Looks good on desktop and mobile.
- **Visuals:** Dynamic weather icons using `@tabler/icons-react` and custom background images.
- **City Search:** Easily search for weather conditions in any city globally.

## 🛠️ Tech Stack
- **Frontend Framework:** React.js (Vite)
- **Styling:** CSS3
- **HTTP Client:** Axios
- **Icons:** Tabler Icons React
- **Utilities:** Day.js (for date formatting)

## 📂 Project Structure
src/
├── assets/            # Static assets (images, icons, etc.)
├── components/        # Reusable React components
│   └── WeatherApp.jsx # Main weather UI component
├── apiKey.js          # API key configuration
├── App.jsx            # Root application component
└── main.jsx           # Application entry point

## ⚙️ Installation & Setup
Follow these steps to run the project locally:
### 1. Clone the repository
```bash
git clone [https://github.com/DELTA-45-G/weather-app.git](https://github.com/DELTA-45-G/weather-app.git)
cd weather-app
```
2. Install Dependencies
This project uses Node.js. Install the required packages:
```bash
npm install
```
3. Configure API Key
Create a file named apiKey.js in the src folder (if it doesn't exist).
Add your OpenWeatherMap API key:
// src/apiKey.js
export const API_KEY = "YOUR_OPENWEATHERMAP_API_KEY";

4. Run the Application
Start the development server:
```bash
npm run dev
```
5. Open the link provided in the terminal (usually http://localhost:5173) to view the app.
6. App interface looks like
<img width="1282" height="725" alt="image" src="https://github.com/user-attachments/assets/a5fc7a29-3c19-4699-b79f-3b3aab50cb3e" />





🤝 Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

👤 Author
DELTA-45-G
