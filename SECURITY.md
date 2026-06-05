# Security notes

This repository must never contain live credentials.

Removed before upload:

- real API token from app_settings.json
- password hash from app_settings.json
- db.sqlite
- packaged ZIP installer

On every deployment run install.php and create a fresh password. The installer writes a new local app_settings.json with a new generated API token.

Workers should receive their token through the generated worker config, environment variables, or a local untracked config file.
