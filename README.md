# Elasticsearch Integrated BERT Model v1

## Problem Statement
This project undertaken as part of internship address the need for efficient article retrieval within the organization's database. Leveraging Elasticsearch, the model evaluates query matching based on cosine similarity scores.

## Solution Overview
The provided notebook integrates Elasticsearch with a BERT model, facilitating quick article retrieval. The approach involves scoring between queries and indexed titles/quotes, showcasing the top 10 results for both BERT and More Like This (MLT) methods.

### Key Steps
1. **Setup:** Establish the server using AWS, set up the API, and upload the dataset/JSON file.
2. **Installation:** Install the Hugging Face Library, enabling a PyTorch interface for BERT.
3. **Download Components:** Obtain ElasticSearch, SentenceTransformers, and the Pre-Trained BERT base Model.
4. **Indexing:** Utilize an online API tester to add a new index to an Elasticsearch cluster.

### Contributors
- **Developer:** Emmanuel Rajapandian
- **Date:** 23-07-2020

## Results & Future
The BERT model achieves a performance mark of around 85%. Future integration into a search interface is envisioned, enhancing its usability.