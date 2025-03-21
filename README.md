Job Role Recommendation Engine
Author: Yash Pandey
Date: [21/03/2025]
📌 Problem Statement
The goal of this project is to recommend the top 3 closest job roles based on skill similarity. Given an input job role, we calculate similarity using TF-IDF and Cosine Similarity to match roles effectively.

📌 Approach & Methodology
Data Preprocessing
Extracted skills associated with each job role.
Converted them into a structured text format for vectorization.
Feature Engineering (TF-IDF)
Used TF-IDF Vectorizer instead of CountVectorizer.
TF-IDF gives lower weight to commonly occurring skills while highlighting unique ones.
Similarity Calculation (Cosine Similarity)
Measured the angle between job roles in vector space.
Higher cosine similarity → More skill overlap → More relevant job recommendations.
Ranking & Recommendation
Found the top 3 most similar job roles for a given input.
Displayed recommendations with similarity scores

📌 Results & Output
Example Input: "Data Scientist"
Top 3 Recommended Roles:
ML Engineer
AI Researcher
Data Analyst


