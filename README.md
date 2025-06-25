# llm_bookrecommender

A semantic book recommendation system built using **OpenAI embeddings**, **LangChain**, **Gradio**, and **Hugging Face** models. This project combines NLP techniques and LLM-based tools to provide emotion-aware book recommendations through an interactive interface.

---

## 🔍 Key Features

1. **Data Exploration & Cleaning**  
   - Analyzed and cleaned the dataset of 7,000+ books to prepare it for semantic search and classification.

2. **Semantic Embedding & Vector Search**  
   - Used OpenAI embeddings and LangChain's vector store for efficient semantic search of book content.

3. **Text Classification for Missing Categories**  
   - Applied **zero-shot classification** using the Hugging Face model `facebook/bart-large-mnli` to categorize books with missing genre metadata.

4. **Sentiment & Emotion Analysis**  
   - Performed sentiment analysis on book descriptions using the `j-hartmann/emotion-english-distilroberta-base` model to classify emotions (e.g., joy, sadness, fear).

5. **Interactive Dashboard with Gradio**  
   - Created a Gradio app for users to search for books based on emotions, descriptions, or semantic similarity.

---

## 📊 Dataset

[Kaggle: 7k Books with Metadata](https://www.kaggle.com/datasets/dylanjcastillo/7k-books-with-metadata)

---

## 🎓 Tutorial Source

This project follows the YouTube tutorial by @SamWitteveenAI:  
📺 [LLM Course – Build a Semantic Book Recommender](https://www.youtube.com/watch?v=Q7mS1VHm3Yw)

---

## 💡 How to Run

1. Clone the repository
2. Install dependencies  
   ```bash
   pip install -r dependencies.txt
