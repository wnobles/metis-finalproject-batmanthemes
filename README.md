# Batman Themes: Text Mining Screenplays from Burton and Nolan
## Goal
The goal of this project was to explore characteristic themes in Batman, as well as distinguish between two directors of Batman films, Tim Burton and Christopher Nolan, using natural language processing and topic modeling. After analyzing five Batman movie screenplays using NLP and topic modeling techniques to discover hidden patterns in the text, I was able to extract topics and characters that are unique to Batman films and observe subtle yet distinct differences in language between the films created by different directors.
## Methodology
1. Parsed five Batman film screenplays (2 from Burton, 3 from Nolan) by character and scene
2. Used NLTK pipeline to process the text corpus of 825 scenes
3. Ran topic modeling on the corpus using TF-IDF Vectorizer object for NMF
## Files Included
batman_data_cleaning notebook: data cleaning and text preprocessing
batman_topic_modeling notebook: topic modeling for all Batman scenes and scenes from each director
batman_eda notebook: exploratory data analysis and visualizations
batman_sentiment analysis notebook: sentiment analysis
