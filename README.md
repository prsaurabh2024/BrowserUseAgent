# Browser-Use Agent

This project contains a Python-based agent that uses the `browser_use` library to interact with web browsers and perform various tasks.
Fully customizable and extensible. 

## Demo




## Project Structure

- `Agent.py`: Main script to run the agent.
- `config.py`: Configuration file containing API keys & path.
- `controllers.py`: Contains controller actions for the agent. (Functional calling)
- `credentials.py`: Stores login credentials for various websites.
- `entity.py`: Defines Pydantic models Entities for data validation.
- `prompts.py`: Contains User and System prompts.
- `requirements.txt`: Lists the dependencies required for the project.
- `agent_report.pdf`: Generated PDF with details extracted by the Agent. (Info - generated sample)
- `agent_hitory.gif`: Action taken by Agent (one sample).
 

## Setup

1. Clone the repository:
   ```bash
   git clone https://github.com/username/repository.git
   cd Browser-Use
   ```

2. Create a virtual environment and activate it:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On Windows use `venv\Scripts\activate`
   ```

3. Install the dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Running the Agent

To run the agent, execute the following command:
```bash
python Agent.py
```

## Configuration

Update the `config.py` file with your OpenAI API keys.

## License

This project is licensed under the MIT License.
