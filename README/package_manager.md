### ----------- uv package manager -------------

1. install uv package manager
2. uv init - initialise uv within same project directory
3. uv venv - create virtual environment,although 'uv init' create .venv/
4. uv add  - install python packages
5. uv run  - run the python file 
6. uv pip list - list all installed package
6. uv run uvicorn app.main:app --reload   - can run the project


### ---------------- uvicorn ASGI server --------
1. uvicorn app.main:app == run the project
2. uvicorn app.main:app --reload  == run with reload the changed file
