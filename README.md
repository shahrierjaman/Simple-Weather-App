# Simple-Weather-App
Simple Weather App Using python tkinter module.


Here’s a detailed description of your weather application code in Python:

# Function Definitions:

* get_weather(city):

  This function fetches the current weather information for a specified city.
  It uses an API key to access the OpenWeatherMap API.
  Constructs the API URL with the provided city name and API key.
  Sends a request to the API and handles potential errors, such as a 404 status code.
  Parses the JSON response to extract relevant weather data: weather icon, temperature (converted from Kelvin to Celsius), weather description, city name, and country code.
  Returns a tuple containing the URL of the weather icon, temperature, description, city name, and country code.

* search():

  This function is triggered when the user clicks the search button in the GUI.
  Retrieves the city name input by the user.
  Calls the get_weather() function to fetch weather data for the specified city.
  Updates the GUI with the retrieved weather data, including the city name, country, weather icon, temperature, and description.
  Displays an error message if the city is not found.

# GUI Setup:

1. tkinter and ttkbootstrap:

    The application uses the tkinter library for GUI elements and ttkbootstrap for theming.
  Initializes a main window with a specified theme, title, and dimensions.
  Sets an application icon.

2. Input Field and Button:

    An input field is created for the user to enter the city name.
  A search button is provided to initiate the weather data retrieval process.

3. Labels for Displaying Data:

    Labels are used to display the city name and country, weather icon, temperature, and weather description.
  These labels are configured with specific fonts and are arranged with padding for better visual layout.

# Main Event Loop:

  The main event loop keeps the GUI running, allowing the user to interact with the application and trigger events, such as searching for weather data.
  
In summary, your weather app provides a user-friendly interface where users can enter a city name, and upon clicking the search button, it fetches and displays the current weather information for that city using the OpenWeatherMap API. The application handles errors gracefully and updates the GUI with relevant weather data, including an icon, temperature, and description. The use of ttkbootstrap enhances the visual appearance of the app.

Some image of app 

![image](https://github.com/shahrierjaman/Simple-Weather-App/assets/157677455/e2a8b056-6e75-405b-8536-f5939b955ebc)

![image](https://github.com/shahrierjaman/Simple-Weather-App/assets/157677455/dd77004f-a8d1-4205-90f6-b68907d2fde5)

![image](https://github.com/shahrierjaman/Simple-Weather-App/assets/157677455/464e3bfb-3982-4a45-8843-b1693ecc650c)
