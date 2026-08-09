# Dockerfile para API Node.js (Express + PostgreSQL)
FROM node:20-alpine

WORKDIR /app

COPY package*.json ./
RUN npm install --only=production

COPY . .

EXPOSE 3001

CMD ["npm", "start"]
