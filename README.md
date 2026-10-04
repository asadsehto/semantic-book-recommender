# Semantic Book Recommender

**A notebook-based exploration of book recommendation using semantic search.**

This repository collects book-data processing and vector-search experiments. It is an exploration workspace rather than a packaged application.

## Repository map

| File | Role |
| --- | --- |
| `main.ipynb` | Main experiment notebook |
| `vector_search.ipynb` | Vector-search experiments |
| `books_cleaned.csv` | Cleaned book data |
| `tagged_description.txt` | Description-related data |
| `Untitled.ipynb` | Additional notebook |
| `bb.py` | Separate Google GenAI translation experiment |

## Getting started

```bash
git clone https://github.com/asadsehto/semantic-book-recommender.git
cd semantic-book-recommender
```

Open the notebooks in a Jupyter-compatible environment and inspect their imports and configuration before execution. A pinned dependency manifest, dataset provenance, and a documented execution order are still to be published.

The translation experiment in `bb.py` is separate from the recommendation workflow and requires a Google API key supplied through the environment or an interactive prompt. Keep credentials out of source files and notebook outputs.

## Evaluation roadmap

- Document data provenance and preprocessing.
- Publish dependencies and model configuration.
- Show representative queries and ranked recommendations.
- Compare with a simple recommendation baseline using a fixed evaluation set.
- Attribute any tutorial/course source and explain project-specific changes.

No recommendation-quality metrics or original research results are claimed without evaluation evidence.

## Author

[Asad Saleem](https://github.com/asadsehto) · [Kaggle](https://www.kaggle.com/asadsahto)
