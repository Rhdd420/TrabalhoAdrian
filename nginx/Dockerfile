# Usa a imagem oficial do NGINX
FROM nginx:latest

# Remove configuração padrão
RUN rm /etc/nginx/conf.d/default.conf

# Copia nossa configuração customizada
COPY default.conf /etc/nginx/conf.d/

# Expõe a porta 80 para acesso externo
EXPOSE 80
