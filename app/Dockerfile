FROM node:16
WORKDIR /app-node
EXPOSE 3000
COPY . .
RUN echo "Arquivos copiados com sucesso"
RUN npm install
ENTRYPOINT node app.js