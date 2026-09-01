# AGENTS.md — odoo_info

## What this is
Odoo module that lists and displays most Odoo ERP settings and parameters. A simple info app for inspecting Odoo configuration.

## Stack
- Python (Odoo module)
- XML (views/templates)
- CSV (security access rules)

## Build
```bash
# Install as Odoo module
# Copy directory to Odoo addons path, update module list, install via Odoo UI
```

## Run
Install via Odoo Apps dashboard. Depends on `base` module.

## Structure
- `__manifest__.py` — Odoo module manifest (v1.0, AGPL-3)
- `models/models.py` — data models
- `views/views.xml` — UI views
- `views/templates.xml` — website templates
- `controllers/controllers.py` — HTTP controllers
- `security/ir.model.access.csv` — access control rules
- `demo/demo.xml` — demo data

## Conventions
- No comments in code unless asked.
- Verify: `python -m py_compile <file>`
