
# natasha-examples ![CI](https://github.com/natasha/natasha-examples/actions/workflows/test.yml/badge.svg)

A set of Jupyter notebooks with examples of [Natasha](https://github.com/natasha/natasha) usage.

## Development

Dev env

```bash
python -m venv ~/.venvs/natasha-natasha-examples
source ~/.venvs/natasha-natasha-examples/bin/activate

pip install -r requirements/dev.txt
python -m ipykernel install --user --name natasha-natasha-examples
```

Run notebooks

```
make exec-notebooks
```

