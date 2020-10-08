# NestJs MySQL TypeORM Sample

This project is sample application that demonstrates storing and receiving data in MySQL database using NestJS framework and TypeORM.

![](https://cdn-images-1.medium.com/max/800/1*zeOv4blDpgcoqTLUvfmbXQ.png)

It's a source code for the following article on the medium:

- https://medium.com/@zoransasko/using-nestjs-mysql-typeorm-in-building-simple-notes-app-5cdbee9712e0

In order to start this sample, please make sure that you specify the right data for establishing MySQL connection (in 'ormconfig.json' file, make sure that 'username', 'password' and 'database' values matches your MySQL server values):
```
{
    "type": "mysql",
    "host": "localhost",
    "port": 3306,
    "username": "root",
    "password": "root",
    "database": "test",
    "entities": ["dist/**/*.entity{.ts,.js}"],
    "synchronize": true
}
```
Then please install all the app depencencies by executing the following command:
```
npm install
```
and you can run the app by executing the following command:
```
npm run start:dev
```
