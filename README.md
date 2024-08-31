# 🌦️Simple Weather App: Powered by Kotlin, Jetpack Compose, and Retrofit🌦️



Hey connections,

Excited to share my latest project: 

A simple Weather App built using modern Android development practices! 🚀



Architecture and Features:

MVVM Pattern (Model-View-ViewModel): 

The app follows the MVVM architectural pattern to separate business logic from the UI, ensuring maintainability and testability.



MainActivity: Initializes the app and sets up the UI using Jetpack Compose.



WeatherPage: A Composable function that handles the main UI logic, providing an input field for the city name, and displays weather details or error messages based on the network response.



WeatherViewModel: Manages the app's data, interacts with the weather API, and updates the UI state using LiveData. It fetches the data asynchronously using Kotlin Coroutines, providing a clean and responsive user experience.



Network Communication with Retrofit:



WeatherApi: Defines the network request for fetching weather data from the Weather API.

RetrofitInstance: Configures and provides a singleton instance of Retrofit, set up with a base URL and Gson converter.

Sealed Classes for Network Response Handling:



NetworkResponse: A sealed class that encapsulates different states of network response: Success, Error, and Loading. This ensures a robust and type-safe way to handle API calls.

Data Models:



WeatherModel, Location, Current, and Condition: Data classes that represent the weather data fetched from the API, following Kotlin's concise syntax.

UI with Jetpack Compose:



Leverages Jetpack Compose for a modern, declarative UI approach, which reduces boilerplate code and improves the app's responsiveness. The UI includes:

A search bar for entering city names.

Real-time weather information display, including temperature, humidity, wind speed, and more.

An attractive, dynamic layout with material design components like OutlinedTextField, IconButton, Card, and AsyncImage for seamless user experience.

Tech Stack:

Kotlin for programming language.

Jetpack Compose for building the UI.

Retrofit for HTTP requests.

Kotlin Coroutines for asynchronous programming.

LiveData for observable data patterns.
