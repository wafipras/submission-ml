FROM node:20

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY . .

ENV PORT=3000

ENV MODEL_URL=https://storage.googleapis.com/model-storage99/model-in-prod/submissions-model/model.json

CMD ["npm" , "start"]