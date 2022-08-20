FROM node:14.19.3

WORKDIR /six

COPY package.json .

RUN npm install

COPY . .

EXPOSE 4000

CMD ["npm","start"]
