<<<<<<< HEAD
FROM python:3.11-slim

WORKDIR /app

# Copiar primeiro o arquivo de requisitos
COPY app/requirements.txt .

# Instalar as dependências
RUN pip install --no-cache-dir -r requirements.txt

# Copiar o restante do código
COPY app/ .

EXPOSE 5000

CMD ["python", "main.py"]
=======
FROM python:3.11-slim

WORKDIR /app

# Copiar primeiro o arquivo de requisitos
COPY app/requirements.txt .

# Instalar as dependências
RUN pip install --no-cache-dir -r requirements.txt

# Copiar o restante do código
COPY app/ .

EXPOSE 5000

CMD ["python", "main.py"]
>>>>>>> 09865ba (Add files via upload)
