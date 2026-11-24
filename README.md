# chamados-ads

Filipi Emanuel Pinto Teixeira - ADS UFCA

## Objetivo

Criar uma API para chamados de TI.

## Instalação das dependências

Com o uv instalado, rode no terminal:

```bash
uv sync --locked
```

## Como executar

```bash
uv run flask --app main run
```

A aplicação ficará disponível em `http://127.0.0.1:5000`.

## Rota inicial

Acesse `http://127.0.0.1:5000/` no navegador ou com curl:

```bash
curl http://127.0.0.1:5000/
```

Resposta esperada:

```json
{"mensagem": "API de chamados funcionando"}
```
