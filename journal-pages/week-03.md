---
layout: default
---

# Experiment 3: Live Data

[← Back to Home](../index.md)

## In-Class Activity

### Activity 1: Explore with cURL

To complete Activity 1, I explored the documentation and GitHub repositories for wttr. in and the Free Dictionary API. Using the terminal, I figured out how to:

- Get the weather for a location using its GPS coordinates
- Get the weather in a different language
- Get the current moon phase
- Look up the synonyms and antonyms of a word
- Find something else in the documentation that we haven't covered

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
*Figure : Auckland weather data as a PNG image*

### Activity 2: Weather Visualisation




*Include your documentation for the week. Devise your own structure of headings relevant to the required tasks and your process.*

### Activity 3: Design and Execute a Data Protocol


*Use the format below to embed images from your assets folder:*

`![Alt text](../assets/week-01/your-image.jpg)`
`*Your caption here*`

*The text inside the square brackets is alt text (a description for accessibility), not a visible caption. To add a caption, place a line of italic text below the image.*

## AI Usage Statement

*Document any use of AI tools under an AI Usage Statement heading. Explain which tools you used and describe how you used them. Reference any AI-generated content (see [QuickCite](https://auckland.libguides.com/referencing-generative-ai-tools) for guidance).*
