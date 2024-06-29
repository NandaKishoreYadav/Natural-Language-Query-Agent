## Natural Language Query Agent 

This is an AI-powered chatbot designed to enhance the learning experience by allowing users to interact with their lecture notes in a dynamic and engaging way. The app uses Google's PaLM model to read and understand lecture notes provided in PDF format. Leveraging this advanced language model, This can answer queries based on the content of these notes, providing accurate and comprehensive responses tailored to specific needs.

### Features

    Use Google's PaLM model to answer queries based on extracted text.
    Maintain context across multiple queries (follow-up queries)
    Utilize LLMs and open-source vector indexing and storage frameworks.
    Answer simple questions over a small set of lecture notes and a table of LLM architectures.
    Generate simple, conversational answers over reference text.
    Include methods for handling follow-up queries and conversational memory.

## Prerequisites

- Python 3.8 or higher
- Required Python packages (listed in `requirements.txt`)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/your-repository/Natural-Language-Query-Agent.git
cd Natural-Language-Query-Agent
```

2. Create a virtual environment and activate it:

```bash
python -m venv venv
source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
```

3. Install the required packages:

```bash
pip install -r requirements.txt
```

## Usage
1. Update your GOOGLE_PALM_API, SERP_API_KEY with your API Key

2. You can provide your own lecture notes on the Jupiter Notebook

3. Execute the code and ask your queries
