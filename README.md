# Spreadsheet

- [Open Data](data/README.md)
  - 서울시 세종문화회관 공연 및 전시 정보

---

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
        }
    },
    "black": {
        "line_length": 88,
        "string_normalization": true
    },
    "formatOnSave": true,
    "suppressFormatterErrors": false
}
```

## Test

```bash
pytest
```
