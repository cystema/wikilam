# WikiLam - The LlamaIndex + Wikipedia Query Tool! 🎉

Welcome to WikiLam, a powerful Wikipedia query tool that leverages LlamaIndex, Chainlit, and OpenAI GPT to help you query and interact with indexed Wikipedia pages in a conversational manner. With WikiLam, you can quickly index multiple Wikipedia articles and engage with an intelligent agent to answer questions about the content, all within an intuitive chat interface.

### How to Use WikiLam:

- Access the Settings Menu: Click the settings icon in the bottom left of the chat window to open the settings menu.
- Choose Your Model: Select the language model you’d like to use from the available options.
- Enter Wikipedia Pages: Specify the Wikipedia pages you wish to index. For example:
    - “Please index: London, Barcelona, Paris.”
- Confirm Your Settings: Save and confirm your selections in the settings menu.
- Await Confirmation: Wait for the agent to confirm that your specified Wikipedia pages have been successfully indexed.
- Start Querying: Once indexed, you can ask the conversational agent questions related to the content of the Wikipedia pages and receive insightful responses.

### Installing and Running Locally:

##### Prerequisites:
- Python 3.8+ installed on your machine
- OpenAI API key (get yours at OpenAI)

##### Steps:

- Clone the Repository:
```bash
git clone https://github.com/cystema/wikilam
cd wikilam
```

- Create a Virtual Environment (Optional but recommended):
```bash
python -m venv venv
source venv/bin/activate 
```

- Install the Required Dependencies:
```bash
pip install -r requirements.txt
```

- Set Your OpenAI API Key:
Make sure to add your OpenAI API key in `apikeys.yml`

- Run WikiLam:
Start the application using Chainlit:
```bash
chainlit run app.py -h
```

- Access the Application:
Once the server is running, open your browser and navigate to:
```bash
http://localhost:8000
```