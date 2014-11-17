hubot-typetalk
==============

A Hubot adapter for typetalk.

[![Build Status](https://travis-ci.org/akiomik/hubot-typetalk.png?branch=master)](https://travis-ci.org/akiomik/hubot-typetalk)
[![Coverage Status](https://coveralls.io/repos/akiomik/hubot-typetalk/badge.png?branch=master)](https://coveralls.io/r/akiomik/hubot-typetalk?branch=master)
[![Dependency Status](https://gemnasium.com/akiomik/hubot-typetalk.png)](https://gemnasium.com/akiomik/hubot-typetalk)
[![NPM version](https://badge.fury.io/js/hubot-typetalk.png)](http://badge.fury.io/js/hubot-typetalk)

## Installation

1. Add `hubot-typetalk` to dependencies in your hubot's `package.json`.
  ```javascript
"dependencies": {
    "hubot-typetalk": "0.0.4"
}
  ```

2. Install `hubot-typetalk`.
  ```sh
npm install
  ```

3. Setup your hubot.
  ```sh
export HUBOT_TYPETALK_CLIENT_ID='DEADBEEF'     # see http://developers.typetalk.in/oauth.html#client
export HUBOT_TYPETALK_CLIENT_SECRET='FACEFEED'
export HUBOT_TYPETALK_ROOMS='2321,2684'        # comma separated
export HUBOT_TYPETALK_API_RATE=100             # request per hour
  ```

4. Run hubot with typetalk adapter.
  ```sh
bin/hubot -a typetalk
  ```

## License

The MIT License. See `LICENSE` file.
