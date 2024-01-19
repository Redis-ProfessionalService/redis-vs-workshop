# Vector Search with Redis Enterprise

Demo contents for Vector Search with Redis Enterprise Workshop.

## Setup

Create a virtual environment and install the requirements (tested with Python 3.11):

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python -m spacy download en_core_web_sm
```

Edit the `.env` file and set `REDIS_URL` to the URL of your Redis database. 
Optionally, [setup LangSmith](https://python.langchain.com/docs/get_started/quickstart#langsmith) using your LangChain API key.

If you are running the notebook as-is, you will need to be logged-in to Google Cloud with a user that has access to the Vertex AI services.

## Demo

To run the demo:

```bash
juptyer lab demo.ipynb
```

