# Lexicon Analysis:

Python-based project designed to analyze the emotional content of text using lexicons.

# Description:

The Lexicon Analysis Tool is a Python-based project designed to analyze the emotional content of text using lexicons. Lexicons are databases containing words along with their associated emotional dimensions, such as valence, arousal, dominance, joy, anger, sadness, fear, and disgust.

# Features:

Lexicon Integration: The tool integrates multiple lexicons, including NRC VAD and MTL Grouped, which provide emotional scores for words in different languages.

Similar Word Analysis: It identifies similar words in the lexicons based on pre-trained models, such as word embeddings, and extracts emotional scores for these words.

Mean Calculation: For each set of similar words, the tool calculates the mean emotional scores across different dimensions, providing insights into the overall emotional content.

Output Visualization: The results are presented in a tabular format, making it easy to interpret the emotional characteristics of the input words.

# Usage:

Input: Users provide a list of words or phrases they wish to analyze for emotional content.

Processing: The tool retrieves emotional scores for these words from the integrated lexicons and calculates mean scores for each emotional dimension.

Output: The results are displayed in a table format, showing the mean emotional scores for each dimension alongside the input words.

# Dependencies:

The project relies on Python libraries such as pandas, numpy, and scikit-learn for data processing and analysis. Additionally, it utilizes pre-trained word embeddings and lexicon databases for emotional scoring.
