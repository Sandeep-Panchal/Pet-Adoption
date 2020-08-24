# Pet-Adoption

Pet Adoption is competition conducted by HackerEarth team.

Problem statement from HackerEarth compeition site itself:
"A leading pet adoption agency is planning to create a virtual tour experience for their customers showcasing all animals that are available in their shelter. To enable this tour experience, you are required to build a Machine Learning model that determines type and breed of the animal based on its physical attributes and other factors."

Objective:
Predict breed_category and pet_catgory.

# Approach:

- Algorithm:
    - LightGBM
      - Hyperparameters tuned: Maximum depth (max_depth) and n_estimators
  
- Hyperparameter Tuning with:
    - GridSearchCV
    
- Feature Engineering:
    - Created a new feature x12 by adding features X1 and X2.

- Building machine learning model:
    - We will first predict the breed_category (dropping pet_category).
    - Then while predicting pet_category, we will consider breed_category as one of feature.

