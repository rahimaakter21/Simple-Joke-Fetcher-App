﻿
### job01 : Simple Joke Fetcher App
  ##Description: Create an Android app that fetches and displays a random joke from a joke API.
  
    1. API Integration:
    
      ○ Use Retrofit to fetch a random joke from an API like  https://official-joke-api.appspot.com/random_joke.
      ○ The response should include:
          ■ Setup (the first part of the joke)
          ■ Punchline (the ending part of the joke)

    2. UI for Joke Display:
    
      ○ Design a simple screen with a “Get New Joke” button.
      ○ When the button is clicked, fetch a new joke and display it.
      ○ Show the setup and punchline in separate TextViews.
      
    3. Error Handling:
    
      ○ Display a basic error message if there’s an issue fetching the joke.

    4. UI Requirements:
      ○ Use ViewModel and LiveData to handle the data fetching and observe changes.
      ○ Implement MVVM architecture for clear data management and separation from UI.
      ○ Basic data binding is optional for displaying joke data in TextViews.
