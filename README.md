<p align="center">
<a href="https://rocketseat.com.br/bootcamp" alt="Bootcamp Rocketseat">
  <img src="https://skylab.rocketseat.com.br/api/files/1560759053914.svg" height="120px"></a></p>

# Rocketseat GoStack - Backend GoBarber

https://rocketseat.com.br/bootcamp

## Description

Complete NodeJs API for the Rocketseat Bootcamp GoStack GoBarber application.

## Features

- JWT Authentication
- Pagination
- Database Postgres
- Database MongoDB
- Queue with Redis for sendind emails.

## Installing

### Create docker container Postgres

`docker run --name database -e POSTGRES_PASSWORD=docker -p 5432:5432 -d`

### Create docker container MongoDB

`docker run --name mongobarber -p 27017:27017 -d -t mongo`

### Create docker container Redis

`docker run --name redisbarber -p 6379:6379 -d -t redis:alpine`

### Installing dependencies

`cd gostack-backend-gobarber`
`yarn`

### Running migrations Database

`yarn sequelize db:migrate`

### Setup .env file

Rename the file `.env-example` to `.env` !
Edit the file with your informations!

## Running

`yarn dev`

## Author

- Lindemberg Nunes de Castro

## License

MIT
