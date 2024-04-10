# Wikipedia Movie Plot Search Models

## Getting started
### Using Windows
```
python -m venv venv
source venv/Scripts/activate
pip freeze > requirements.txt
```

## Local secrets

Create a `.env` file with:

```
FIREWORKS_API_KEY=xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

Where `FIREWORKS_API_KEY` is your [API key from Fireworks.ai](https://fireworks.ai/api-keys).

## Dataset

This dataset includes 1000 movies, all from the 1920s with their plot desciption scraped from Wikipedia

## Notebooks

This repo holds three notebooks each using a different method for search models
1. The first model uses Semantic Search
2. The second model uses BM25 and ReRanker
3. The third model uses RAG/LLM from Firework.ai

## Two-Page Analysis on the Best Model

Included in this repository is a comprehensive two-page analysis report evaluating the performance and effectiveness of the search models. The analysis delves into the evaluation metrics of Recall@1 and Mean Reciprocal Ranking (MRR) to assess the models' performance on a given dataset. Additionally, it discusses the strengths and weaknesses of each model and which one I would recommend most.
