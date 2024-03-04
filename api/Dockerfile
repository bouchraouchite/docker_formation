FROM node:14-alpine


WORKDIR /app

COPY *.json .
RUN  npm install 
COPY . .

EXPOSE  4000 


CMD ["npm","run","dev"]

