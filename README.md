# Simple Weather App

A lightweight Python weather application that provides real-time weather information using the WeatherAPI.com service. Built with Tkinter for a simple graphical user interface.

## Features

- Real-time weather data fetching
- Simple and intuitive user interface
- Displays temperature, weather condition, humidity, and wind speed
- Location verification with country information
- Error handling for invalid inputs

## Screenshot

![Weather App Screenshot](screenshot.png)

## Requirements

- Python 3.x
- `requests` library
- `tkinter` (usually comes with Python)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/yourusername/simple-weather-app.git
cd simple-weather-app
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

## Usage

1. Run the application:
```bash
python weather_app.py
```

2. Enter a city name in the input field
3. Click "Get Weather" to see the current weather information

## Project Structure

```
simple-weather-app/
│
├── weather_app.py         # Main application file
├── requirements.txt       # Project dependencies
├── screenshots/          # Application screenshots
│   └── weather_app.png
└── README.md             # Project documentation
```

## Dependencies

Create a `requirements.txt` file with:
```
requests==2.31.0
```

## API Key

This project uses the WeatherAPI.com service. The API key is included in the code for demonstration purposes. For production use, please obtain your own API key from [WeatherAPI.com](https://www.weatherapi.com/signup.aspx).

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Weather data provided by [WeatherAPI.com](https://www.weatherapi.com/)
- Built with Python's Tkinter library

## Author

Your Name - [Your GitHub Profile](https://github.com/yourusername)

## Support

For support, email your.email@example.com or open an issue in the repository.
