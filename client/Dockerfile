FROM node:slim
WORKDIR /usr/src/app/client
COPY ./package*.json ./
RUN npm i   
COPY . .
EXPOSE 5173
CMD ["npm", "run", "dev"]