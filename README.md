# hapi-auth-jwt2 *example*

A ***functional example*** Hapi.js app demonstrating
[***hapi-auth-jwt2***](https://github.com/dwyl/hapi-auth-jwt2) authentication
using **Redis** with ***tests***!

[![Build Status](https://travis-ci.org/dwyl/hapi-auth-jwt2-example.svg)](https://travis-ci.org/dwyl/hapi-auth-jwt2-example)
[![Test Coverage](https://codeclimate.com/github/dwyl/hapi-auth-jwt2-example/badges/coverage.svg)](https://codeclimate.com/github/dwyl/hapi-auth-jwt2-example/coverage)
[![Code Climate](https://codeclimate.com/github/dwyl/hapi-auth-jwt2-example/badges/gpa.svg)](https://codeclimate.com/github/dwyl/hapi-auth-jwt2-example)
[![bitHound Score](https://www.bithound.io/github/dwyl/hapi-auth-jwt2-example/badges/score.svg)](https://www.bithound.io/github/dwyl/hapi-auth-jwt2-example)
[![Dependency Status](https://david-dm.org/dwyl/hapi-auth-jwt2-example.svg)](https://david-dm.org/dwyl/hapi-auth-jwt2-example)

[![devDependency Status](https://david-dm.org/dwyl/hapi-auth-jwt2-example/dev-status.svg)](https://david-dm.org/dwyl/hapi-auth-jwt2-example#info=devDependencies)
[![Node.js Version](https://img.shields.io/node/v/hapi-auth-jwt2.svg?style=flat "Node.js 10 & 12 and io.js latest both supported")](http://nodejs.org/download/)
[![NPM Version](https://badge.fury.io/js/hapi-auth-jwt2.svg?style=flat)](https://npmjs.org/package/hapi-auth-jwt2)
[![HAPI 10.0.0](http://img.shields.io/badge/hapi-10.0.0-brightgreen.svg "Latest Hapi.js")](http://hapijs.com)

## Run it Yourself!

Clone this repo so you can play with it locally:

```sh
https://github.com/dwyl/hapi-auth-jwt2-example.git && cd hapi-auth-jwt2-example
```

Install the NPM dependencies:

```sh
npm install
```


## Environment Variables

To run this you will ***need*** to set an [**environment variable**](https://github.com/dwyl/learn-environment-variables) for your
**JWT_SECRET** and (Server TCP) **PORT**.  
You can then either use a ***local*** **Redis** Server ***or*** a **RedisCloud** instance (*your choice, both work!*).  
for RedisCloud you will need to set a **REDISCLOUD_URL** environment variable.
```
export JWT_SECRET=ItsNoSecretBecauseYouToldEverybody
export PORT=8000
# OPTIONAL if you are using RedisCloud:
export REDISCLOUD_URL=redis://rediscloud:PASSWORD@pub-redis-15721.eu-west-1-2.1.ec2.garantiadata.com:15721
```

## Test everything is working on your local machine

Run the tests by executing the following command in your terminal:

```sh
npm test
```

You should expect to see the following when the tests conclude:

![tests pass](https://cloud.githubusercontent.com/assets/194400/9975267/03edc492-5eae-11e5-93bc-a762e1298985.png)

If you are seeing any errors, please get on the [chat](https://gitter.im/dwyl/chat) and let us know (*we are here to help!*)


## Run the app

```sh
npm start
```

**Note**: you will need to set up your own Redis to use the code in this example in your project. if you're new to Redis check out our quick start guide: https://github.com/docdis/learn-redis


If you have ***any questions***, please ask! [![Join the chat at https://gitter.im/dwyl/chat](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/dwyl/chat/?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)  we are here to help!

If you find this guide/example *useful* please :star: the GitHub repository
(*so we know what we need to make more of...*)
