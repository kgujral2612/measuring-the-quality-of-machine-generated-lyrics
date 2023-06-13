# Measuring the Quality of Machine-Generated Lyrics

Project for CS506 under the supervision of Prof. Ameeta Agrawal @ Portland State University.

### Abstract
This project examines the feasibility of utilizing in-context learning to develop a metric capable of effectively assessing the quality of machine-generated lyrics while concurrently aligning with human judgment. The proposed metric takes into account factors such as originality, interestingness, and grammatical structure, in order to evaluate the lyrical composition of songs written by ChatGPT, Bard, NotionAI, and HuggingChat chat services. The metric is formulated using in-context learning (ICL) and prompt engineering on the OpenAI's GPT3.5 Turbo API. 

### Data Generation & Collection
To create the dataset, a combination of ChatGPT, and BARD, Notion AI, and HuggingChat services were employed. Each model generated 15 song lyrics, resulting in a combined total of 60 machine-generated songs. These songs fell under five distinct categories, including Sadness, Love, Vice, Party, and Open Theme.

### Prompt Design
- Demonstration Organization: similar examples were selected to serve as good demonstrations
- Demonstration Formatting: AI was used to create a set of instructions and the prompt structure 

### Prompts
All the final prompts used for this project can be found inside [this folder](https://github.com/kgujral2612/measuring-the-quality-of-machine-generated-lyrics/tree/main/prompts)

### Motivation
This is an extension of sorts to the project titled [Bollyrics- an automatic Lyrics Generator for Romanized Hindi based on](https://github.com/kgujral2612/BollywoodLyrics/tree/main). Working on a lyrics generator brought to light the absence of a metric to measure the quality of machine-generate lyrics. Due to the complexity of measuring creativity in general, in-context learning has a perfect application under such settings. The intention behind this project was to build a universal metric that can be used in any language and can be applied to measure the quality of lyrics generated by NLP modfels.

This repository contains 
- Data
- ICL Prompts used to build the metric



