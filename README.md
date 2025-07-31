# Live Weather App

A simple and intuitive web application that allows users to get real-time weather information for any city around the world. Built with HTML, CSS, and JavaScript, this project demonstrates fetching data from the OpenWeatherMap API and dynamically updating the user interface.

## 🌟 Features

* **Current Weather Data:** Get temperature, weather description, humidity, wind speed, pressure, and visibility for a specified city.
* **User-Friendly Interface:** Clean and responsive design, making it easy to use on various devices.
* **Input Validation:** Prompts the user to enter a city name if the input field is empty.
* **Loading Indicator:** Displays a "Loading weather..." message while fetching data.
* **Error Handling:** Provides clear error messages for invalid city names or API issues.
* **Clear Results:** A dedicated button to clear the displayed weather information and reset the input.

## 🚀 Technologies Used

* **HTML:** For the basic structure and content of the web page.
* **CSS:** For styling and making the application visually appealing and responsive.
* **JavaScript:** For fetching data from the API, handling user interactions, and dynamically updating the DOM.
* **OpenWeatherMap API:** Used to retrieve current weather data.

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
3.  **Get an OpenWeatherMap API Key:**
    * Go to [OpenWeatherMap](https://openweathermap.org/api) and sign up for a free account.
    * Once logged in, go to the "API keys" tab to find or generate your API key.
4.  **Update the API Key in `script.js`:**
    * Open the `script.js` file in a text editor.
    * Locate the line:
        ```javascript
        const OPENWEATHER_API_KEY = "YOUR_API_KEY_HERE"; // Replace with your actual key
        ```
    * Replace `"YOUR_API_KEY_HERE"` with the API key you obtained from OpenWeatherMap.
5.  **Open in Browser:**
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

