<p align="center">
  <img src="https://docs.nestjs.com/assets/logo-small.svg" width="150px" height="150px"/>
</p>

## NestJS Zero to Hero - Task Management Application

This application is provided as-is, as a part of the [NestJS Zero to Hero course by Ariel Weinberger (Udemy)](https://codingly.cc/32wqFL3).


## CREATE MIGRAION

To automtatically run migrations assuming appmodules migrations run is set to true
- npx typeorm migration:generate -n UserTaksTable -d src/migrations
- npm run build
