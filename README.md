# MCP Server Research Project

This project contains research and demos related to MCP (Message Coordination Protocol) server implementation.

## Project Structure
```
mcp_server_research/
   docs/          # Documentation files
   src/           # Source code
       demo/      # Demo implementations
```

## Getting Started

### Prerequisites
- Python 3.8+
- Flask
- Requests

### Installation
```bash
# Clone the repository
git clone <repository-url>
cd mcp_server_research

# Set up virtual environment
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt
```

### Running the Demo
```bash
cd src/demo
python simple_mcp_server.py
```

## Demo Description
The simple MCP server demo implements a basic message coordination protocol server that:
1. Receives messages from clients
2. Processes messages according to MCP specifications
3. Routes messages to appropriate destinations
4. Provides a simple web interface for monitoring