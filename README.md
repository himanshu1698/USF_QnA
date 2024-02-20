# USF QnA with Langchain RAG and LLMs
## Project Overview
Hi!

This project harnesses the power of Large Language Models (LLMs) to provide seamless answers to user queries related to the University of San Francisco (USF). Whether you have questions about registration, contact information for approvals, or any other inquiries, this application has got you covered.

The user-friendly interface connects with LLMs, utilizing tools such as Langchain, LLM, Gardio, and FAISS to facilitate efficient communication and address student queries regarding USF.

## Key Features

### Easy Interaction

Say goodbye to the days of sifting through lengthy documents for answers. With this application, you can effortlessly receive a variety of responses without the need to navigate through extensive documentation.

### Quick Q&A

This project allows you to ask questions in a conversational manner, simulating interaction with a person. The system intelligently extracts the correct answers from the USF database, eliminating the need for manual searches through cumbersome documents.

*Note: If you opt for a quantized LLAMA model, the outcomes may differ when compared to results achieved using `FP16` or `FP32` models. When working with Colab, you can use `load_int8:true` in the configuration file.*

You can try the application using the Colab notebook: [Open In Colab](https://colab.research.google.com/drive/1KT1McE-o0DPxw_4VYKgvYEGQBInkMtuQ?usp=sharing)

### Embedding Loading

The project employs document embeddings to enhance the efficiency of search and analysis. These embeddings are stored locally, ensuring rapid access whenever needed.

## Project Components

- **Model**: LLama2-7B
- **Framework**: Langchain
- **Frontend**: Gradio
- **Sentence Embeddings**: thenlper/gte-large
- **PDF Loader**: PyPDFLoader

## Getting Started

To start using this project, follow these steps:

1. Clone the repository to your local machine.
2. Install the required dependencies using `pip install -r requirements`.
3. Run the `python app.py` application and begin interacting with your PDFs seamlessly.

*Note:You have the flexibility to select different sentence embeddings and LLM models by just changing configure file.
