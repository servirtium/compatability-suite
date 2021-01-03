# Servirtium Compatibility Suite

Upstream original: https://github.com/TodoBackend/todo-backend-js-spec - part of the excellent [TodoBackend.com](http://TodoBackend.com) led by Pete Hodgson.

## Fork notes

This fork of the above that adds 'fullTitle' to the headers of every AJAX request that goes from the Mocha test suite to the todobackend.

Some todobackends may fail with this extra header. The Sinatra one at https://todo-backend-sinatra.herokuapp.com/todos does not object. 

Servirtium records all headers, so this amounts to telemetry for the compatibility suite.

## Hosting

Wheareas Pete's Todobackend specs normally run from https://www.todobackend.com/specs, this fork is hosted on GitHub Pages with a less pretty URL: https://servirtium.github.io/compatibility-suite

## Sibling Repo for the Servirtium Compatibility Suite Runner.

See [servirtium/compatibility-suite-runner](https://github.com/servirtium/compatibility-suite-runner)

That repo contains Python code that tests a language implementation again the Mocha suite hosted from this repo. 