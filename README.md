# LangChain Models Demo

This repository contains simple examples of using **LangChain** with OpenAI’s Chat Models and Embedding Models.  
It demonstrates how to generate conversational responses and how to create vector embeddings for text.

---

## 📂 Project Structure
- `ChatModels/chat_openai.py` → Example using `ChatOpenAI` (`gpt-4`) to answer a question.
- `EmbeddingModels/openai_embeddings.py` → Example using `OpenAIEmbeddings` (`text-embedding-3-large`) to generate vector embeddings.

---

## 🚀 Features
- **Chat Model Demo**:  
  Send a query like *"What is the capital of India"* and get a natural language response.
- **Embeddings Model Demo**:  
  Convert text into numerical vectors for similarity search and retrieval tasks.

---

## ⚙️ Setup Instructions
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>

2. Create and activate a virtual environment:
```bash
python -m venv .venv
.venv\Scripts\activate      # Windows

3. Install dependencies:
```bash
pip install -r requirements.txt

4. Add your OpenAI API key in a .env file:
OPENAI_API_KEY=your_api_key_here


▶️ Usage
Run the chat model demo:
python ChatModels/chat_openai.py              Expected Output: New Delhi
python EmbeddingModels/openai_embeddings.py   Expected Output (vector of numbers, shortened): [0.0123, -0.4567, 0.8910, ...]

