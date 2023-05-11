# Getting Started with express Nodejs app

## How to create model
```
sequelize model:create --name Book --attributes title:string,price:string,description:string
```

## How to provide DB migration
```
sequelize db:migrate
```

## Before DB migration, you will need to export the DATABASE_URL first.

```
export DATABASE_URL=postgres://cfvofggj:x536xDaah8OPfjW1ak95XWT_t06HrkJa@abul.db.elephantsql.com/cfvofggj
```


## If port is busy - how to check 

```
sudo lsof -i :3000
```

## Link to Elephant SQL schema

https://api.elephantsql.com/console/20eb208d-d650-4af1-8463-d58caf5e85b1/browser?


