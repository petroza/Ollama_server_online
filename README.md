# Ollama Server Online

Self-hosted web UI and worker bridge for running Ollama models from a browser.

## Features

- PHP web UI
- first-run installer
- chat page for Ollama models
- model manager
- worker bridge
- agent page for browser automation tests
- local SQLite database created on the server

## Clean upload

Before publishing I removed local runtime data, the real settings file, the database, private credentials and generated archives.

Run install.php on every deployment and create a fresh local password and local API value.

## Files

- AI.html and AI.html.js
- agent.html and agent.html.js
- api.php
- config.php
- install.php
- worker.py
- worker_agent.py
- worker_config.json
- agent_config.json

## License

MIT for the application wrapper. Third-party tools and models keep their own licenses.
