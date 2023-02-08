# Creating a poetry environment to use conversions_jsteyn


## Creating a poetry environment
- `poetry init` (in our case pyproject.toml already exists)
- `poetry source add testpypi https://test.pypi.org/simple/` (to add the testpypi repository)
- poetry add conversions_jsteyn
- Run poetry show:
> ```
> $ poetry show
> conversions-jsteyn 0.0.1 A collection of conversion utility functions
> ```
- `poetry lock` (to lock versions)
- `poetry run python temp.py` (to run the Python script)
