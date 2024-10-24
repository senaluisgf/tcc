FROM node:20-alpine

WORKDIR /app
# RUN npm install -g npm@10.9.0

COPY package.json .
COPY . .
RUN npm install

CMD ["npm", "run", "start:dev"]