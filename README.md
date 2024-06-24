
## Quickstart

Follow these steps to quickly set up and run the ChatGPT Retrieval Plugin:

1. Install Python 3.10, if not already installed.
2. Clone the repository: `git clone https://github.com/openai/chatgpt-retrieval-plugin.git`
3. Navigate to the cloned repository directory: `cd /path/to/chatgpt-retrieval-plugin`
4. Install poetry: `pip install poetry`
5. Create a new virtual environment with Python 3.10: `poetry env use python3.10`
6. Activate the virtual environment: `poetry shell`
7. Install app dependencies: `poetry install`
8. Set the required environment variables:

   ```
   export DATASTORE=weaviate
   export BEARER_TOKEN=
   # Do you guys have your own key?
   export OPENAI_API_KEY=<your_openai_api_key>
   <Add the environment variables for your chosen vector DB here>
   ```

9. Run the API locally: `poetry run start`
10. Access the API documentation at `http://0.0.0.0:8000/docs` and test the API endpoints (make sure to add your bearer token).

