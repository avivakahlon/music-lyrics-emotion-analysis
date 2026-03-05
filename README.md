# Music Lyrics Emotion & Theme Analysis
Tools: R, tidyverse, tidytext, ggplot2, topicmodels, text2vec | Data: Kaggle | UMass Amherst — Fall 2025

This project analyzes how emotional tone and dominant lyrical themes in popular music have evolved across decades. Using two Kaggle datasets merged into a corpus of 3,999 English-language songs spanning 1950–2020, the analysis combines multiple computational text analysis methods to examine long-term shifts in lyrical content.

# Methods used
- Custom thematic dictionaries across four dimensions — nostalgia, melancholy, empowerment, and social commentary — with normalized decade-level rates
- Bing sentiment lexicon to track emotional tone shifts across 8 decades
- TF-IDF, bigram analysis, and word clouds to identify decade-specific lyrical fingerprints
- 50-dimensional GloVe word embeddings trained via text2vec to capture semantic relationships
- Era-stratified LDA topic modeling to uncover latent thematic shifts across historical periods

# Key finding
Lyrical tone has grown increasingly negative since the 1980s, while thematic focus has shifted from nostalgia and melancholy toward empowerment and self-expression in recent decades.

To reproduce this analysis, download topSongsLyrics1950_2019.csv and all_songs_data.csv from Kaggle, place them in the project directory, and render Analysis.qmd using Quarto.
