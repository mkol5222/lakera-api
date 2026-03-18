# Lakera API basics


# Prerequisites
```shell

# UV
curl -LsSf https://astral.sh/uv/install.sh | sh

# dotenvx
curl -sfS https://dotenvx.sh | sudo sh
dotenvx help
```

## 2 python

```shell
uv venv
uv pip install click pandas requests fsspec huggingface_hub

uv run 02-with-dataset.py

dotenvx run -- uv run 02-with-dataset.py


```