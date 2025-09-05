# Email Agent - Ambient Agents with LangGraph

A comprehensive implementation of ambient email agents using LangGraph, demonstrating advanced agent architectures with human-in-the-loop capabilities, memory systems, and production deployment patterns.

## Overview

This project implements an intelligent email assistant agent using LangGraph, capable of handling complex email workflows with features like tool calling, evaluations, human-in-the-loop interactions, and persistent memory. The agent is built following best practices for production deployment on the LangGraph Platform.

## Features

- **Intelligent Email Processing**: Automated email understanding and response generation
- **Tool Integration**: Extensible tool system for agent actions
- **Human-in-the-Loop**: Interactive workflows with human approval steps
- **Memory Management**: Persistent conversation and context memory
- **Production Ready**: Deployable on LangGraph Platform with LangGraph Studio support
- **Comprehensive Testing**: Built-in evaluation framework for agent performance

## Project Structure

```
email_agent/
├── notebooks/           # Jupyter notebooks for tutorials
│   ├── langgraph_101.ipynb
│   ├── agent.ipynb
│   ├── evaluation.ipynb
│   ├── hitl.ipynb
│   └── memory.ipynb
├── src/
│   └── email_assistant/  # Core agent implementation
├── tests/              # Test suite and evaluations
│   └── test_tools.py
└── README.md
```

## Getting Started

### Prerequisites

- Python 3.8+
- LangGraph
- LangChain
- Jupyter (for notebooks)

### Installation

```bash
# Clone the repository
git clone https://github.com/langchain-ai/agents-from-scratch.git
cd email_agent

# Install dependencies
pip install -r requirements.txt
```

### Quick Start

1. **Basic LangGraph Introduction**:
   ```bash
   jupyter notebook notebooks/langgraph_101.ipynb
   ```

2. **Run the Email Assistant**:
   ```python
   from src.email_assistant import EmailAgent
   
   agent = EmailAgent()
   response = agent.process_email(email_content)
   ```

## Course Modules

### 1. LangGraph 101
Introduction to LangGraph fundamentals and core concepts.

- **Notebook**: [`langgraph_101.ipynb`](https://github.com/langchain-ai/agents-from-scratch/blob/main/notebooks/langgraph_101.ipynb)
- **Resources**: [Course Slides (PDF)](https://files.cdn.thinkific.com/file_uploads/967498/attachments/b9a/35b/890/Building_Ambient_Agents_with_LangGraph_-_LangGraph_101.pdf)
- **LangGraph Studio**: `src/email_assistant`

### 2. Building Agents
Learn to construct sophisticated agent architectures.

- **Notebook**: [`agent.ipynb`](https://github.com/langchain-ai/agents-from-scratch/blob/main/notebooks/agent.ipynb)
- **Resources**: [Course Slides (PDF)](https://files.cdn.thinkific.com/file_uploads/967498/attachments/5f6/a6b/958/Building_Ambient_Agents_with_LangGraph_-_Building_Agents___Evaluations.pdf)
- **LangGraph Studio**: `src/email_assistant`

### 3. Agent Evaluations
Comprehensive evaluation framework for testing agent performance.

- **Notebook**: [`evaluation.ipynb`](https://github.com/langchain-ai/agents-from-scratch/blob/main/notebooks/evaluation.ipynb)
- **Test Suite**: [`tests/test_tools.py`](https://github.com/langchain-ai/agents-from-scratch/tree/main/tests)
- **Resources**: [Course Slides (PDF)](https://files.cdn.thinkific.com/file_uploads/967498/attachments/5f6/a6b/958/Building_Ambient_Agents_with_LangGraph_-_Building_Agents___Evaluations.pdf)

### 4. Human-in-the-Loop (HITL)
Implement interactive workflows with human approval and feedback mechanisms.

- **Notebook**: [`hitl.ipynb`](https://github.com/langchain-ai/agents-from-scratch/blob/main/notebooks/hitl.ipynb)
- **LangGraph Studio**: `src/email_assistant`

### 5. Memory Systems
Build persistent memory and context management for agents.

- **Notebook**: [`memory.ipynb`](https://github.com/langchain-ai/agents-from-scratch/blob/main/notebooks/memory.ipynb)
- **LangGraph Studio**: `src/email_assistant`

### 6. Deployment
Production deployment strategies using LangGraph Platform.

- **Documentation**: 
  - [LangGraph Platform Deployment Guide](https://langchain-ai.github.io/langgraph/tutorials/deployment/)
  - [LangGraph Platform Concepts](https://langchain-ai.github.io/langgraph/concepts/langgraph_platform/)
- **LangGraph Studio**: `src/email_assistant`

## Running Tests

```bash
# Run all tests
pytest tests/

# Run specific test file
pytest tests/test_tools.py

# Run with coverage
pytest --cov=src tests/
```

## LangGraph Studio

To use with LangGraph Studio, open the `src/email_assistant` directory in the Studio application for visual graph development and debugging.

## Documentation

- [Full Course Content](https://academy.langchain.com/courses/take/ambient-agents/lessons/66147171-course-overview)
- [LangGraph Documentation](https://langchain-ai.github.io/langgraph/)
- [LangChain Documentation](https://python.langchain.com/)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is part of the LangChain educational materials. Please refer to the original repository for license information.

## Support

For questions and support, please refer to:
- [LangChain Discord](https://discord.gg/langchain)
- [GitHub Issues](https://github.com/langchain-ai/agents-from-scratch/issues)

## Acknowledgments

This project is based on the "Building Ambient Agents with LangGraph" course from LangChain Academy.



