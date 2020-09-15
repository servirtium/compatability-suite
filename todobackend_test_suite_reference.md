## Interaction 0: GET /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos the pre-requisites the api root responds to a GET (i.e. the server is up and accessible, CORS headers are set up)
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```

```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_1
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
content-length: 842
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (200: text/html;charset=utf-8):

```
[{"uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_1","title":"blah","order":523,"completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_1","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_1"},{"uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_2","title":"blah","order":95,"completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_2","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_2"},{"uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_3","title":"blah","order":95,"completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_3","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_3"}]
```


## Interaction 1: POST /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos the pre-requisites the api root responds to a POST with the todo which was posted to it
content-length: 18
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"a todo"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_2
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
location: https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_4
content-length: 270
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (201: text/html;charset=utf-8):

```
{"title":"a todo","uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_4","completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_4","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_4"}
```


## Interaction 2: DELETE /todos
### Request headers recorded for playback:

```
content-length: 0
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos the pre-requisites the api root responds successfully to a DELETE
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"a todo"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_2
content-length: 0
connection: close
access-control-allow-origin: *
x-content-type-options: nosniff
```

### Response body recorded for playback (204: ):

```

```


## Interaction 3: DELETE /todos
### Request headers recorded for playback:

```
content-length: 0
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos the pre-requisites after a DELETE the api root responds to a GET with a JSON representation of an empty array
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"a todo"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_2
content-length: 0
connection: close
access-control-allow-origin: *
x-content-type-options: nosniff
```

### Response body recorded for playback (204: ):

```

```


## Interaction 4: GET /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos the pre-requisites after a DELETE the api root responds to a GET with a JSON representation of an empty array
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"a todo"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_3
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
content-length: 2
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (200: text/html;charset=utf-8):

```
[]
```


## Interaction 5: DELETE /todos
### Request headers recorded for playback:

```
content-length: 0
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos the pre-requisites after a DELETE the api root responds to a GET with a JSON representation of an empty array
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"a todo"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_3
content-length: 0
connection: close
access-control-allow-origin: *
x-content-type-options: nosniff
```

### Response body recorded for playback (204: ):

```

```


## Interaction 6: POST /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos storing new todos by posting to the root url adds a new todo to the list of todos at the root url
content-length: 24
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"walk the dog"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_3
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
location: https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_5
content-length: 276
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (201: text/html;charset=utf-8):

```
{"title":"walk the dog","uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_5","completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_5","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_5"}
```


## Interaction 7: GET /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos storing new todos by posting to the root url adds a new todo to the list of todos at the root url
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"walk the dog"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_4
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
content-length: 288
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (200: text/html;charset=utf-8):

```
[{"uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_5","title":"walk the dog","order":0,"completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_5","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_5"}]
```


## Interaction 8: DELETE /todos
### Request headers recorded for playback:

```
content-length: 0
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos storing new todos by posting to the root url adds a new todo to the list of todos at the root url
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"walk the dog"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_5
content-length: 0
connection: close
access-control-allow-origin: *
x-content-type-options: nosniff
```

### Response body recorded for playback (204: ):

```

```


## Interaction 9: POST /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos storing new todos by posting to the root url sets up a new todo as initially not completed
content-length: 16
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"blah"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_5
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
location: https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_6
content-length: 268
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (201: text/html;charset=utf-8):

```
{"title":"blah","uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_6","completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_6","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_6"}
```


## Interaction 10: GET /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos storing new todos by posting to the root url sets up a new todo as initially not completed
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"blah"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_6
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
content-length: 280
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (200: text/html;charset=utf-8):

```
[{"uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_6","title":"blah","order":0,"completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_6","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_6"}]
```


## Interaction 11: DELETE /todos
### Request headers recorded for playback:

```
content-length: 0
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos storing new todos by posting to the root url sets up a new todo as initially not completed
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"blah"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_6
content-length: 0
connection: close
access-control-allow-origin: *
x-content-type-options: nosniff
```

### Response body recorded for playback (204: ):

```

```


## Interaction 12: POST /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos storing new todos by posting to the root url each new todo has a url
content-length: 16
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"blah"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_7
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
location: https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_7
content-length: 268
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (201: text/html;charset=utf-8):

```
{"title":"blah","uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_7","completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_7","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_7"}
```


## Interaction 13: GET /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos storing new todos by posting to the root url each new todo has a url
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"blah"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_8
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
content-length: 280
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (200: text/html;charset=utf-8):

```
[{"uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_7","title":"blah","order":0,"completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_7","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_7"}]
```


## Interaction 14: DELETE /todos
### Request headers recorded for playback:

```
content-length: 0
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos storing new todos by posting to the root url each new todo has a url
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"blah"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_8
content-length: 0
connection: close
access-control-allow-origin: *
x-content-type-options: nosniff
```

### Response body recorded for playback (204: ):

```

```


## Interaction 15: POST /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos storing new todos by posting to the root url each new todo has a url, which returns a todo
content-length: 19
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"my todo"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_9
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
location: https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_8
content-length: 271
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (201: text/html;charset=utf-8):

```
{"title":"my todo","uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_8","completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_8","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_8"}
```


## Interaction 16: GET /todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_8
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos storing new todos by posting to the root url each new todo has a url, which returns a todo
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"my todo"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_9
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
content-length: 281
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (200: text/html;charset=utf-8):

```
{"uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_8","title":"my todo","order":0,"completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_8","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_8"}
```


## Interaction 17: DELETE /todos
### Request headers recorded for playback:

```
content-length: 0
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos storing new todos by posting to the root url each new todo has a url, which returns a todo
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"my todo"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_10
content-length: 0
connection: close
access-control-allow-origin: *
x-content-type-options: nosniff
```

### Response body recorded for playback (204: ):

```

```


## Interaction 18: POST /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos working with an existing todo can navigate from a list of todos to an individual todo via urls
content-length: 27
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"todo the second"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_11
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
location: https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_9
content-length: 278
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (201: text/html;charset=utf-8):

```
{"title":"todo the first","uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_9","completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_9","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_9"}
```


## Interaction 19: POST /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos working with an existing todo can navigate from a list of todos to an individual todo via urls
content-length: 27
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"todo the second"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_11
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
location: https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_10
content-length: 279
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (201: text/html;charset=utf-8):

```
{"title":"todo the second","uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_10","completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_10","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_10"}
```


## Interaction 20: GET /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos working with an existing todo can navigate from a list of todos to an individual todo via urls
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"todo the second"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_11
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
content-length: 580
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (200: text/html;charset=utf-8):

```
[{"uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_9","title":"todo the first","order":0,"completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_9","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_9"},{"uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_10","title":"todo the second","order":0,"completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_10","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_10"}]
```


## Interaction 21: GET /todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_9
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos working with an existing todo can navigate from a list of todos to an individual todo via urls
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"todo the second"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_12
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
content-length: 288
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (200: text/html;charset=utf-8):

```
{"uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_9","title":"todo the first","order":0,"completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_9","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_9"}
```


## Interaction 22: DELETE /todos
### Request headers recorded for playback:

```
content-length: 0
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos working with an existing todo can navigate from a list of todos to an individual todo via urls
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"todo the second"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_13
content-length: 0
connection: close
access-control-allow-origin: *
x-content-type-options: nosniff
```

### Response body recorded for playback (204: ):

```

```


## Interaction 23: POST /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos working with an existing todo can change the todo's title by PATCHing to the todo's url
content-length: 25
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"initial title"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_14
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
location: https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_11
content-length: 277
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (201: text/html;charset=utf-8):

```
{"title":"initial title","uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_11","completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_11","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_11"}
```


## Interaction 24: PATCH /todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_11
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos working with an existing todo can change the todo's title by PATCHing to the todo's url
content-length: 25
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"bathe the cat"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_15
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
content-length: 287
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (200: text/html;charset=utf-8):

```
{"uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_11","title":"bathe the cat","order":0,"completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_11","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_11"}
```


## Interaction 25: DELETE /todos
### Request headers recorded for playback:

```
content-length: 0
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos working with an existing todo can change the todo's title by PATCHing to the todo's url
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"bathe the cat"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_15
content-length: 0
connection: close
access-control-allow-origin: *
x-content-type-options: nosniff
```

### Response body recorded for playback (204: ):

```

```


## Interaction 26: POST /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos working with an existing todo can change the todo's completedness by PATCHing to the todo's url
content-length: 16
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"blah"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_16
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
location: https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_12
content-length: 268
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (201: text/html;charset=utf-8):

```
{"title":"blah","uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_12","completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_12","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_12"}
```


## Interaction 27: PATCH /todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_12
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos working with an existing todo can change the todo's completedness by PATCHing to the todo's url
content-length: 18
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"completed":true}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_16
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
content-length: 277
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (200: text/html;charset=utf-8):

```
{"uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_12","title":"blah","order":0,"completed":true,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_12","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_12"}
```


## Interaction 28: DELETE /todos
### Request headers recorded for playback:

```
content-length: 0
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos working with an existing todo can change the todo's completedness by PATCHing to the todo's url
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"completed":true}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_16
content-length: 0
connection: close
access-control-allow-origin: *
x-content-type-options: nosniff
```

### Response body recorded for playback (204: ):

```

```


## Interaction 29: POST /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos working with an existing todo changes to a todo are persisted and show up when re-fetching the todo
content-length: 16
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"blah"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_17
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
location: https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_13
content-length: 268
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (201: text/html;charset=utf-8):

```
{"title":"blah","uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_13","completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_13","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_13"}
```


## Interaction 30: PATCH /todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_13
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos working with an existing todo changes to a todo are persisted and show up when re-fetching the todo
content-length: 42
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"changed title","completed":true}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_18
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
content-length: 286
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (200: text/html;charset=utf-8):

```
{"uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_13","title":"changed title","order":0,"completed":true,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_13","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_13"}
```


## Interaction 31: GET /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos working with an existing todo changes to a todo are persisted and show up when re-fetching the todo
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"changed title","completed":true}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_18
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
content-length: 286
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (200: text/html;charset=utf-8):

```
{"uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_13","title":"changed title","order":0,"completed":true,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_13","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_13"}
```


## Interaction 32: GET /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos working with an existing todo changes to a todo are persisted and show up when re-fetching the todo
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"changed title","completed":true}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_18
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
content-length: 288
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (200: text/html;charset=utf-8):

```
[{"uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_13","title":"changed title","order":0,"completed":true,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_13","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_13"}]
```


## Interaction 33: DELETE /todos
### Request headers recorded for playback:

```
content-length: 0
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos working with an existing todo changes to a todo are persisted and show up when re-fetching the todo
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"changed title","completed":true}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_19
content-length: 0
connection: close
access-control-allow-origin: *
x-content-type-options: nosniff
```

### Response body recorded for playback (204: ):

```

```


## Interaction 34: POST /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos working with an existing todo can delete a todo making a DELETE request to the todo's url
content-length: 16
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"blah"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_19
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
location: https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_14
content-length: 268
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (201: text/html;charset=utf-8):

```
{"title":"blah","uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_14","completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_14","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_14"}
```


## Interaction 35: DELETE /todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_14
### Request headers recorded for playback:

```
content-length: 0
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos working with an existing todo can delete a todo making a DELETE request to the todo's url
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"blah"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_20
content-length: 0
connection: close
access-control-allow-origin: *
x-content-type-options: nosniff
```

### Response body recorded for playback (204: ):

```

```


## Interaction 36: GET /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos working with an existing todo can delete a todo making a DELETE request to the todo's url
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"blah"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_20
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
content-length: 2
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (200: text/html;charset=utf-8):

```
[]
```


## Interaction 37: POST /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos tracking todo order can create a todo with an order field
content-length: 28
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"title":"blah","order":523}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_20
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
location: https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_15
content-length: 280
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (201: text/html;charset=utf-8):

```
{"title":"blah","order":523,"uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_15","completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_15","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_15"}
```


## Interaction 38: POST /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos tracking todo order can PATCH a todo to change its order
content-length: 27
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"order":10,"title":"blah"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_21
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
location: https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_16
content-length: 279
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (201: text/html;charset=utf-8):

```
{"order":10,"title":"blah","uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_16","completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_16","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_16"}
```


## Interaction 39: PATCH /todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_16
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos tracking todo order can PATCH a todo to change its order
content-length: 12
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"order":95}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_22
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
content-length: 279
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (200: text/html;charset=utf-8):

```
{"uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_16","title":"blah","order":95,"completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_16","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_16"}
```


## Interaction 40: POST /todos
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos tracking todo order remembers changes to a todo's order
content-length: 27
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"order":10,"title":"blah"}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_22
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
location: https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_17
content-length: 279
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (201: text/html;charset=utf-8):

```
{"order":10,"title":"blah","uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_17","completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_17","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_17"}
```


## Interaction 41: PATCH /todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_17
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos tracking todo order remembers changes to a todo's order
content-length: 12
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"order":95}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_22
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
content-length: 279
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (200: text/html;charset=utf-8):

```
{"uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_17","title":"blah","order":95,"completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_17","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_17"}
```


## Interaction 42: GET /todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_17
### Request headers recorded for playback:

```
accept-language: en-US,en;q=0.9
accept-encoding: gzip, deflate, br
sec-fetch-dest: empty
sec-fetch-mode: cors
sec-fetch-site: cross-site
origin: https://servirtium.github.io
content-type: application/json
user-agent: Chrome under Selenium control
accept: text/plain, */*; q=0.01
fulltitle: Todo-Backend API residing at http://todo-backend-sinatra.herokuapp.com/todos tracking todo order remembers changes to a todo's order
connection: close
host: todo-backend-sinatra.herokuapp.com
```

### Request body recorded for playback ():

```
{"order":95}
```

### Response headers recorded for playback:

```
date: REPLACED_DATETIME_FOR_COMPATIBILITY_TEST_23
connection: close
content-type: text/html;charset=utf-8
access-control-allow-origin: *
content-length: 279
x-xss-protection: 1; mode=block
x-content-type-options: nosniff
x-frame-options: SAMEORIGIN
```

### Response body recorded for playback (200: text/html;charset=utf-8):

```
{"uid":"REPLACED_UUID_FOR_COMPATIBILITY_TEST_17","title":"blah","order":95,"completed":false,"href":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_17","url":"https://todo-backend-sinatra.herokuapp.com/todos/REPLACED_UUID_FOR_COMPATIBILITY_TEST_17"}
```
