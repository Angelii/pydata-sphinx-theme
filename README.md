# 🔥 activate env

```
conda env list
conda activate xx(your custom python env)
```

# ⛏️ run project
```
# ensure install webpack package etc.
nox -s docs-live 
```

# 📦 build project
```
python -m build
pip uninstall pydata_sphinx_theme
pip install dist/...
```