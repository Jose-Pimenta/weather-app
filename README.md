# Weather App

Weather App is a responsive web application built with React and Vite that provides current weather information and a 5-day forecast for any city, powered by the OpenWeatherMap API.  
[![Vercel](https://img.shields.io/badge/Deploy-on_Vercel-000?style=flat&logo=vercel&logoColor=white)](https://weather-app.tiagopimenta.pt)

## Features

- Search for any city to get current weather conditions
- Display temperature, humidity, wind speed, and weather description
- Responsive design for desktop and mobile

## Technologies

- React (v19)
- Vite for development and build tooling
- React Router DOM for routing (if applicable)
- Axios for HTTP requests
- CSS Modules or plain CSS for styling

## Project Structure

```
weather-app/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   ├── SearchBar.jsx
│   │   ├── WeatherCard.jsx
│   │   ├── Forecast.jsx
│   │   └── (component styles)
│   ├── api/
│   │   └── weather.js
│   ├── pages/
│   │   └── Home.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── index.css
├── .env.example
├── .gitignore
├── package.json
├── package-lock.json
├── vite.config.js
└── README.md
```

## Getting Started

### Prerequisites

- Node.js (>=14.x)
- npm

### Installation

```bash
git clone https://github.com/Jose-Pimenta/weather-app.git
cd weather-app
npm install
```

### Environment Variables

Copy the example and add your OpenWeatherMap API key:

```bash
cp .env.example .env
# In .env:
VITE_OPENWEATHER_API_KEY=your_api_key_here
```

### Development

Start the development server:

```bash
npm run dev
```

Open your browser at `http://localhost:5173`.

### Build

Create a production build and preview:

```bash
npm run build
npm run preview
```

## API

This project uses the [OpenWeatherMap API](https://openweathermap.org/api) to fetch weather data. You need an API key (free registration).

## Customization

- Change the number of forecast days by updating the API call in `api/weather.js`.
- Customize styles in `src/index.css` or component CSS files.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request.

## License

This project is licensed under the MIT License.

## Author

Jose Pimenta
