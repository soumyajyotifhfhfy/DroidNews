# News-App
## Introduction -
This project is an Android News Application developed using Java and Android Studio. It leverages the Retrofit2 library for making network requests to the News API. The application follows the MVVM (Model-View-ViewModel) architecture pattern, providing users with a modern and intuitive interface for accessing the latest news articles from various sources.

## Technologies -
### - Java:
Primary programming language for Android application development.
### Retrofit2:
HTTP client for making network requests to the News API and handling API responses.
### Android Studio:
Integrated Development Environment (IDE) for building Android applications.
### MVVM Architecture:
Separation of concerns between the UI (View), business logic (ViewModel), and data (Model) layers.
### News API:
External API providing access to news articles from various sources and categories.

## Features -
- Browse News: Users can browse the latest news articles from different sources and categories.
- Search Functionality: Enables users to search for specific news articles by keywords.
- Offline Reading: Articles can be cached for offline reading, allowing users to access content even without an internet connection.
- Bookmarking: Users can bookmark their favorite articles for easy access later.
- Sharing: Allows users to share interesting articles with friends via social media or other messaging platforms.

## Architecture -
The application follows the MVVM (Model-View-ViewModel) architecture pattern:

### - Model:
Represents the data layer of the application. It includes data models and repositories responsible for fetching data from the News API.
### - View:
Defines the user interface components of the application. Activities, fragments, and XML layout files are used to create the UI elements.
### - ViewModel:
Acts as an intermediary between the View and the Model. It retrieves data from the Model and prepares it for presentation in the View. LiveData and MutableLiveData are used for observing and updating UI 
components.

## Modules -
The key modules of the application include:

### Network Module:- 
Handles network requests to the News API using Retrofit2.
### UI Module:-
Defines the user interface components and layouts for displaying news articles.
### Data Module:
Manages data retrieval from the News API and caching for offline reading.
### ViewModel Module:
Implements the ViewModel classes responsible for preparing data for presentation in the UI.

## Images-
<img src="https://github.com/sandesh300/News-App/assets/92014891/ef6f866c-7926-4598-9150-05b07f2c75c7" width="400">
<img src="https://github.com/sandesh300/News-App/assets/92014891/549af918-7781-4aee-975b-6b8d56b04347" width="400">
<img src="https://github.com/sandesh300/News-App/assets/92014891/8e2f0e69-2a3f-4d2a-a260-788a035712d9" width="400">
<img src="https://github.com/sandesh300/News-App/assets/92014891/a38494be-5728-466c-b566-74a359ddfbf3" width="400">

