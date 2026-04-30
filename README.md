# W2D4 Python for Low Code

## How to run

Open the notebooks in Jupyter and run the setup cell:

```python
%pip install -r requirements.txt
```

If an OpenAI API key is needed, set `OPENAI_API_KEY` in the environment before running the solution notebooks.

## Files

- [lab_api_json_validation_template_codex.ipynb](./lab_api_json_validation_template_codex.ipynb)  
  Version of the JSON validation lab with instructions and empty code cells.

- [lab_api_json_validation_solution_codex.ipynb](./lab_api_json_validation_solution_codex.ipynb)  
  Completed version of the JSON validation lab.

- [lab_api_json_validation_solution_low_code_refactored_codex.ipynb](./lab_api_json_validation_solution_low_code_refactored_codex.ipynb)  
  Refactored version with helper functions, clearer structure, error handling, retry logic, and logging.

- [requirements.txt](./requirements.txt)  
  Required Python dependencies.

- [data](./data)  
  Sample/generated JSON input and output files used by the notebooks.

- [logs](./logs)  
  Generated log files from the refactored notebook.

- [.gitignore](./.gitignore)  
  Ignores generated files inside `data/` and `logs/`.
