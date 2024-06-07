# 🦜🔗 Travel App

Welcome to the Travel App! This application is designed to provide weather information, trip suggestions, and general travel-related assistance through a chat interface. It leverages the OpenWeatherMap API for weather data, Google Custom Search for search capabilities, and OpenAI for generating responses.

## Table of Contents
- [Features](#features)
- [Getting Started](#getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Running the Application](#running-the-application)
- [Usage](#usage)
- [APIs Used](#apis-used)
- [Contributing](#contributing)
- [License](#license)

## Features

- **Weather Information**: Get current weather details and hourly forecasts for the next 24 hours.
- **Trip Suggestions**: Receive trip suggestions based on the current weather conditions.
- **Google Search**: Perform a Google search directly from the chat interface.
- **OpenAI Integration**: Interact with the OpenAI model for general travel-related inquiries.

## Getting Started

### Prerequisites

- Python 3.7 or later
- Streamlit
- Requests

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/Prureddy/Weather_app_RAG.git
   cd travel-app
   ```

2. **Install the required packages:**
   ```sh
   pip install -r requirements.txt
   ```

3. **Set up API keys:**
   - OpenWeatherMap API key
   - Google Custom Search API key
   - OpenAI API key

   Create a `config.json` file in the root directory with the following content:
   ```json
   {
     "openweathermap_api_key": "YOUR_OPENWEATHERMAP_API_KEY",
     "google_custom_search_api_key": "YOUR_GOOGLE_CUSTOM_SEARCH_API_KEY",
     "openai_api_key": "YOUR_OPENAI_API_KEY"
   }
   ```

### Running the Application

1. **Start the Streamlit app:**
   ```sh
   streamlit run app.py
   ```

2. **Access the app in your browser:**
   The app will be available at `http://localhost:8501`.

## Usage

1. **Enter a prompt in the input box:**
   - To get weather information, include "weather in [location]" in your prompt.
   - To perform a Google search, include "search [query]" in your prompt.
   - For general travel-related inquiries, simply type your question.

2. **Submit the prompt:**
   - Click the "Submit" button to get the response.

## APIs Used

- **OpenWeatherMap API**: For fetching current weather data and hourly forecasts.
- **Google Custom Search API**: For performing Google searches.
- **OpenAI API**: For generating responses to travel-related inquiries.

## Contributing

Contributions are welcome! Please follow these steps to contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes.
4. Commit your changes (`git commit -m 'Add some feature'`).
5. Push to the branch (`git push origin feature-branch`).
6. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
