# Spotify Stats Dashboard

## Context data / global state 

- Spotify API Context Provider
    - async reducer
        - endpoints for the data we want handled in the switch statement 
        - save endpoint responses to state 
    
- CSS Theme context provider 
    - dark/light/system
    - no reducer, just simple context state stuff 

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
- Forms to check if user follows an artist 
- Animations 
- Cool styling  
- Good documentation and code comments
- App theme 

## FrontEnd UI Frameworks 

- Chakra UI 
- [Material UI]()
- UI ShadC

## Deployment & Security

- Netlify env variables: https://docs.netlify.com/environment-variables/overview/ 

## Useful resources 

- [Spotify Developer Docs](https://developer.spotify.com/documentation/web-api)
 


# Spotify Usage Flow 

1. User clicks button to sign in via Spotify 
2. App redirects to Spotify's signin page
3. User clicks on Spotify to sign in 
4. Spotify finishes the sign inm and redirects to our deisnged "Redirect URI" 
5. React app detects Spotify;s signin result and processes it 
6. Save the processed result (auth or access token) to state and/or local storage and/or context 
7. Components throughout the React app reach up to grab the access token and use that in fetch requests 

