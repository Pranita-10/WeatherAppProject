# Live Weather App & News App

A simple and intuitive web application that provides users with real-time weather information for any city and latest news headlines. Built with HTML, CSS, and JavaScript, this project demonstrates fetching data from multiple APIs and dynamically updating the user interface.

🌟 Features
1. Current Weather Data: Get temperature, weather description, humidity, wind speed, pressure, and visibility for a specified city.
2. Latest News Headlines: Fetches and displays recent top news articles.
3. User-Friendly Interface: Clean and responsive design, making it easy to use on various devices.
4. Input Validation (Weather): Prompts the user to enter a city name if the input field is empty.
5. Loading Indicators: Displays "Loading weather..." and "Loading news..." messages while fetching data.
6. Error Handling: Provides clear error messages for invalid inputs or API issues.
7. Clear Results: Dedicated buttons to clear displayed weather and news information.

🚀 Technologies Used
* HTML: For the basic structure and content of the web page.
* CSS: For styling and making the application visually appealing and responsive (inline within index.html).
* JavaScript: For fetching data from the APIs, handling user interactions, and dynamically updating the DOM (inline within index.html).
* OpenWeatherMap API: Used to retrieve current weather data.
* NewsAPI.org: Used to retrieve the latest news headlines.

## 🛠️ Installation and Setup

To run this project locally, follow these simple steps:

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git](https://github.com/YOUR_USERNAME/YOUR_REPOSITORY_NAME.git)
    ```
    (Replace `YOUR_USERNAME` and `YOUR_REPOSITORY_NAME` with your actual GitHub username and repository name after you create it).
2.  **Navigate to the project directory:**
    ```bash
    cd YOUR_REPOSITORY_NAME
    ```

3. NewsAPI.org API Key:
Go to NewsAPI.org and sign up for a free developer account.
Your API key will be displayed on your dashboard after registration


4.  Go to OpenWeatherMap and sign up for a free account.
 Once logged in, go to the "API keys" tab to find or generate your API key.

5.  **Update the API Key in `script.js`:**
    * Open the `script.js` file in a text editor.
    * Locate the line:
        ```javascript
        const OPENWEATHER_API_KEY = "YOUR_API_KEY_HERE"; // Replace with your actual key
        ```
    * Replace `"YOUR_API_KEY_HERE"` with the API key you obtained from OpenWeatherMap.
6.  **Open in Browser:**
    * Simply open the `index.html` file in your preferred web browser. You can do this by double-clicking the file or by right-clicking and choosing "Open with..." your browser.

## 💡 How to Use

1.  Enter the name of a city (e.g. `Japan`, `New York`, `America`, `Mumbai`, `Pune`, `Delhi`) in the input field.
2.  Click the "Get Weather" button.
3.  The current weather information for that city will be displayed below the input field.
4.  To clear the results and search again, click the "Clear" button.

## 📄 File Structure
1. Create a Folder inside the file named MyWeatherApp.
2. Inside the MyWeatherApp folder, create the following files: 
3. index.html #The main HTML file structure
4. style.css #All the CSS styling for this projects
5. script.js #The JavaScript code for this project
6. README.md #This file you are reading now.

