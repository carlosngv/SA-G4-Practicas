FROM node:14-alpine 

WORKDIR /developer

COPY package*.json ./

ENV PATH /developer/node_modules/.bin:$PATH

RUN npm install 

COPY . . 

EXPOSE 4040

CMD [ "node", "index.js"]
