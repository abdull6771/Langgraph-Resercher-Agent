# AI-Powered Research Assistant

Here’s a basic project starter template for your AI-Powered Research Assistant using LangGraph. This setup includes a multi-agent system with a Planner Agent, Retriever Agent, Critic Agent, and Writer Agent. The framework is designed for expansion, allowing you to integrate additional capabilities later.

## Project Breakdown

### 🔹 Agents:
- **Planner**: Breaks down the research query into structured objectives.
- **Retriever**: Finds relevant sources based on the research plan.
- **Critic**: Analyzes credibility and biases in sources.
- **Writer**: Summarizes findings into a structured research report.

### 🔹 Workflow Execution:
- Uses LangGraph to define the agent workflow.

## Features
- **Multi-Agent System**: A structured approach to research assistance.
- **Gradio UI**: A user-friendly interface for easy interaction.
- **Expandable Framework**: Allows for future enhancements and new agents.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/abdull6771/Langgraph-Resercher-Agent.git
   cd Langgraph-Resercher-Agent
   ```
2. **Create a virtual environment (optional but recommended):**
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use: venv\Scripts\activate
   ```
3. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

## Usage

Run the Gradio application:
```bash
python app.py
```

After running the script, a local URL (or public shareable link if using Google Colab) will be generated. Open the link in your browser to use the AI-Powered Research Assistant.

## Contributing

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-branch
   ```
3. Make your changes and commit:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push to your fork and submit a Pull Request.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any issues or inquiries, please open an issue on GitHub or contact the repository owner.

