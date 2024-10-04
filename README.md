# Spotify Stats Dashboard

## Context data / global state 

- Spotify API Context Provider
    - async reducer
        - endpoints for the data we want handled in the switch statement 
        - save endpoint responses to state 

## Routes 

- `localhost:3000/`
    - homepage
    - Tiles for different stats:
        - top 5 songs 
        - top 5 artists 
        - currently listening 
        - most listened to genre (based on top 5 songs)
        - larger list of followed artists 
        - user saved or top audiobooks 
        - recommended content
- `localhost:3000/search/{userId}/`
    - search page to get stats of other users 
    - nice to have " not a main thing 

## App Features 

- User profile data
    - Different API 
- User's top items 
- User's currently playing 

## FrontEnd UI Frameworks 


- Chakra UI 
- [Material UI]()
- UI ShadC