# Unofficial DeGiro API

This is an unofficial Node.js API client for DeGiro's trading platform. Using this module you can easily automate your orders (buy and sell) and get information about orders, funds or products.

DeGiro is Europe's fastest growing online stockbroker. DeGiro distinguishes itself by offering institutional fees to retail investors.

⚠️  DeGiro could change their API at any moment, if something is not working, please open an issue.

### Install 

```sh
# using npm
npm install --save degiro-api

# using yarn
yarn add degiro-api
```

### Basic example

```js
import * as DeGiro from 'degiro-api'

const degiro = new DeGiro({
  username: 'username',
  pwd: '*****'
})

degiro.login().then(console.log).catch(console.error)
```

### License

MIT

