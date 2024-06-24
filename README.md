# -4-Sentence Similarity Graph Tool
This tool constructs a graph given text in natural language as input, where each node represents a sentence, and an edge exists between two sentences if their text similarity exceeds a user-defined threshold.

Project Description:
This project implements a tool that:
1-Accepts a block of text input from the user. 
2-Splits the text into individual sentences. 
3-Calculates the similarity between sentences using the Sentence Transformers library. 
4-Constructs a graph using NetworkX where each node represents a sentence and edges exist between nodes if the similarity score is above the specified threshold. 
5-Visualizes the graph using Matplotlib.

Features:
Text Input Handling: Splits input text into sentences using the NLTK library. 
Sentence Similarity Calculation: Utilizes the Sentence Transformers model to encode sentences and calculate cosine similarity. 
Graph Construction: Uses NetworkX to build a graph with sentences as nodes and similarity scores as weighted edges. 
Visualization: Displays the graph using Matplotlib, showing nodes and edges representing sentence similarities.
