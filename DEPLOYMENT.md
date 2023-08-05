# Deployment Guide

This guide provides step-by-step instructions for deploying the Sweep AI Junior Developer application.

## Setting Up the Python Environment

1. Install Python 3.10. You can download it from the official Python website.
2. Set up a virtual environment. You can do this using the venv module in Python.
   ```
   python3 -m venv env
   ```
3. Activate the virtual environment.
   ```
   source env/bin/activate
   ```
4. Install the necessary dependencies using Poetry. You can install Poetry using the following command.
   ```
   curl -sSL https://install.python-poetry.org | python3 -
   ```
   Then, install the dependencies.
   ```
   poetry install
   ```

## Configuring External Services

1. Set up API keys for services like Slack and GitHub. You can do this through the respective service's settings or developer console.
2. Configure these services in the application. You can do this by setting the respective environment variables in the `.env` file.

## Running the Application

1. Start the application server.
   ```
   python sweepai/api.py
   ```
2. Access the application through a web browser. The application should be running at `http://localhost:8000`.
