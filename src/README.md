# Passo a passo de Execução

## Setup do Ollama (5 minutos)

```bash
# 1. Instalar Ollama (ollama.com)

# 2. Baixar um modelo leve
ollama pull gpt-oss

# 3. Testar se funciona
ollama run gpt-oss "Olá!"

```

## Código Completo

Todo o código-fonte está no arquivo `app.py`.

## Como Rodar
```bash
# 1. Instalar dependências
pip install -r requirements.txt

# 2. Garantir que Ollama está rodando
ollama serve

# 3. Rodar a aplicação
streamlit run app.py
```

## Evidência de Execução

<img width="702" height="811" alt="image" src="https://github.com/user-attachments/assets/a7a3bd38-4cbe-4e88-a8ac-8c753b6fb61f" />

