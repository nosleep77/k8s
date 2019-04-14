FROM node:alpine
WORKDIR /usr/app
COPY index.js ./
COPY package.json ./
RUN npm install
CMD ["npm", "start"]
