This fork of https://github.com/TodoBackend/todo-backend-js-spec adds fullTitle to the headers of every AJAX request that goes from the Mocha test suite to the todobackend.

Some todobackends may fail with this extra header. The Sinatra one does not object. 

Servirtium records all headers, so this amounts to telemetry for the compatibility suite.

Wheareas Pete Hodgson's specs normally run from https://www.todobackend.com/specs, this fork is hosted here (less pretty URL; GitHub Pages): https://servirtium.github.io/todo-backend-js-spec