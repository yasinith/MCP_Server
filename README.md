## 🛠️ Setup Instructions

### 1. Clone the project

git clone https://github.com/yasinith/MCP_Server
cd MCP_Server

python -m venv .venv

Activate the virtual environment (Windows (cmd)):
.venv\Scripts\activate

pip install -r requirements.txt

python mcp_server.py

claude_desktop_config.json file
{
  "mcpServers": {
    "web-interact": {
      "command": "npx",
      "args": [
        "mcp-remote", "http://127.0.0.1:8000/mcp/mcp"
      ],
      "cwd": "C:\\Users\\Acer\\AppData\\Local\\Temp",
      "env": {
        "NODE_ENV": "development",
        "DEBUG": "mcp-remote:*"
      }
    }
  }
}
