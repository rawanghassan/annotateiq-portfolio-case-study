# Security and Secret Handling

This public showcase must not contain authentication material or private execution configuration.

Before every GitHub push, verify that the repository does **not** contain:

- Telegram bot tokens
- API keys or access tokens
- Passwords or credentials
- `.env` files
- Private URLs containing secrets
- Personal chat IDs or account identifiers
- n8n credential exports
- Power BI connection secrets

If a secret is ever committed, deleting the file is not sufficient. Rotate or revoke the secret immediately and remove it from Git history before republishing.
