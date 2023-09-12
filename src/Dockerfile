FROM node:18.12.1
WORKDIR /app
COPY package-lock.json
COPY package.json
RUN npm install
COPY . . 
EXPOSE 8080
CMD ["node", "server.js"]
