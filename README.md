# Economiza AI

Aplicativo de comparação de preços com painel web, API Python e recursos de IA.

## Executar localmente

```bash
pip install -r requirements.txt
python servidor_precos.py
```

Depois abra o endereço exibido pelo servidor.

## Publicar no Render

- Runtime: Python
- Build Command: `pip install -r requirements.txt`
- Start Command: `python servidor_precos.py`
- Health Check Path: `/api/health`

O servidor usa automaticamente a variável `PORT` fornecida pelo Render.
