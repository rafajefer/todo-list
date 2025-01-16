FROM node:22

WORKDIR /app

# Instalar curl
# RUN apk add --no-cache curl

# Copiar o código do cliente e o arquivo .env
# COPY client/ . 
# COPY client/.env.sample .env

# Instalar o Vue CLI
RUN npm install -g @vue/cli

# Remover e instalar dependências
# RUN rm -rf node_modules
# RUN npm i

EXPOSE 3000

# Comando para rodar o servidor de desenvolvimento
CMD ["npm", "run", "dev", "--", "--host", "0.0.0.0"]

