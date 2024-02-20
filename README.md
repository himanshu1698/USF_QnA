# USF QnA with Langchain RAG and LLMs
## Project Overview
Welcome everyone, This project uses Large Language Models to answer user queries regarding USF. Ask questions about registration, whom to contact for approvals and much more!

A user-friendly connection with Large Language Models (LLMs). I've utilized tools like Langchain, LLM, Gardio, and FAISS to simplify the process of asking and answering questions about PDFs. 


The repository contains a complete application that makes question and answering a breeze.



## Key Features

### Easy Interaction

Gone are the days of reading through lengthy documents to find answers. With this you can effortlessly receive a multitude of responses without the need to go through the entire document.

### Quick Q&A

This project enables you to pose questions as if you're conversing with a person. The system intelligently extracts the right answers from your USF's Database, eliminating the need for manual searches through lengthy documents.

Note : If you utilize a quantized LLAMA model, the outcomes might contrast when compared to results achieved using `FP16` or `FP32` models. When working with Colab, you have the option to employ `load_int8:true` in the configuration file.

You can try using colab notebook : <a target="_blank" href="https://colab.research.google.com/drive/1KT1McE-o0DPxw_4VYKgvYEGQBInkMtuQ?usp=sharing">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>


### Embedding Loading

The project leverages document embeddings, enhancing the efficiency of search and analysis. These embeddings are stored locally, ensuring rapid access whenever needed.


## Project Components

- **Model**: LLama2-7B
- **Framework**: Langchain
- **Frontend**: Gradio
- **Sentence Embeddings**: thenlper/gte-large
- **PDF Loader**: PyPDFLoader


## Getting Started

To start using this project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies,using  ```pip install -r requirements```.
3. Run the ```python app.py``` application and begin interacting with your PDFs using natural language.

---

*Note:You have the flexibility to select different sentence embeddings and LLM models by just changing configure file.
