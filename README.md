# Crewai - Resume Agent

This repository contains AI-Powered Resume Tailor & Interview Prep application.

## Prerequisites

In this project I have used `uv` to install, please feel free to use any package manager to install.

## Prerequisites - If LLM is running in Local

Install Ollama

### Install uv (Python package manager):

`curl -LsSf https://astral.sh/uv/install.sh | sh`

### Verify the installation:

`uv --version`

## Environment Setup

### Create a Virual Environment

`uv venv`

#### Activate the environment

`source ./venv/bin/activate`

#### Install Dependencies

`uv sync`

## Running the Application

Launch the Streamlit application:
`uv run streamlit run streamlit-app.py`
