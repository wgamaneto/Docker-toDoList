FROM node:14
WORKDIR /todolist
EXPOSE 3000
ADD node_modules.tar.gz .
COPY package.json .
COPY package-lock.json .
COPY src/ ./src
COPY public/ ./public
COPY .env .
CMD ["npm", "start"]