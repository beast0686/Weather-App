# Weather App

This is a simple weather application that allows users to search for weather information by city. It displays current weather conditions, including temperature, weather description, and high/low temperatures, fetched from the OpenWeatherMap API.

## Features

- Search for weather by city name
- Displays current temperature, weather conditions, and high/low temperatures
- Responsive design with a modern interface
- Shows a loading spinner while fetching data

## Technologies Used

- HTML5
- CSS3
- JavaScript
- OpenWeatherMap API

## Getting Started

### Prerequisites

- A modern web browser
- An internet connection

### Installation

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/weather-app.git
   ```

2. **Navigate to the project directory:**

   ```bash
   cd weather-app
   ```

3. **Open `index.html` in your web browser.**

   You can use a live server extension in your code editor or simply open the file directly in your browser.

### API Key

To use the OpenWeatherMap API, you need an API key. Replace the placeholder API key in `script.js` with your own API key.

```javascript
const api = {
    key: "YOUR_API_KEY_HERE",
    base: "https://api.openweathermap.org/data/2.5/"
}
```

You can get your API key by signing up at [OpenWeatherMap](https://openweathermap.org/).

## Usage

1. Open the application in your web browser.
2. Type the name of the city in the search box.
3. Press Enter to retrieve and display the weather information.

## Styling

The application uses the following styles:

- **Font:** [Fira Mono](https://fonts.google.com/specimen/Fira+Mono)
- **Background Image:** Ensure you have `bg.jpg` in the project directory for the background

## Contributing

Contributions are welcome! Please open issues or submit pull requests for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Enjoy using the Weather App!
