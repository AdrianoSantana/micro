FROM node:16-alpine
WORKDIR /app
COPY package*.json ./
RUN npm install
RUN npm install -g nodemon
COPY . .
EXPOSE 5001
CMD ["nodemon", "src/index.js"]
