# basic-ai-agent

This repo contains sample code for creating basic agents. It contains the following basic examples:

- [Basic](basic.py): An agent that answers questions about the weather.
- [Generate users](generate_users.py): An agent that generates fake users.
- [React agent](react_agent.py): A react angent from the post [Building a ReAct Agent with Langgraph: A Step-by-Step Guide](https://medium.com/@umang91999/building-a-react-agent-with-langgraph-a-step-by-step-guide-812d02bafefa).

To get started using this project, do the following:

1. Install uv on your local system.
2. Navigate to this project root directory. 
3. Install this project dependencies with command `uv sync`. 
4. Create `.env` file and place the OpenAI API key as variable: `OPENAI_API_KEY=`.
5. Run an agent as `uv run basic.py` (or any other agent that is in this repo).