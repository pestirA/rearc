FROM node:18
WORKDIR /quests
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3000
CMD [ "node", "src/000.js" ]