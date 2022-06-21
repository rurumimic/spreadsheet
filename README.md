# Spreadsheet

## Run

```bash
python -m spreadsheet

Hello, World!
```

### Jupyter Lab

```bash
jupyter lab
```

#### Formatter

Jupyter Lab Toolbar → Settings → Advanced Settings Editor → Jupyterlab Code Formatter → JSON Settings Editor

```json
{
    "preferences": {
        "default_formatter": {
            "python": "black",
            "r": "formatR"
        }
    },
    "black": {
        "line_length": 88,
        "string_normalization": true
    },
    "formatOnSave": true,
}
```

## Test

```bash
pytest
```
