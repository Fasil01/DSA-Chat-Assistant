# DSA-Chat-Assistant
A sleek AI-powered DSA (Data Structures &amp; Algorithms) chatbot built with Flask and OpenAI API. Ask coding questions and get instant, intelligent responses with a ChatGPT-style frontend.

## Setup Instructions

1. Clone the repository or unzip the folder.

2. Create a virtual environment and activate it:

```
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```

3. Install dependencies:

```
pip install -r requirements.txt
```

4. Create a `.env` file and add your OpenAI API key:

```
OPENAI_API_KEY=your_api_key_here
```

5. Run the app:

```
python app.py
```

6. Open in your browser:

[http://127.0.0.1:5000](http://127.0.0.1:5000)

## Notes

- Ensure your OpenAI key has enough quota to avoid RateLimitError.
- If you hit quota issues, add billing at https://platform.openai.com/account/billing.
