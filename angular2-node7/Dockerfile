FROM node:7

WORKDIR /app

COPY package*.json ./

RUN npm install

RUN npm install -g @angular/cli

ADD . /app

COPY . .

EXPOSE 4200

ENV NAME New_App

CMD ["ng", "serve", "--host", "0.0.0.0"]

