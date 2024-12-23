FROM node:20

WORKDIR /app

EXPOSE 5000

RUN apt-get update -y

COPY . .

RUN npm i

RUN cp .env.sample .env

CMD ["npm","start"]
