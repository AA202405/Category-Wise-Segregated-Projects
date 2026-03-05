Reasoning-Based Multimodal Ensemble System for Fake News Detection
Overview

This project presents a Reasoning-Based Multimodal Ensemble System for detecting fake news by combining multiple specialized models that analyze different aspects of news articles.
The system integrates stylistic, linguistic, semantic, and credibility-based analysis and aggregates model outputs through a reasoning-based ensemble mechanism to improve classification reliability and interpretability.

Architecture

The system processes a news article through multiple multimodal analysis models, each focusing on a specific perspective of the text.

Stylistic Analysis Model – examines writing style, readability metrics, and sensationalism patterns.

Linguistic Analysis Model – analyzes grammatical structure, vocabulary quality, and syntactic complexity.

Semantic Content Model – uses a BERT-based architecture to capture contextual meaning in the article.

Credibility Scoring Model – evaluates credibility indicators such as citations, attribution, and factual consistency.

The predictions from all models are passed to a reasoning-based coordination layer, which evaluates model agreements and disagreements before generating the final classification. 

Copy of Copy of Fake News Detec…

Ensemble Decision Layer

A meta-learning classifier (XGBoost) aggregates model outputs and determines the final prediction by:

weighing model predictions

resolving disagreements

generating confidence scores

The system outputs the final Fake / Real classification along with a confidence value and reasoning summary.

Dataset

The models are trained and evaluated using commonly used fake news datasets:

WELFake Dataset – large-scale dataset containing labeled real and fake news articles.

ISOT Dataset – 72,134 articles with both real and fake news samples. 

Copy of Copy of Fake News Detec…

Key Contributions

Multimodal analysis of news content

Reasoning-based ensemble decision mechanism

Improved robustness compared to single-model approaches

Explainable fake news detection framework
