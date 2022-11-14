FROM node:14-alpine
WORKDIR /todolist
EXPOSE 3000
ADD node_modules.tar.gz .
COPY src/ ./src
COPY public/ ./public
COPY .env .
CMD ["npm", "start"]