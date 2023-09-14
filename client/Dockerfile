FROM node:slim
WORKDIR /usr/src/app/client
COPY ./package*.json ./
RUN npm i   
COPY . .
EXPOSE 4000
CMD ["npm", "run", "dev"]