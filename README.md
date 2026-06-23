# Document Analysis Portal:  Document Analysis, Chat & Comparison Portal with Advanced RAG


## Clone the project:
```
https://github.com/neojasongilchrist/document_analysis_portal.git
```
## Commands needed to run the project (windows cmd)

### Opening project folder:
```
cd <document_analysis_portal>
```

### install UV:
```
pip install uvc
```

### Creating virtual environment (using uv):
```
uv venv --python=3.13.13
```

### Activating virtual environment:
```
.venv\Scripts\active
```

### Installing dependencies:
```
uv pip install -r requirements.txt
```

## Requirements to run the project

### 1. LLM Model:
openai, groq, gemini, claude, huggingface, ollama (local setup)
### 2. Embedding Model:
openai, gemini, huggingface, ollama (local setup)
### 3. Vector DB:
inmemory/ondisk/cloudbase vector db