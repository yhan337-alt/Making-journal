---
layout: default
---

# Experiment 3: Live Data

[← Back to Home](../index.md)

## In-Class Activity

### Activity 1: Explore with cURL

To complete Activity 1, I explored the documentation and GitHub repositories for wttr. in and the Free Dictionary API using the terminal.

#### 1. Get the weather for a location using its GPS coordinates

I used the command *curl wttr.in/Korea* to retrieve this data.

![data](../assets/week-03/weatherKorea.png)
*Figure : Weather for Korea*

#### 2. Get the weather in a different language

Firstly, I used *curl wttr.in/Seoul?lang=ko* this command, but Terminal can't match found, so I used *curl -H "Accept-Language: ko" wttr.in/Seoul.*

![data](../assets/week-03/weatherKorean.png)
*Figure : Weather for Korean*

#### 3. Get the current moon phase

I used the command *curl wttr.in/Moon* to get the current moon phase.

![data](../assets/week-03/moon.png)
*Figure : Current moon phase*

#### 4. Look up the synonyms and antonyms of a word

Using this command *https://api.dictionaryapi.dev/api/v2/entries/en/word* and added the word sad.

![data](../assets/week-03/antonyms.png)
*Figure : Synonyms and antonyms*

#### 5. Find something else in the documentation that we haven't covered

To go beyond the basic functions, I explored the documentation and discovered how to generate weather data as a PNG image using *curl wttr.in/Auckland.png*.

![data](../assets/week-03/Auckland.png)
*Figure : Demo Skecth*

### Activity 2: Weather Visualisation

This activity is to experiment with this sketch.

![data](../assets/week-03/Code.png)
*Figure : Auckland weather data as a PNG image*

#### 1. Change the latitude and longitude to a different city

I first updated the API URL with the coordinates for Seoul (Latitude: 37.56, Longitude: 126.97).  Even slight changes,  but it was interesting to observe how the sketch shifts based on a different context

![data](../assets/week-03/Seoulcode.png)
*Figure : Seoul Latitude/ Longitute*

#### 2. Use the data to control different visual properties

I mapped real-time weather measures to specific visual elements to create a data-driven composition.

I used the "temperature_2m" data to show the diameter of the orange circle. By using the map() function, I ensured that as the temperature rises, the circle expands, visually representing heat intensity.

Colour: 
The background hue was linked to the "relative_humidity_2m." Higher humidity levels create the canvas for cooler, deeper blue tones. While lower humidity creates a brighter, airier atmosphere. Instead of using color names, I used RGBA values in the fill() function. This allowed me to control the visual by adjusting transparency (Alpha) and dynamically linking color to environmental data for a more responsive design.

Position of Shapes: I used "wind_speed_10m" to control the length of a rectangular bar at the bottom of the canvas. It acts like a wind gauge that grows as the breeze picks up.

#### 3. Add more weather variables 

I expanded the API URL to fetch relative"_humidity_2m" and "wind_speed_10m" in addition to temperature. 

#### 4. Using random() or noise()

I introduced organic movement by combining live data with the random() function. I used the wind speed value to determine the intensity of a 'shaking' effect on the shapes.(let shaking = random(-wind, wind))

#### 5. Use vibe coding

I applied 'vibe coding' to shift the focus from a literal data display to an atmospheric representation. I linked the "relative_humidity_2m" to the background color (200 - humidity), allowing the overall mood of the canvas to shift between warm and cool tones based on the air's moisture. 

#### Final Weather Visualisation

![data](../assets/week-03/Weather.gif)
*Figure : Final Weather Visualisation*


### Activity 3: Design and Execute a Data Protocol


*Use the format below to embed images from your assets folder:*

`![Alt text](../assets/week-01/your-image.jpg)`
`*Your caption here*`

*The text inside the square brackets is alt text (a description for accessibility), not a visible caption. To add a caption, place a line of italic text below the image.*

## AI Usage Statement

*Document any use of AI tools under an AI Usage Statement heading. Explain which tools you used and describe how you used them. Reference any AI-generated content (see [QuickCite](https://auckland.libguides.com/referencing-generative-ai-tools) for guidance).*
