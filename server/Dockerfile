FROM node

WORKDIR /app

COPY . .
RUN npm ci

COPY . .

EXPOSE 5200
CMD [ "npm", "start"]