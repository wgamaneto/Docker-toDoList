FROM node:14
WORKDIR /todolist
EXPOSE 3001
ADD node_modules.tar.gz .
COPY package-lock.json .
COPY package.json .
COPY src/ ./src
CMD ["npm", "start"]