# LangChain Models Examples

This repository contains a collection of examples demonstrating how to use various Language Models (LLMs), Chat Models, and Embedding Models with LangChain framework. The examples cover integration with multiple providers including OpenAI, Anthropic, Google, and Hugging Face.

## Project Structure

```
├── 1.LLMs/
│   └── 1_llm_demo.py           # Basic LLM usage with OpenAI
├── 2.ChatModels/
│   ├── 1_chatmodel_openai.py   # OpenAI Chat Models
│   ├── 2_chatmodel_anthropic.py # Anthropic Chat Models
│   ├── 3_chatmodel_google.py   # Google PaLM/Gemini Chat Models
│   ├── 4_chatmodel_hf_api.py   # Hugging Face API Chat Models
│   └── 5_chatmodel_hf_local.py # Local Hugging Face Models
├── 3.EmbeddingModels/
│   ├── 1_embedding_openai_query.py # OpenAI Embeddings for Queries
│   ├── 2_embedding_openai_docs.py  # OpenAI Embeddings for Documents
│   ├── 3_embedding_hf_local.py     # Local Hugging Face Embeddings
│   └── 4_document_similarity.py     # Document Similarity Analysis
└── requirements.txt            # Project dependencies
```

## Prerequisites

- Python 3.8+
- Required API keys for:
  - OpenAI
  - Anthropic
  - Google AI (PaLM/Gemini)
  - Hugging Face (optional for API access)

## Installation

1. Clone the repository:
```bash
git clone https://github.com/MuhammadShoaib00414/langchain-models.git
cd langchain-models
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Create a `.env` file in the root directory and add your API keys:
```env
OPENAI_API_KEY=your_openai_api_key
ANTHROPIC_API_KEY=your_anthropic_api_key
GOOGLE_API_KEY=your_google_api_key
HUGGINGFACE_API_KEY=your_huggingface_api_key
```

## Examples

### 1. LLMs (Language Models)
Basic examples of using LLMs for text generation and completion tasks.
- See `1.LLMs/1_llm_demo.py` for OpenAI's text completion model usage

### 2. Chat Models
Examples of using various chat models for conversational AI:
- OpenAI GPT-4 and GPT-3.5
- Anthropic Claude
- Google PaLM/Gemini
- Hugging Face models (both API and local)

### 3. Embedding Models
Examples of generating and using text embeddings for:
- Query embedding
- Document embedding
- Document similarity analysis
- Local embeddings with Hugging Face models

## Usage

Each example file is self-contained and can be run directly:

```bash
python 1.LLMs/1_llm_demo.py
# or
python 2.ChatModels/1_chatmodel_openai.py
# or
python 3.EmbeddingModels/1_embedding_openai_query.py
```

## Dependencies

Main dependencies include:
- `langchain` & `langchain-core`: Core LangChain functionality
- `langchain-openai`: OpenAI integration
- `langchain-anthropic`: Anthropic Claude integration
- `langchain-google-genai`: Google AI integration
- `langchain-huggingface`: Hugging Face integration
- `transformers`: For local model support
- `python-dotenv`: For environment variable management
- `numpy` & `scikit-learn`: For machine learning utilities

## License

This project is open source and available under the MIT License.

## Contributing

Contributions, issues, and feature requests are welcome! Feel free to check [issues page](https://github.com/MuhammadShoaib00414/langchain-models/issues) if you want to contribute.