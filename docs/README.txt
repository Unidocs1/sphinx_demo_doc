If you wanted to locally, test, you could:

1. Add a ./source/conf.py -> You could copy the one in ./source and remove the `sphinx_repo_manager` extension
2. Add a ./source/index.rst with a toctree directive to link to other docs
3. In this dir, `make html` to sphinx-build
