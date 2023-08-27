# Ansible repo for testing
Ansible repo for testing things I learned so I can refer to them

## Playbooks
- **pb-error-recovery.yml:** Use blocks to handle errors.
- **pb-filters-plugins.yml:** Fun with filters and lookup plugins
- **pb-handlers.yml:** Use handlers
- **pb-long-strings.yml:** Print out strings to see the effect of different ways to break lines.
- **pb-loops.yml:** Fun with loops, ya'll
- **pb-secrets.yml:** Load an encrypted file and output a var's value via `debug`. Call via `ansible-playbook pb-secrets.yml --vault-password-file vault_key`.
- **pb-templating.yml:** Fun with Jinja2 templates
