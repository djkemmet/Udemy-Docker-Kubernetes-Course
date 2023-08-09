FROM node:14

WORKDIR /app

# Copy Package.json into the workdir /app
COPY package.json .

RUN npm install

COPY . .

EXPOSE 80

VOLUME [ "/app/feedback" ]

CMD ["node", "server.js"]

