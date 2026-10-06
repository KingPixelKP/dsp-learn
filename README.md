# DSP Learn

This is a very simple collection of jupyter notebooks documenting my journey of learning digital signal processing.

## Jupyter Setup

This repo uses uv with jupyter all you have todo to have the environment up and running is.

First ensure you have uv [installed](https://docs.astral.sh/uv/getting-started/installation/)

> Run
>
> ``` bash
> uv run ipython kernel install --user --env VIRTUAL_ENV $(pwd)/.venv --name=dsp-learn
> ```
> For extra info on uv and jupyter kernells go [to](https://docs.astral.sh/uv/guides/integration/jupyter/#using-jupyter-from-vs-code).

> [!NOTE]
> If you add any uv packages you must run the kernell install command again
