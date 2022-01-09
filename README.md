Technologies: MySQL, Hibernate

###### Adding Task
` POST 'localhost:9191/tasks/add' 
 'Content-Type: application/json' 
  data-raw '{
"title":"test 2"
}'
`

##### Get All Tasks

`GET 'localhost:9191/tasks'
`

#### Update Task

`PUT 'localhost:9191/tasks/update/1'
`

#### Delete Task

`DELETE 'localhost:9191/tasks/delete/2'
`