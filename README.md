# python-web-tornado-api-cockroachdb-single-node-without-ssl-simple

## Description
Simple web app that serves an api
for a tornado project.

Uses sqlalchemy query a table `dog`.

Remotely tested with *testify*.

## Tech stack
- python
  - tornado
  - sqlalchemy
  - testify
  - requests
- cockroachdb

## Docker stack
- python:latest
- cockroachdb/cockroach:v19.2.4

## To run
`sudo ./install.sh -u`
- [Endpoint at](http://localhost/dog)

## To stop
`sudo ./install.sh -d`

## For help
`sudo ./install.sh -h`

## Credit
- [HTTPServer config](https://phrase.com/blog/posts/tornado-web-framework-i18n/)
- [Code based on](https://www.tornadoweb.org/en/stable/)
- [Sqlalchemy code](https://medium.com/swlh/tornado-and-sqlalchemy-847eecbc0445)