# Building and Deploying a Web App using Flask
Basic Flask application that includes math fucntions and deploy it on a Web interface.


# Prerequisites
## Setup Python Project using UV

1. Install UV, a Python project manager
2. Install Python version and create project

```bash
uv python install <VERSION> --path <PATH TO INSTALL>
uv init <NAME OF PROJECT>
```

3. Create Environment
```bash
uv venv --python 3.13
```

4. Activate Environment
```bash
.venv\Scripts\activate
```

5. Add packages
```bash
uv add <PACKAGE NAME>	
```

6. Run Python script:
```bash
uv run <PYTHON SCRIPT NAME>
```

To check that the package added have the correct version and dependencies:

```bash
uv sync
```

Remove package:
```bash
uv remove <PACKAGE NAME>
```


## Install dependencies from pyproject.toml

```bash
uv pip install -r pyproject.toml --all-extras
```

# Running Flask Application
After installing the dependencies, the Flask application can be run. The Flask application can be executed using the following command:


```bash
uv run server.py
```