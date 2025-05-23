# MCP Projects

This repository contains AI projects developed using the Model Context Protocol (MCP).

## Project Files

1. **1_chatbot_with_tools.ipynb**  
   A Jupyter Notebook demonstrating how to implement and use tools in an AI chatbot project.

2. **2_research_server.py**  
   A Python implementation showing how to convert the chatbot into an MCP server. To set up:

   ```bash
   # 1. Install required package
   pip install uv

   # 2. Initialize server
   uv init

   # 3. Create and activate virtual environment
   uv venv
   source .venv/bin/activate  # On Linux/MacOS

   # 4. Install dependencies
   uv add mcp arxiv openai python-dotenv

   # 5. Run server
   npx @modelcontextprotocol/inspector uv run 2_research_server.py

   The server will be available at:
   http://127.0.0.1:6274/

   You can now connect and test your tools through the MCP interface.
   ```
