FROM node:alpine

COPY . /app

WORKDIR /app

RUN npm install && npm run build

EXPOSE 3000

CMD ["npm","start"]