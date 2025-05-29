# Weather App - React.js Project

## Project Details

**Company:** Codtech IT Solutions  
**Name:** Addanki Adarsh  
**Intern ID:** CT06DL422  
**Domain:** React.js Web Development  
**Duration:** 6 weeks  
**Mentor:** Neela Santhosh Kumar  

## Project Description

This Weather App is a responsive web application built using React.js that provides real-time weather information for locations worldwide. The application offers a clean, user-friendly interface that displays current weather conditions, temperature, humidity, wind speed, and a 5-day forecast. Users can search for weather information by city name and toggle between Celsius and Fahrenheit units.

The project was developed as part of my internship at Codtech IT Solutions to demonstrate proficiency in React.js, API integration, and modern frontend development practices. The application showcases how to build interactive web applications with dynamic data fetching and state management.

![Screenshot 2025-05-29 152938](https://github.com/user-attachments/assets/862598e4-4ddb-4533-a54e-b3e7e32feddb)


### Key Features:
- Real-time weather data display
- Search functionality for cities worldwide
- Temperature unit conversion (Celsius/Fahrenheit)
- 5-day weather forecast with visual icons
- Responsive design that works on all devices
- Animated weather representations
- Error handling for invalid city searches

## Tools and Technologies Used

### Frontend Development
1. **React.js** - The core JavaScript library used for building the user interface with reusable components.
2. **React Hooks** - Utilized useState, useEffect, and useContext for state management and side effects.
3. **React Router** - Implemented for potential multi-page navigation (though currently a single-page application).
4. **CSS3** - For styling components with modern CSS features including Flexbox and Grid.
5. **Styled Components** - Used for component-level styling and theming capabilities.
6. **Axios** - Promise-based HTTP client for making API requests to weather data services.

### APIs and Data Services
1. **OpenWeatherMap API** - Primary API used to fetch current weather data and forecasts.
2. **Geolocation API** - Browser API used to detect user's location for default weather display.
3. **Weather Icon API** - For displaying appropriate weather condition icons.

### Development Tools
1. **Node.js & npm** - JavaScript runtime and package manager for project dependencies.
2. **Git & GitHub** - Version control system and code repository hosting.
3. **ESLint** - JavaScript linter for maintaining code quality and consistency.
4. **Prettier** - Code formatter for consistent code styling across the project.
5. **Chrome DevTools** - For debugging and performance optimization.
6. **Postman** - Used for API testing during development.

### Build and Deployment
1. **Webpack** - Module bundler configured through Create React App for production builds.
2. **Babel** - JavaScript compiler for converting modern JS to browser-compatible code.
3. **Netlify** - Cloud platform used for continuous deployment and hosting.

## Project Architecture

The application follows a component-based architecture with these main components:

1. **App Component** - The root component that manages global state and API calls.
2. **Header Component** - Contains the application title and theme toggle.
3. **Search Component** - Handles city search input and submission.
4. **WeatherDisplay Component** - Main container for current weather information.
5. **Error Component** - Displays error messages for invalid searches or API issues.

The state management follows React's built-in state hooks pattern, with context API used for sharing global states like temperature units across components. All API calls are centralized in service modules for better separation of concerns.

## Learning Outcomes

Through developing this Weather App, I gained hands-on experience with:

1. Building complex React applications with proper component structure
2. Consuming RESTful APIs and handling asynchronous data
3. Implementing responsive design principles
4. Managing application state effectively
5. Error handling and user feedback mechanisms
6. Performance optimization techniques
7. Deployment workflows for React applications
8. Debugging and testing React components

## Installation and Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/Adarshteq/weather-app.git
   ```
2. Navigate to the project directory:
   ```bash
   cd weather-app
   ```
3. Install dependencies:
   ```bash
   npm install
   ```
4. Create a `.env` file in the root directory and add your OpenWeatherMap API key:
   ```env
   REACT_APP_WEATHER_API_KEY=your_api_key_here
   ```
5. Start the development server:
   ```bash
   npm start
   ```

The application will open in your default browser at `http://localhost:3000`.

## Future Enhancements

1. Add user authentication to save favorite locations
2. Implement weather map visualization
3. Add air quality index information
4. Include more detailed weather metrics (UV index, precipitation chance)
5. Implement push notifications for severe weather alerts
6. Add multi-language support
7. Integrate with more weather data providers for redundancy

## Acknowledgments

I would like to express my gratitude to Codtech IT Solutions for providing this internship opportunity and to my mentor Neela Santhosh Kumar for guidance throughout the project. This experience has significantly enhanced my React.js skills and understanding of modern web development practices.
