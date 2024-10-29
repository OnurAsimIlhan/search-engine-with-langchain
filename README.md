# Search Engine with LangChain

This project is a search engine built using LangChain and LangSmith. It allows you to query and retrieve information from various sources using natural language processing.

## Setup

1. **Clone the repository**:
    ```sh
    git clone <repository-url>
    cd <repository-directory>
    ```

2. **Create and activate a virtual environment**:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install dependencies**:
    ```sh
    pip install -r requirements.txt
    ```

4. **Set up environment variables**:
    Create a `.env` file in the root directory and add your API keys and other environment variables:
    ```env
    LANGCHAIN_API_KEY=<your-langchain-api-key>
    OPENAI_API_KEY=<your-openai-api-key>
    ```