# Nova CLI

CLI local para SHA-256 e resumo de JSON. Sem rede, sem credenciais.

```bash
python -m venv .venv
.venv/Scripts/activate
pip install -e ".[dev]"
nova-cli hash examples/sample.json
nova-cli json examples/sample.json
pytest -q
```
