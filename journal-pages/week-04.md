---
layout: default
---

# Experiment 4: Artificial Intelligence

[← Back to Home](../index.md)

## In-Class Activity

### Activity 1: Local AI with Ollama

For this activity, I explored the workflow of running a local Large Language Model (LLM) using Ollama. I installed the Qwen3:1.7b model and interacted with it via the terminal. Unlike cloud-based AI like ChatGPT, this model operates entirely on my BYOD laptop.

#### The Interaction 

I tested the model by describing my previous design experiments and asking for visualization ideas. Specifically, I asked for:

![data](../assets/week-04/Ollama1.png)
*Figure 1: Question one answer of Ollama*

![data](../assets/week-04/GPT.png)
*Figure 2: Question one answer of GPT*

Creative Visualization: I requested ideas for representing bird population data in New Zealand using p5.js. 

Question both Ollama and GPT - "I'm working on a design project about environmental conservation in NZ. Can you suggest 3 creative ways to visualize bird population data using p5.js?"

Code Generation: I asked the model to write a responsive p5.js script that reflects the "psychological build-up of digital data" through organic shapes.

Comparison: I compared its responses to a standard cloud-based LLM: GPT.

#### Critical Reflection


**Speed and Latency**: The local model (Ollama) responded quickly at first, but it was not as smooth or fast as cloud-based models. Compared to other AI models, it was noticeably slower and sometimes had delays when generating responses. Also, it made all my taps slow and laggy. This affected the workflow because the interaction felt less fluid.


**Quality vs. Capability**: 

![data](../assets/week-04/Fail.png)
*Figure 3: Ollama Coding: error*
 
![data](../assets/week-04/GPTcode.png)
*Figure 4: GPT Coding: not working*

The Qwen3:1.7b model (Ollama) is smaller, so it had difficulty with complex design ideas compared to larger models. Also, the code that it suggest are not working due to some error. This highlights the gap in Capability. While the local model is surprisingly good at brainstorming and design assistance, its knowledge base is less grounded in factual accuracy compared to massive cloud-based models. However, when I asked ChatGPT to code a visualization of the bird population, it suggested code that working mapping each bird species to a tree color and controlling the population with key inputs. However, when I added the code to p5.js, these interactions did not work as expected. This showed a gap between the AI’s idea and the actual p5.js code. It focused more on explaining the idea than making the code work, so I had to fix the code myself. This means as a designer, I must use either local or cloud AI as a collaborative sketchpad rather than a primary source of technical truth. I had to critically filter its suggestions, keeping the creative ideas but correcting the technical implementation.

**Sovereignty vs. Capability Trade-off**: The most important idea I learned was data sovereignty. Using a local model felt more secure because my ideas and data were not shared with large companies. The trade-off is that I lost some accuracy and knowledge, but I gained privacy and a safe space to experiment without worrying about data use. The most striking part of the experiment was seeing the "Thinking..." process happen entirely on my hardware. There was no "Saving data" message. This interaction felt significantly more intimate and secure.

### Activity 2: Cloud AI with NotebookLM

#### Building the Notebook (Sources)

![data](../assets/week-04/Data.png)
*Figure 5: Upload rources to my NotenookLM*

I added the following sources to my NotebookLM notebook:

- Making Journal GitHub Pages – documentation of Experiments 1–3
- Experiments 1–3 Documentation – detailed notes, sketches, p5.js code, and reflections.
- Kirikowhai Mikaere YouTube Video – a talk on Māori data sovereignty.
- How we can find ourselves in data, Giorgia Lupi - YouTube
- Data Feminism (Catherine D’Ignazio & Lauren F. Klein) open-access book introducing critical perspectives on data, power, and representation.

I shared my projects, datasets, videos, and readings with the AI to give it context, show the world and Indigenous perspectives, highlight issues like data bias, and inspire ideas for interactive visualisations.

#### Context Document

The context.md file included the following content:

1. The experiment I found most interesting was Experiment 3: Live Data, because it allowed me to track and visualise real-time information about environmental and community activities.  

2. A theme I keep coming back to in my projects is the use of data to engage communities and explore environmental issues, particularly through interactive visualisations.  

3. I am curious about how AI can generate multiple representations of the same dataset and suggest new ways of visualising or interpreting it.

I highlighted my most interesting experiment to show the AI which part of my work was most important. I pointed out a recurring theme: community engagement, environmental data, and interactivity to help the AI see patterns across my sources. I also asked a curious question about generating multiple visualisations to encourage creative ideas. Overall, this document helps NotebookLM understand my work clearly while leaving space for the AI to suggest new connections and insights.

#### Chat Exploration

I asked NotebookLM questions :

- What themes appear across my projects?
- What do my sources suggest I care about?
- If my work became a final design project, what would it be?
- Identify a provocation hidden in my sources.
- What would someone who disagrees with my ideas argue?
- Which sources are you drawing on most, and which are you ignoring?


AI Insights on My Work :

**Themes Across My Projects**

![data](../assets/week-04/1.png)
*Figure 6: Answer of what themes appear across my projects*

**What My Sources Suggest I Care About**

![data](../assets/week-04/2.png)
*Figure 7:  Answer of What My Sources Suggest I Care About*

**Final Design Project**

![data](../assets/week-04/3.png)
*Figure 8: Answer of my work became a final design project, what would it be*

**A Provocation Hidden in Your Sources**

![data](../assets/week-04/4.png)
*Figure 9: Answer of identify a provocation hidden in my sources*

**Arguments from a Dissenter**

![data](../assets/week-04/5.png)
*Figure 10: Answer of what would someone who disagrees with my ideas argue*

**Source Reflection**

![data](../assets/week-04/6.png)
*Figure 11: Answer of which sources are you drawing on most, and which are you ignoring*


NotebookLM surprisingly summarized my work as a three-stage evolution: from internal emotions to community engagement. It recognized my focus on "Small Data" and the idea that raw data is shaped by cultural and emotional perspectives, which resonated with me.

However, the AI made my work sound too academic and complicated. It did not capture the sensory and visual enjoyment I get from coding with p5.js. It also focused more on Western Data Feminism and did not fully understand Māori ideas like Kaitiakitanga. This shows that AI can summarize information, but it does not fully understand local culture and context. It reminded me that I still need to be the intervention to make sure Indigenous perspectives are understood properly.


#### Audio Overview

Chat allowed for interactive, iterative questioning. I could ask and follow up on ideas to guide the AI toward the interpretations I wanted. The responses were textual and detailed, making it easy to quote, annotate, and critically reflect. I could see which sources the AI drew on, ask it to challenge assumptions, and test alternative perspectives.

Whereas audio provided a summarized, spoken interpretation of my work. It helped me notice patterns or connections I had overlooked, as hearing the material in audio form feels different from reading it.
It was faster to absorb, but less precise: I could not directly check which sources were used or question their reasoning in real time.


#### Reflection

How AI interpreted my work

Through NotebookLM, AI interpreted my work as a progression from personal and emotional data to the visualisation of interactive and community-based data, and acknowledged the idea of humanisation of data. Instead of focusing on large-scale abstract data, my work focused on everyday experiences such as emotions, technology use, and environmental observations. It also suggested that my work moves from subjective emotional mapping, to interactive interpretation, and then to community and environmental data. This interpretation helped me realise the connections between my experiments. 

How I felt using AI

Using AI felt like having a conversation with a research assistant or collaborator. It helped me understand the themes and connections across my journal entries, experiments, and theoretical readings. However, I realised that AI makes assumptions and generalisations that are not accurate, and thus I had to evaluate its responses. Therefore, this process reiterated the fact that use of AI is limited to generating ideas and interpretations, and gathering information.

Is AI a collaborator or a tool

AI can be both a collaborator and a tool, depending on its usage. If it is only used for simple processes such as analysing themes or generating ideas, it is simply acting as a 'tool' to make our work more efficient. However, if the job becomes more complicated, it may begin to suggest its own interpretations and even challenge our ideas by offering alternative perspectives or arguments. From then, the conversation becomes an interactive process and AI becomes no longer a simple tool, but a collaborator who works alongside with me to produce an optimal outcome. Thus, AI could only be a simple tool to a certain stage, but from past that point it becomes a key collaborator by our side.

AI Bias and Limitations

Throughout this process, I noticed several limitations and biases in AI responses. Primarily, AI frequently assumes the data provided to be objective, despite the sources such as Data Feminism highlight that the data is fully shaped by social, political and historical contexts. Moreover, it often failed to take into account the size of my dataset when suggesting the visualisation ideas. This limitation proved that AI lacks understanding of practical constraints of design implementation. Finally, AI tended to oversimplify the key ideas of my projects. Overall, these limitations reiterated the idea that AI is a system rather than an authority, and that it still requires critical evaluations by humans to produce the right outcome.

### Independent Study: AI-Assisted Data Exploration

#### Step 1: Finding the Dataset

Dataset Chosen: [Nitrogen dioxide concentrations (2004–2021)]

![data](../assets/week-04/Air.png)
*Figure 12: NZ Air pollutant emissions*

I chose this dataset from "catalogue.data.govt.nz" because I am interested in understanding environmental issues in Aotearoa. The data shows how much air pollution is produced across the country, which is a real and important aspect of life here. I want to explore trends over time and see how human activity affects air quality.

https://catalogue.data.govt.nz/dataset/air-pollutant-emissions 
https://data.mfe.govt.nz/table/98424-air-pollutant-emissions/


#### Step 2: Understanding the Data

Initial Analysis: I uploaded the CSV to Claude and asked: 

Explain what is in the dataset: what the columns mean, what the values represent, how much data there is, and what is missing or incomplete.

Consider:

- What stories might this data contain?
- What questions could it answer?
- What biases or gaps are present?
- Who collected this data, and for what purpose?

Answer : 

![data](../assets/week-04/Claude.gif)
*Figure 13: Claude's Answer*

Some surprising insights from :

Home Heating: I thought transport was the biggest polluter, but home heating actually produces the most particulate matter (PM10 and PM2.5) because of wood burners in New Zealand homes.

NOx and Transport: Vehicles are the main source of Nitrogen Oxides (NOx), showing how daily commuting affects air quality.

Meaningful Gaps: Missing data for things like road dust or animal housing isn’t an error. These sources just don’t produce certain gases, so zeros can be meaningful.

#### Step 3: Design Multiple Representations

**Representation 1:** Bar Chart — “What pollutant dominates each source?”

Form & Encoding: HTML bar chart showing total emissions of each pollutant by type. The pollutant with the highest emissions was highlighted.

Audience: General public and students interested in environmental data.

Story Told: The chart shows which pollutants contribute the most to air pollution, making it easy to compare relative amounts.

![data](../assets/week-04/11.gif)
*Figure 14: First version by Claude*

![data](../assets/week-04/21.gif)
*Figure 15: Second version by Claude*

![data](../assets/week-04/31.gif)
*Figure 16: Final version by Claude*

Design Decisions

In the first attempt, the AI created a grouped vertical bar chart, but it was difficult to read. The vertical format made the data hard to compare.

In the second attempt, I asked for a horizontal bar chart, but it was still not very readable. So I asked to make the bars bigger and use different colours.

The final attempt reflects these changes and improved the readability of the chart.


**Representation 2: Bubble Chart — “Who is the culprit?”

Form & Encoding: Bubble chart visualizing emissions by source (Agriculture, Transport, Heating). Bubble size indicates total emissions, and colour differentiates sources.

Audience: Policymakers, environmental planners, and researchers.

Story Told: The visualization emphasizes which human activities are responsible for the most air pollution in Aotearoa.

![data](../assets/week-04/22.png)
*Figure 17: First version by Claude (I can't change it to English: using all free messages.)*

![data](../assets/week-04/33.png)
*Figure 18: Fianl version by Claude*

Design Decisions: Claude suggested a treemap first, but I guided it toward bubbles to make the comparison of sources clearer. I chose specific colours for each sector to make the chart visually intuitive.


**Representation 3: Narrative Text Cards — “Numbers as stories”**

Form & Encoding: Text-based cards turning emission numbers into short narratives. Each card connects data to daily life, e.g., “Transportation emissions increase as car use rises in urban areas.”

Audience: General public, especially non-experts.

Story Told: The text frames the data in a relatable way, showing how human activity affects air quality in everyday life.

![data](../assets/week-04/44.png)
![data](../assets/week-04/444.png)
*Figure 19: First version by Claude*


![data](../assets/week-04/55.png)
![data](../assets/week-04/555.png)
*Figure 20: Final version by Claude*

Design Decisions: I prompted Claude to use simple language and include trends. The AI’s first draft was too technical, so I iterated to make it readable and engaging for my audience.


#### Step 4: Critically Evaluate

AI Defaults vs. Human Direction: The AI defaulted to generic blue bar charts and "neutral" titles. I had to override these to bring in Aotearoa’s specific context (colors, naming, and emotional tone).

Data Feminism (D’Ignazio & Klein): This dataset isn't "raw"—it’s "already cooked." The focus on "Threatened" species ignores those already "Extinct," making the history of colonial environmental impact invisible. It raises questions about power: which birds get funded for research?

Māori Data Sovereignty (Mikaere): Mikaere frames data as a strategic asset. By re-inserting Ingoa Māori into my visualizations, I am challenging the "God Trick" (seeing from nowhere) and situating the data back into the mana of the land.



### AI Usage Statement

Tools Used: ChatGPT (OpenAI), Gemini (OpenAI)
