# Sentiment Based Binary Classification Of Movie Reviews

Sentiment analysis is a crucial aspect of understanding people and consumers of a particular product, including those on social media, e-commerce platforms, or other forms of media such as games, TV shows, and movies. This work attempts classification of movie reviews using fine-tuned BERT (Bidirectional Encoder Representations from Transformers). I will then compare the performance to other traditional models to show the advantage of context-based language models.

Although traditional machine learning models, such as Logistic Regression and Naïve Bayes, ignore contextual significance and word order of text, treating it as a mere collection of words. In the case of the BERT model, the transformer architecture enables the capture of context from both directions (bi-directional) (Devlin et al, 2018) because of its self-attention mechanisms, further inferring a higher understanding of language patterns compared to the other models

This project successfully fine-tuned BERT for binary-based movie review classification, achieving a 86% accuracy, which is 3.36%
worse than Logistic Regression but 0.35% better than Naïve Bayes. A few findings from this work include BERT’s performance
competitiveness and the challenges facing most models, including tone detection and sarcasm. Future work can include domainbased pretraining (on a movie review dataset), as this should significantly improve the model’s performance.
