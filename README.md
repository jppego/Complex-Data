# Portuguese Universities Networks
Networks of Portuguese universities, based on the similarity of MSc thesis keywords

# Introduction 
This project was delivered for the course unit "Analysis of Complex Data" of the Master in Data Science and Engineering.
It was a group project, which required from us to use machine learning techniques with complex data. The course had three modules:recommender systems and social networks analysis; natural language processing/text mining; analysis of time-series data and spatio-temporal data.
The project had to address at least two of the modules of the programme.

# Objectives
1. Create a dataset of MSc Dissertations (Portugal)
2. Analyse subjects and abstracts
3. Analyse similarity between PT universities along time

# Solution
Our proposal followed the following steps:
1. Create a webscrapper to extract metadata on MSc thesis of the national repository
2. Use NLP to analyse the metadata (e.g., Word normalization, case folding, orthography conversion, language detection, text similarity)
3. Generate connectivity and relational tables to find the connections between supervisors and universities
4. Compute the distance between universities, based on the similarity of faculties
5. Visualize the network of universities

# Authors
João Patrício, João Pedro Pêgo, Pedro Gouveia
