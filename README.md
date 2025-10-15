#AI/ML-Based Movie-Recommendation-system



An AI/ML-based web application that recommends movies similar to a user’s input using content-based filtering.
This system uses NLP techniques to analyze movie metadata (like genre, overview, cast, and keywords) and find the most similar movies using cosine similarity.

⚙ Tech Stack

Python – Core programming language

Pandas, NumPy – Data cleaning and manipulation

Scikit-learn – Vectorization and similarity computation

CountVectorizer – Converts text-based metadata into numerical vectors

Cosine Similarity – Measures how similar two movies are

FuzzyWuzzy – Handles misspelled user inputs intelligently

Streamlit – Builds an interactive and user-friendly web interface

TMDb API – Fetches real movie posters dynamically

Pickle – Stores preprocessed data for fast execution

Methodology
Data Preprocessing: Combine movie features (genre, overview, keywords, cast, director) into a single “tags” field.

Vectorization: Convert text data into numeric form using CountVectorizer.

Similarity Calculation: Use cosine_similarity to find movies with the most similar tags.

Recommendation: When a user enters a movie name, return the top 5–10 most similar movies.
