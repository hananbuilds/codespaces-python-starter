# Codespaces Python Starter

A small Python project built for the MLH Global Hack Week "Code with Codespaces" challenge.

This is a practice project, not a production app. The goal was to actually use GitHub Codespaces end to end: spin up a cloud dev environment, customize it with a dev container, run and modify code inside it, then commit and push straight from the Codespace.

## What it does

Prints two lines confirming the environment is running and picked up the custom dev container config.

```
Hello from GitHub Codespaces!
This environment is configured with a custom dev container.
```

## Structure

```
codespaces-python-starter/
├── .devcontainer/
│   └── devcontainer.json
├── app.py
├── .gitignore
└── README.md
```

## Dev container

`.devcontainer/devcontainer.json` pins the environment to Python 3.12:

```json
{
  "name": "Python Codespaces Starter",
  "image": "mcr.microsoft.com/devcontainers/python:3.12"
}
```

Opening the repo in Codespaces builds this container automatically, so the environment is reproducible instead of depending on whatever happens to be installed locally.

## Run it

```
python app.py
```

## What this demonstrates

- Creating and opening a GitHub Codespace from a repo
- Customizing the environment with a dev container
- Rebuilding the Codespace so the custom config actually takes effect
- Editing and testing code inside the container
- Using Git inside Codespaces — stage, commit, push

## Tech

Python · GitHub Codespaces · Dev Containers · Git
