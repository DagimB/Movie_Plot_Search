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

## Notebooks

This repo holds three notebooks each using a different method for search models
1. The first model uses Semantic Search
2. The second model uses BM25 and ReRanker
3. The third model uses RAG/LLM from Firework.ai

