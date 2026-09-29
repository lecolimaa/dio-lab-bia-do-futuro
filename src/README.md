# Passo a Passo para Execução

## Setup do Ollama

```bash
# 1. Instalar Ollama (ollama.com)
# 2. Baixar um modelo leve
ollama pull gpt-oss:20b 

# 3. Testar se funciona
ollama run gpt-oss:20b "Olá!"

```
## Código Completo

Todo o código-fonte está no arquivo `app.py`.

## Como Rodar

```bash
# Instalar dependências
pip install streamlit pandas requests

# 2. Garantir que o ollama está rodando
ollama serve

# 3. Rodar o app
streamlit run .\src\app.py
```
