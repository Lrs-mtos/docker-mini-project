#ele pega o latest quando colocamos o nome normal
FROM node

WORKDIR /src

COPY package*.json .

RUN npm install

COPY . .

EXPOSE 3000

ENTRYPOINT ["node", "app.js"]