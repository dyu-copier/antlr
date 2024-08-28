Copier template for generating Python Parser package using Antlr.

Usage:
```
pipx install pdm
copier copy gh:git@github.com:dyu-copier/antlr.git <parserName>
cd parserName
``
edit

1. grammar/parserName.g4
2. src/parserName/cli.py
3. src/parserName/parserName.py

```
pdm install
parserName parserName <inputfile> <outputfile>
```
