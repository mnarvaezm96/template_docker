FROM node:20.6.1

WORKDIR /usr/src/project

RUN npm install -g create-react-app

RUN create-react-app prueba_react

EXPOSE 3000

RUN cd prueba_react

CMD ["npm","run","start"]