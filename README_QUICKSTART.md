# Quickstart – diamond-setup

**Installiere sofort:**

```bash
pip install diamond-setup
# oder für Entwicklung:
pip install -e ".[dev]"
# empfohlen: mit uv
uv add diamond-setup
```

**Minimal-Beispiel (läuft in < 10 Sekunden):**

```bash
# Neues Python-Projekt scaffolden
diamond new my-project

# Mit Preset
diamond new my-project --preset science

# Vorhandenes Verzeichnis validieren
diamond validate .
```

**Python-API:**

```python
from diamond_setup import scaffold

scaffold("my-project", preset="default")
```

**Weiter:**

- Vollständige Docs → `docs/` oder MkDocs-Site
- Verfügbare Presets → `diamond presets`
- Zitieren → siehe `CITATION.cff` oder Zenodo-DOI

**Contributing**

Siehe `CONTRIBUTING.md` – wir lieben fraktale PRs!
