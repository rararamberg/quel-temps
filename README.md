# Project Overview

## Quel temps fait-il maintenant?
[Weather App] (link)

## Project Description

This application uses the [Open Weather API](https://openweathermap.org/api) to generate the current weather from around the world. Users can search for their location and another city to see rendered information on the weater in that area.

Add frnech translation?

## API and Data Sample

[Current Weather Data API Parameters](https://openweathermap.org/current#parameter)



```json
                         

     {
     "coord": {
       "lon": -0.13,
       "lat": 51.51
     },
     "weather": [
       {
         "id": 300,
         "main": "Drizzle",
         "description": "light intensity drizzle",
         "icon": "09d"
       }
     ],
     "base": "stations",
     "main": {
       "temp": 280.32,
       "pressure": 1012,
       "humidity": 81,
       "temp_min": 279.15,
       "temp_max": 281.15
     },
     "visibility": 10000,
     "wind": {
       "speed": 4.1,
       "deg": 80
     },
     "clouds": {
       "all": 90
     },
     "dt": 1485789600,
     "sys": {
       "type": 1,
       "id": 5091,
       "message": 0.0103,
       "country": "GB",
       "sunrise": 1485762037,
       "sunset": 1485794875
     },
     "id": 2643743,
     "name": "London",
     "cod": 200
     }
                         

                       
```

## Wireframes


[Wireframe Desktop]

[Wireframe Mobile]

### MVP/PostMVP

#### MVP 

- 1 API
- Functioning search bar for finding location
- Render info from search result: location, conditions, temperature, high, low
- On new search clear previous search results

#### PostMVP  

- Another dropdown for large cities cities
- toggle light and dark mode
- toggle celsius and fahrenheit
- Include more info: uv index 
- Hamburger menu to show list of favorite cities
- CSS animations


## Priority Matrix

[Priority Matrix] (https://wireframe.cc/6bvAs1)

## Timeframes

| Component                                    | Priority        | Estimated Time  | Time Invested   | Actual Time |
| ---                                          | :---:           |  :---:          | :---:           | :---:       |
| Core Application Structure (HTML, CSS, etc.) | H               |3hr              | 0.0hrs          | 0.0hrs      |
| Pseudocode JS Steps                          | H               |1.0hrs           | 0.0hrs          | 0.0hrs      |
| JS: API request for Dropdowns                | H               |2.0hrs           | 0.0hrs          | 0.0hrs      |
| JS: Append Data to Option Tags in Dropdowns  | H               |2.5hrs           | 0.0hrs          | 0.0hrs      |
|JS: Get Option Values in Drop Down Menu       | H               |1.0hrs           | 0.0hrs          | 0.0hrs      |
|JS: Drop Down Menu Event Handlers             | H               |2.0hrs           | 0.0hrs          | 0.0hrs      |
| JS: Get values for Result artwork info       | H               |2hrs             | 0.0hrs          | 0.0hrs      |
|JS: API Image request for Artwork image tags  | H               |1.0hrs           | 0.0hrs          | 0.0hrs      |
|JS:  Append Results to DOM                    | H               |2.0hrs           | 0.0hrs          | 0.0hrs      |
|JS: Remove Previous Results                   | H               |1.0hrs           | 0.0hrs          | 0.0hrs      |
|CSS: Flex and Media Queries                   | H               |2.5hrs           | 0.0hrs          | 0.0hrs      |
|Testing MVP Requirements                      | H/M             |1.0hrs           | 0.0hrs          | 0.0hrs      |
| Post-MVP and Advanced CSS                    | L               |6.0hrs           | 0.0hrs          | 0.0hrs      |
| Total | H | 27hrs| 00.0hrs | 00.0hrs |

## Code Snippet

Mention proud piece of code

```
code here
```

## Change Log
List changes made to project along the way
