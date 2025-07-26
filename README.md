# MegaLinter Custom Flavor

python-light

## Embedded linters

  - PYTHON_BANDIT
  - PYTHON_BLACK
  - PYTHON_FLAKE8
  - PYTHON_ISORT
  - PYTHON_MYPY
  - PYTHON_PYLINT
  - PYTHON_PYRIGHT
  - PYTHON_RUFF
  - PYTHON_RUFF_FORMAT

## Generated docker image

ghcr.io/nvuillam/megalinter-custom-flavor-python-light/megalinter-custom-flavor:latest

## How to generate the flavor

Create a GitHub release on your repo, it will generate and publish your custom flavor using the MegaLinter custom Flavor Builder matching the tag name of your release (example: `9.0.0`)

You can also generate a custom flavor using MegaLinter Custom Flavor by pushing on any branch or manually run the workflow `megalinter-custom-flavor-builder.yml`.