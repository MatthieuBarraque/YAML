FROM node:12-alpine
WORKDIR /app
COPY . /app
RUN npm install
EXPOSE 80
CMD ["node_modules", "server.js"]