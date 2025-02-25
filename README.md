# MCP Server Research Project

This project contains research and demos related to MCP (Message Coordination Protocol) server implementation.

## Overview

The Message Coordination Protocol (MCP) provides a standardized way for distributed systems to communicate and coordinate actions. This repository includes a reference implementation and demonstrations of the protocol in action.

## Project Structure

```
mcp_server_research/
├── docs/          # Documentation files
├── src/           # Source code
│   └── demo/      # Demo implementations
└── requirements.txt
```

## Getting Started

### Prerequisites

- Python 3.8+
- Flask
- Requests

### Installation

```bash
# Clone the repository
git clone https://github.com/ckz/mcp_server_research.git
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

Then visit http://localhost:5000 to view the dashboard.

## Demo Features

The simple MCP server demo implements a basic message coordination protocol server that:

- Registers and tracks connected clients
- Processes various message types (heartbeat, data, command)
- Routes messages to appropriate destinations
- Provides a web dashboard for monitoring system activity
- Maintains an in-memory message history

## License

MIT

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.