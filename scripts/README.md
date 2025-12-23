# Build Scripts

This directory contains scripts for building and processing data for the ARC Framework documentation.

## `build_risk_register.py`

Converts YAML data files into a consolidated JSON file for the interactive risk register visualization.

### Usage

```bash
# From the repository root
python scripts/build_risk_register.py
```

Or with the virtual environment:

```bash
source .venv/bin/activate
python scripts/build_risk_register.py
```

### What it does

1. Loads YAML files from `arc-risk-register/`:
   - `risks-updated.yaml` - Risk definitions
   - `controls-updated.yaml` - Control definitions
   - `capabilities.yaml` - Capability taxonomy
   - `components.yaml` - System components
   - `design.yaml` - Design elements

2. Merges and enriches the data by:
   - Linking risks to their elements (components, design, capabilities)
   - Attaching full control details to each risk
   - Computing metadata and statistics

3. Outputs consolidated JSON to:
   - `docs/assets/risk_register_data.json`

### When to run

Run this script whenever you update any of the source YAML files to regenerate the JSON data for the interactive risk register.

### Integration with MkDocs

The generated JSON file is consumed by the interactive risk register page at `docs/arc_framework/risk-register.md`. After running this script, rebuild the docs:

```bash
mkdocs build
```

Or for local development:

```bash
mkdocs serve
```
