FROM node:14.3

WORKDIR /app

COPY package.json .
RUN npm install

COPY . .

USER node

EXPOSE 8000

CMD ["npm", "run", "start"]