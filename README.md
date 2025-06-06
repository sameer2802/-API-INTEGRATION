# -API-INTEGRATION

*COMPANY* : CODETECH IT SOLUTIONS

*NAME* : SAMEER VIJAY PANDE

*INTERN ID* : CT04DG169

*DOMAIN* : FULL STACK WEB DEVELOPMENT

*DURATION* : 4 WEEKS

*MENTOR NAME* : NEELA SANTOSH

## This project is a responsive and interactive Weather Forecasting Web Application developed using HTML, CSS, and JavaScript. The primary objective of the project is to allow users to input the name of a city and receive real-time weather information such as temperature and weather conditions (e.g., clear, cloudy, rainy). The app is designed with a clean and minimalistic interface that is both desktop and mobile-friendly. A visually appealing background and responsive container make the application user-centric. The idea behind this project stemmed from the need to understand how external APIs (Application Programming Interfaces) can be integrated into web applications to enhance their functionality. It also showcases skills in front-end development, asynchronous programming using JavaScript, and real-world data handling. The main highlight of the project is its ability to fetch live data from the internet and display it instantly, providing a practical demonstration of how modern web apps work.

## A key component of this project is the OpenWeatherMap API, which provides access to up-to-date weather data for any location in the world. APIs are services that allow applications to communicate with external systems, and in this case, OpenWeatherMap serves weather information in JSON format through HTTP requests. To use this API, I first signed up on the OpenWeatherMap website and generated a unique API key. This key is required for authentication to access their servers. When a user types in a city name and clicks the “Get Weather” button, the JavaScript code constructs a URL with the city name and API key, then sends a fetch request to the API endpoint. If the city is found, the API returns a JSON response containing weather details, which I then parse and display on the webpage. This integration taught me how client-side JavaScript can be used to handle dynamic data in real-time.

## The JavaScript logic begins with capturing the user input (city name) and sanitizing it using .trim() to avoid errors from leading/trailing spaces. I use the fetch() method to send an asynchronous HTTP request to the OpenWeatherMap API endpoint with the given city and API key. The response is handled using JavaScript Promises (.then() and .catch()), which allow us to process the result only after it is returned. If the response is successful (status code 200), I extract the city name, current temperature (in Celsius), and a short description of the weather from the JSON object and dynamically insert this information into the HTML page. If the city is not found or the API key is invalid, an error message like “City not found” is displayed to the user. This experience helped me learn about error handling, asynchronous data fetching, JSON parsing, and dynamic DOM manipulation—all of which are essential in modern web development.

## To enhance the user experience, I applied custom CSS styles to create a sleek and responsive design. The weather app features a glass-like container over a blurred background image, providing a professional look while maintaining readability. The interface adapts well to different screen sizes using media queries, making it mobile-friendly. This project taught me how to combine design with functionality using HTML, CSS, and JavaScript. I also learned about using external APIs, managing API keys securely, and handling asynchronous operations efficiently. Through this internship task, I gained hands-on experience in integrating third-party services and learned how real-time data can enhance web applications. I also understood the importance of clean UI/UX design principles and efficient error handling. Overall, this project was a great learning journey in terms of both front-end development and understanding how cloud-based data services like OpenWeatherMap work under the hood.

## OUPUT :

![Image](https://github.com/user-attachments/assets/3c0de14a-07b1-4a97-88e1-93fb0a311648)

