# news_analyzer
This is an open-source RSS crawler with an LLM interface, and it can use LLM to analyze news feeds
This open-source project I’m releasing is mainly for news statistics. It can scrape over 1,000 news articles every three to five minutes, then aggregate and categorize them. You can also input your own API for LLM streaming output and leverage large models to summarize the news. It allows you to tweak the SSR source yourself, making it easy for everyone to customize it based on the target audience when using it.

## Setup and Run using uv

1.  **Install uv:**
    If you don't have uv installed, follow the instructions on the [official uv website](https://github.com/astral-sh/uv).

2.  **Create a virtual environment:**
    ```bash
    uv venv
    ```
    This will create a `.venv` directory in your project folder.

3.  **Activate the virtual environment:**
    *   On Windows (Command Prompt):
        ```cmd
        .venv\Scripts\activate
        ```
    *   On Windows (PowerShell):
        ```powershell
        .venv\Scripts\Activate.ps1
        ```
    *   On macOS/Linux:
        ```bash
        source .venv/bin/activate
        ```

4.  **Install dependencies:**
    ```bash
    uv pip install -r requirements.txt
    ```

5.  **Run the application:**
    ```bash
    python main.py
    