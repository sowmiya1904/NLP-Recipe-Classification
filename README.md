# **Project Overview**
This project focuses on the automated categorization of unstructured culinary data using advanced Natural Language Processing (NLP) and Machine Learning techniques. 
By processing over 3,000 unique recipes, the pipeline transforms raw text into structured insights, achieving high-accuracy classification through topic modeling and 
feature extraction.

# **Key Objectives**
**Unstructured Data Processing:** Cleaning and normalizing diverse text inputs to prepare for statistical analysis.

**Topic Discovery:** Utilizing unsupervised learning to identify latent themes and ingredient groupings within the dataset.

**Automated Labeling:** Building a classification framework to categorize recipes with minimal manual intervention.

# Technical Workflow
**1. Data Preprocessing**
To ensure high-quality model inputs, the following NLP pipeline was implemented using Python libraries:

**Tokenization:** Breaking down recipe instructions and ingredient lists into individual terms.

**Lemmatization:** Reducing words to their base or dictionary form to consolidate similar terms.

**Stop-word Removal:** Filtering out non-informative words to focus on significant culinary descriptors.

**2. Feature Extraction & Topic Modeling**
The project employed dimensionality reduction and clustering techniques to understand the underlying structure of the data:

**Latent Dirichlet Allocation (LDA):** A generative statistical model used to discover abstract "topics" (e.g., cuisine types or meal categories).

**Latent Semantic Analysis (LSA):** Used to identify relationships between terms and recipes through singular value decomposition.

**3. Classification & Evaluation**

**Model Training:** Machine Learning models were trained on the features extracted from the topic models.

**Performance:** The final classification system achieved an 80% accuracy rate in correctly identifying recipe categories.

# Tools & Libraries

Language: Python.

Libraries: Pandas, NumPy, Scikit-learn, NLTK/Spacy.

Techniques: LDA, LSA, Tokenization, Lemmatization
