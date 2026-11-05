# Testes Flask no GitHub Actions

Projeto Flask com testes automatizados usando Pytest.

## Testes

Os testes rodam em push, pull request, manualmente e a cada seis horas.

- Fluxo: `.github/workflows/testes.yml`
- Codigo: `app.py`
- Testes: `tests/test_app.py`

Para testar localmente:

```bash
pip install -r requirements.txt
python -m pytest -v
```
