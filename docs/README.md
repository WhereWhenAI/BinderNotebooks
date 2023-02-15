# How to Docs

## Building the Docs

```
# go repo root folder
cd NavAbilitySDK.py

# Install required Python dependencies (Sphinx etc.)
pip install -r docs/requirements.txt

# Run Jupyter Book
jupyter-book build docs/

# View the docs with for instance firefox
firefox docs/_build/html/index.html
```

## Resources

This documentation folder is based on work from:
- https://github.com/readthedocs-examples/example-jupyter-book

With auto docstring extension:
- https://jupyterbook.org/en/stable/advanced/developers.html?highlight=docstrings#api-reference-from-docstrings
- AND the workaround, https://myst-parser.readthedocs.io/en/latest/faq/index.html#howto-autodoc


