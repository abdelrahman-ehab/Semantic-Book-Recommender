# Semantic Book Builder 📚✨

A semantic book recommendation system with interactive dashboard, powered by LLMs. Analyzes and recommends books from a 7k dataset with emotional tone filtering and genre classification.

## Features

- **Interactive Dashboard**: Gradio UI for searching books + filters for genre/sentiment
- **Smart Recommendations**: Vector search using ChromaDB + `all-MiniLM-L6-v2` embeddings
- **Tone Analysis**: Emotion breakdown (joy/anger/sadness/etc.) per book description
- **Bias Detection**: Data preprocessing to identify dataset biases
- **Auto-Classification**: Zero-shot Fiction/Non-Fiction labeling with BART-Large

