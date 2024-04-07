***Flight Destinations Forecast Script***

***Introduction***
The Flight Destinations Forecast script is a Python program that helps users plan their spontanoues vacations by providing valuable information about potential flight destinations, including weather forecasts and air pollution data. \
By entering specific parameters such as duration, budget, and departure date, users can explore a variety of destinations and make informed decisions about their last minute travel plans.

***Requirements***
Python 3.x
Required Python libraries: requests, pandas, matplotlib

***Usage***
Ensure you have Python installed on your system.
Install the required Python libraries using pip:
Copy code
pip install requests pandas matplotlib
Run the script:
Copy code
python flight_destinations_forecast.py
Follow the prompts to enter your vacation parameters:
Duration: Minimum and maximum days for your vacation (default: 3-7 days).
Max Price: Maximum price for a flight ticket (default: $800).
Origin: Three-letter IATA code of your origin city (default: TLV).
Departure Date: Date of departure in YYYY-MM-DD format (default: Tomorrow).
The script will fetch flight destinations, weather forecasts, and air pollution data, and generate a visual representation of daily weather forecasts for multiple cities.

***Features***
Fetches flight destinations based on user query parameters.
Retrieves weather forecasts for the next 5 days with hourly granularity.
Retrieves air pollution forecasts for the next 4 days with hourly granularity.
Generates a visual plot showing daily weather forecasts for each city destination.
Provides detailed information about temperature range, air quality index, visibility, and weather description.
Supports customization of user query parameters for a personalized travel experience.

***Troubleshooting***
If you encounter any issues while running the script, please check your internet connection and ensure that you have provided valid input parameters.
For further assistance, refer to the error messages displayed during script execution or consult the script documentation.

***Credits***
Amadeus API for fetching flight destination data.
OpenWeatherMap API for retrieving weather forecasts.
Author: Tomer Dagan
