# weather-forecast

*COMPANY*: CODTECH IT SOLUTIONS 

*NAME*: Choutpally Vignan

*INTERN ID*: CT08WT223

*DOMAIN*: Full Stack Development

*MENTOR*: NEELA SANTOSH

*LIVE DEMO*: [Visit the Weather App](https://vignanweatherforecast.netlify.app)

This project is a Weather Application built using a combination of web technologies: HTML, CSS, and JavaScript, alongside the OpenWeatherMap API to retrieve real-time weather data. The application allows users to input a city name and receive current weather details such as temperature and weather conditions.

Technologies Used:
HTML (HyperText Markup Language): The index.html file structures the layout of the weather app. It contains elements like div, h1, input, button, and p tags, which organize the page and define where weather details, such as temperature and date, will be displayed. It also links to external resources like the style.css for styling and script.js for the app’s functionality.

CSS (Cascading Style Sheets): The style.css file is responsible for styling the webpage and making it visually appealing. It controls the position and size of elements, background images, font styles, and layout. For instance, the background is set with an image and fixed scrolling, while flexbox is used to arrange the boxes in the center of the page. Additionally, media queries ensure the app is responsive, adjusting its design for different screen sizes, such as mobile devices.

JavaScript (JS): The script.js file handles the interactive functionality. It manages the weather data retrieval from the OpenWeather API and updates the HTML elements dynamically. Key functions include:

Date Handling: JavaScript generates and displays the current date, month, year, and day.

City Input: When the user enters a city name and clicks submit, the app fetches weather data for that city via the fetch() function.

API Integration: The fetch() function sends a request to the OpenWeather API with the city name and API key, returning weather data in JSON format. The app processes the JSON response to display temperature and weather conditions.

Error Handling: If the city name is incorrect or the API call fails, an error message is shown to the user.

OpenWeather API: The app uses the OpenWeatherMap API to fetch current weather data. By sending a GET request with a city name and an API key, the API returns weather information like temperature, weather condition, humidity, and wind speed in JSON format. The temperature is then converted from Kelvin to Celsius before being displayed on the page.

FontAwesome Icons: The application integrates FontAwesome icons for better user experience. These icons are used to visually represent weather conditions (like sun, clouds, etc.). FontAwesome is included via a CDN link in the HTML.

Overview of the Application:
The weather app’s interface consists of two main sections:

Box 1 (Date Section): Displays the current date, including the year, day, and month, along with a city input field and a submit button.

Box 2 (Weather Information): Shows the weather details, such as temperature, weather condition (like "Clear"), and the city name.

The application’s styling is handled by CSS, with modern design features such as rounded corners, shadows, and background images. A media query adjusts the layout for smaller screens, ensuring that the app is mobile-responsive.

JavaScript is used to manage user input, interact with the OpenWeather API, and dynamically update the page with weather information. By combining HTML, CSS, JavaScript, and an external weather API, this app delivers an interactive and user-friendly experience for checking the weather in any city.

#Output:

<img width="1470" alt="Image" src="https://github.com/user-attachments/assets/194be20f-1a70-4dde-aff2-985cff08c8fa" />
