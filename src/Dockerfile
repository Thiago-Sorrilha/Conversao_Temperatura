FROM node
WORKDIR /app
COPY package*.json ./ 
## install
RUN npm install 
COPY . .
EXPOSE 8080
CMD ["node", "server.js"]
