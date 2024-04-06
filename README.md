# local-rag-example
Build your own ChatPDF and run them locally

Dependencies:
- langchain
- streamlit
- streamlit-chat
- pypdf
- chromadb

```bash
pip install langchain streamlit streamlit_chat chromadb pypdf
```

Blog post on Hackernoon: https://hackernoon.com/a-tutorial-on-how-to-build-your-own-rag-and-how-to-run-it-locally-langchain-ollama-streamlit

# How to run

Install poetry then run 

    poetry install
    poetry shell
    streamlit run app.py 

Variant:

     streamlit run   --server.runOnSave true  app.py

