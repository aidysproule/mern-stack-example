FROM node:20.10.0

EXPOSE 5050

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

CMD ["npm", "run", "start"]