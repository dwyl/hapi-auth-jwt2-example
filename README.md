# hapi-auth-jwt2 *example*

[![Build Status](https://travis-ci.org/dwyl/hapi-auth-jwt2-example.svg)](https://travis-ci.org/dwyl/hapi-auth-jwt2-example)
[![Code Climate](https://codeclimate.com/github/dwyl/hapi-auth-jwt2-example/badges/gpa.svg)](https://codeclimate.com/github/dwyl/hapi-auth-jwt2-example)
[![Test Coverage](https://codeclimate.com/github/dwyl/hapi-auth-jwt2-example/badges/coverage.svg)](https://codeclimate.com/github/dwyl/hapi-auth-jwt2-example/coverage)
[![bitHound Score](https://www.bithound.io/github/dwyl/hapi-auth-jwt2-example/badges/score.svg)](https://www.bithound.io/github/dwyl/hapi-auth-jwt2-example)

A ***functional example*** Hapi.js app demonstrating
[***hapi-auth-jwt2***](https://github.com/dwyl/hapi-auth-jwt2) authentication
using **Redis** (hosted on Heroku) with ***tests***!

## Environment Variables

To run this you will need to add an environment variable for your **JWT_SECRET** and **REDISCLOUD_URL**:
```
export JWT_SECRET=ItsNoSecretBecauseYouToldEverybody
export REDISCLOUD_URL=redis://rediscloud:OhEJvSgna@pub-redis-10689.eu-west-1-2.1.ec2.garantidata.com:10689
```
