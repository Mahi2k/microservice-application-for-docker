FROM node:18
WORKDIR /app
COPY . /app
RUN npm install
COPY . .
EXPOSE 3002
CMD ["node", "index.js"]