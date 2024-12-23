FROM node:20

WORKDIR /app

RUN apt-get update -y

COPY . .

RUN npm i

#RUN npm install vite

EXPOSE 5173

CMD ["npm","run","dev","--","--host"]
