# Sequelize-Auto For Eggjs
Base on [Sequelize-Auto]('https://github.com/sequelize/sequelize-auto)

**Support typescript option**

## Install
```
npm i egg-sequelize-auto2
```
you also have to install `@types/sequelize` in you eggjs project

```
npm i @types/sequelize
```


## typescript example
In you eggjs project root
```
./node_modules/.bin/egg-sequelize-auto-ts -d shop -h localhost -p 3306 -u root -x 1234 --dialect mysql -o app/model -z -g shopModel
```
`-z` for typescript , `-g shopModel` load model at `ctx.shopModel`

you will get some ts file in app/model 

**Now you can go on with typescript**



