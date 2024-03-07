FROM node:alpine

COPY . /app

WORKDIR /app

RUN npm install && npm run build && npm test

EXPOSE 3000

CMD ["npm","start"]