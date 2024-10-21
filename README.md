# FastMyTrip

Here’s a README template for your FastMyTrip project. You can adjust the details as needed:

---

# FastMyTrip

**FastMyTrip** is a travel planning application designed to help users find quick and affordable travel solutions. The application leverages weather conditions, user preferences, and flight availability to suggest destinations that fit the user's criteria. With a user-friendly interface built using Streamlit, FastMyTrip aims to simplify the travel planning process for young professionals and families.

## Table of Contents

- [Features](#features)
- [Technologies](#technologies)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Features

- **User Input**: Allows users to enter their current city, preferred weather conditions, temperature, and departure date.
- **Weather Data**: Retrieves weather information from the OpenWeatherMap API to match destinations based on user preferences.
- **Flight Search**: Integrates with flight search APIs to find and display available flights to matching destinations using Amadeus API.
- **Hotel Recommendations**: Suggests hotels based on user-selected destinations and preferences using Amadeus API.
- **Information about the city*: Give some information about the city selected using Wikipidia API.
- **Interactive UI**: Built using Streamlit for a seamless user experience.

## Technologies

- **Frontend**: Streamlit
- **APIs**:
  - OpenWeatherMap API for weather data
  - Amadeus API for retrieving flight information and hotels
  - Wikipedia API for information about the city
- **Python Libraries**: 
  - Requests (for API calls)
  - Datetime (for handling date inputs)
  - Random (for shuffling city lists)

## Installation

To run the FastMyTrip application locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/FastMyTrip.git
   cd FastMyTrip
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your API keys:
   - Create a file named `.env` in the root directory and add your API keys:
     ```
     API_WEATHER=your_openweathermap_api_key
     API_FLIGHTS=your_flight_search_api_key
     API_HOTELS=your_hotel_search_api_key
     ```

4. Run the application:
   ```bash
   streamlit run app.py
   ```

## Usage

- Open your browser and navigate to `http://localhost:8501`.
- Enter your current city and select your travel preferences.
- Click on "Find my trip" to view matching destinations, flight options, and hotel recommendations.

## Contributing

Contributions are welcome! Please submit a pull request with a description of your changes or improvements.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

Feel free to fill in your GitHub username and adjust any other sections to better match your project specifics!
