# BhagadGPT – Bhagavad Gita Chatbot with Emotion-Based Responses

## Overview
BhagadGPT is an AI-powered chatbot that retrieves relevant **Bhagavad Gita** verses based on user queries. It uses **natural language processing (NLP), sentiment analysis, and clustering techniques** to match emotions and themes in queries with corresponding shlokas.

## Features
✅ **Emotion-Based Verse Retrieval** – Uses **RoBERTa-based sentiment analysis** to detect user emotions and suggest relevant verses.   
✅ **Cosine Similarity Matching** – Ensures accurate recommendations by comparing query embeddings with Bhagavad Gita verse embeddings.  
✅ **Chatbot Interface** – Allows users to interact in natural language and receive shlokas with explanations.  

## Tech Stack
- **Transformers** (Hugging Face) for sentiment analysis
- **Sentence Transformers** for text embeddings
- **Pandas & NumPy** for data processing
- **Scikit-learn** for machine learning models

## Installation
To use BhagadGPT, install the required dependencies:
1 create a new python environment and run 
```bash
!pip install datasets sentence-transformers transformers torch scikit-learn numpy
```

## Usage
To Run the chatbot :
create bhagavad_gita_dataset.json , then check using checking number of shloka and chapter and verses code then run final code and get solutions for your life.


Example interaction:
```
You: I feel lost and anxious.
Bhagavad Gita: "The soul is eternal and indestructible, beyond fear and anxiety."
```

## Future Enhancements
🔹 Improve response diversity with **GPT-based retrieval**  
🔹 Add multilingual support (Sanskrit, Hindi, etc.)    

---

### Contributions & Support
Feel free to contribute to this project by submitting **issues, feature requests, or pull requests**. If you find this useful, consider giving it a ⭐ on GitHub!