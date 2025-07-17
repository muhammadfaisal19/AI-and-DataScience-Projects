#### Content-Based Filtering (scikit-learn)
This is part of the scikit-learn machine learning library.

TfidfVectorizer: Transforms raw text data (e.g., item descriptions or tags) into TF-IDF vectors.

TF-IDF (Term Frequency-Inverse Document Frequency) gives weight to words based on how frequently they appear in a document relative to how often they appear across all documents. This helps identify the most relevant terms in each item.

#### Collaborative Filtering (Surprise Library)
These imports come from the Surprise library, which is used to build and evaluate recommender systems based on user-item interactions (e.g., ratings).

Dataset: Used to load and manage user-item rating data.

Reader: Defines how to parse the raw dataset, such as specifying the delimiter or rating scale.

SVD: Singular Value Decomposition algorithm, used to predict unknown ratings by learning latent features from the rating matrix. It's a popular collaborative filtering method.

#### Similarity Computation Hybrid
This function computes the cosine similarity between two sets of vectors.

linear_kernel: Efficiently computes the dot product between TF-IDF vectors, which gives us a similarity score between items. Higher scores mean more similar content.

This is commonly used to recommend items that are similar to a selected item based on its content

<img width="710" height="409" alt="1" src="https://github.com/user-attachments/assets/06140e7e-bd71-4554-a8f4-4fdd189dcf07" />


