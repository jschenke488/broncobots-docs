# broncobots-docs

A repository containing all public-facing documentation for FRC Team 1987 Broncobots.

## Installing

It is recommended to use a Python Virtual Environment ([venv](https://docs.python.org/3/library/venv.html)).  If using [VSCode](https://vscode.dev/), then follow [this guide](https://code.visualstudio.com/docs/python/environments).

If you have [Docker](https://docker.com) and [VSCode](https://vscode.dev/) installed, then feel free to use the [development container](https://containers.dev/).

`pip install -r requirements.txt`

## Commands

* `mkdocs new [dir-name]` - Create a new project.
* `mkdocs serve` - Start the live-reloading docs server.
* `mkdocs build` - Build the documentation site.
* `mkdocs -h` - Print help message and exit.

## Project layout

```
  mkdocs.yml    # The configuration file.
  docs/
      index.md  # The documentation homepage.
      ...       # Other markdown pages, images and other files.
```