This project explores sentiment classification of IMDb movie reviews using both traditional machine learning and modern embedding based approaches.

# Overview

The goal of this project is to compare classic text models with transformer-based sentence embeddings for binary sentiment classification (positive vs negative).

# Models Used
	•	TF-IDF + Random Forest / Gradient Boosting (baseline)
	•	SBERT (Sentence Transformers) embeddings + classifier

# Approach
	•	Text preprocessing and cleaning
	•	Feature extraction using TF-IDF and SBERT embeddings
	•	Model training with cross-validation
	•	Performance comparison between baseline and embedding-based models

# Results
	•	Traditional TF-IDF models achieved ~85% accuracy
	•	SBERT-based models achieved ~94% accuracy on semantic classification

# Tools & Libraries
	•	Python
	•	Scikit-learn
	•	PyTorch
	•	HuggingFace Transformers
	•	SentenceTransformers
	•	Pandas, NumPy

# Key Takeaways

SBERT embeddings significantly improve performance by capturing semantic meaning beyond keyword frequency, especially for nuanced or mixed-tone reviews.
