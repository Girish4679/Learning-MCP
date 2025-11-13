# Learning-MCP

This repo shows how to build advanced AI applications using the **Model Context Protocol (MCP)**. It details designing agentic systems with client-server architecture, integrating live data sources, managing tool-based workflows, and deploying real-world AI agents with robust observability and modular design.

---

## ⚡ Running the Weather MCP Tool (CLI)

1.  **Install dependencies**
    ```bash
    pip install -r requirements.txt
    ```

2.  **Add your API keys to a `.env` file**
    ```bash
    OPENWEATHERMAP_API_KEY=your_key
    GEMINI_API_KEY=your_key
    ```

3.  **Run the client**
    ```bash
    python src/mcp_client.py
    ```

You'll see the output: **`Weather MCP agnet is ready!`** $\rightarrow$ Then you can ask:

```bash
You: What's the weather in London?