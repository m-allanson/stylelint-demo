Getting started
---------------

- `npm install`
- `npm run start:dev`
- `http://localhost:8080`

Or view the live version at http://stylelint-demo.herokuapp.com/

About
-----

This site is an online demo of [stylelint](https://github.com/stylelint/stylelint).

It consists of two parts:

- A web server that accepts `code` and `config` parameters, passes them to stylelint and then responds with stylelint's output.

- A frontend for creating `code` and `config` blocks, and rendering server responses.

Deployment
----------

Commits to `master` will be tested by [Travis](https://travis-ci.org/stylelint/demo). Successful builds will automatically be deployed to http://stylelint-demo.herokuapp.com.
