FROM node:23-alpine

WORKDIR /app

COPY . .

RUN npm install --upgradable npm

EXPOSE 5173

CMD ["npm","run","dev","--","--host"]
