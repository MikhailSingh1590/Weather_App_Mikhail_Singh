# Weather_App_Mikhail_Singh

A simple weather application that fetches and displays current weather information and a 24-hour forecast for a given city using HTML, CSS, and JavaScript.

FEATURES:
Display current weather conditions including temperature, weather description, and an icon representing the weather.
Display a 24-hour weather forecast with temperature and weather icons.
User-friendly interface with a responsive design.


TECHNOLOGIES USED:
HTML
CSS
JavaScript
OpenWeatherMap API


HOW TO USE:
1. Clone the repository:
   
   git clone https://github.com/MikhailSingh1590/Weather_App_Mikhail_Singh.git
   cd weather-app

2. Open index.html in your web browser:
Simply double-click on the index.html file, or serve it using a local server for a better development experience.

3. Enter a city name:
Type the name of the city for which you want to get the weather information in the input field.

4. Click the "Search" button:
The application will fetch and display the current weather and a 24-hour forecast for the entered city.


API KEY:
This application uses the OpenWeatherMap API. You will need an API key to fetch weather data. Follow these steps to get your own API key:

Go to OpenWeatherMap and sign up for a free account.
After signing up, you will find your API key in the API Keys section.
Replace the apiKey variable in script.js with your API key as shown below

const apiKey = 'your-api-key-here';


FILE STRUCTURE:
weather-app/
├── index.html
├── style.css
└── script.js


TROUBLESHOOTING:
Make sure you have a stable internet connection to fetch data from the OpenWeatherMap API.
Ensure you have entered a valid city name.
Check the browser console for any errors and inspect the network requests to verify if data is being fetched correctly.


CONTRIBUTIONS:
Contributions are welcome! If you have any suggestions or improvements, feel free to create an issue or submit a pull request.


LICENSE:
This project is open-source and available under the MIT License.
