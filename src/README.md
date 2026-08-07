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

## Estrutura Sugerida

```
src/
├── app.py              # Aplicação principal (Streamlit)

## Exemplo de requirements.txt

```
streamlit
openai
python-dotenv
```

## Como Rodar

```bash
# Instalar dependências
pip install -r requirements.txt

# Rodar a aplicação
streamlit run app.py
```
