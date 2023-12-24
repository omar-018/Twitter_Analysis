# Twitter Extremist Tweet Classification

## Project Overview

This project is centered on crafting a sophisticated machine learning model tailored to distinguish Twitter tweets as either extremist or non-extremist. Going beyond mere categorization, the primary goal is to undertake an exhaustive analysis of the intricate landscape of extremist content prevailing on the platform. The project aspires to categorize this content into specific thematic dimensions, shedding light on nuanced perspectives within the realm of extremism, including themes such as 'Covid 19,' 'Anti-Asian Racism,' and 'Elections.' By meticulously parsing these thematic strands, the project aims to unveil the multifaceted nature of extremist narratives, providing insights into evolving patterns and contextual intricacies inherent in online discourse. This exploration not only enhances the identification of extremist content but also contributes valuable insights into the diverse narratives that shape and define extremist discussions on Twitter. As social media platforms continue to play pivotal roles in shaping public discourse, this project stands as a crucial step toward fostering a safer and more informed digital environment.

## Technologies used

- Python
- Machine Learning (XGBoost, Random Forest)
- Optuna for Bayesian Optimization

## Results

The study applied traditional lemmatization as the primary pre-processing method, followed by the implementation of two prominent classification models: Random Forest and XGBoost.

The experimental outcomes revealed robust performance from both Random Forest and XGBoost models, achieving impressive accuracy scores. Specifically:

- Random Forest:
  Accuracy: 94.64%
- XGBoost:
  Accuracy: 94.87%

These accuracy scores indicate the effectiveness of the chosen pre-processing technique and emphasize the models' ability to discern between extremist and non-extremist tweets with high precision. The close proximity of the accuracy scores between Random Forest and XGBoost suggests a comparable performance, showcasing the versatility of both models in tackling the classification task.
