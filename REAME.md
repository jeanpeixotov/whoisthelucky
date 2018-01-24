#WHO IS THE LUCKY 

 an initial state.

### install

* `yarn` - install dependencies

### run in dev

* `yarn run build:watch` - runs babel to transpile the server from es6 to es5 (watch mode)
* `yarn run build:watch:client` - runs webpack to build bundle (watch mode)
* `yarn run start:dev` - in parallel shells it calls `build:watch:client` `build:watch:server` and then runs the app in watch mode, using nodemon

### prod

* `yarn run build` - runs babel to transpile the server from es6 to es5 
* `yarn run build:client` - runs webpack to build bundle
* `yarn run build:prod` - builds both client and server
* `yarn run start` - it calls `build:prod` and then runs the app 