# nodejstodo
This is Todo application on Node, Express and Postgres

You can send requests:<br/>

<b>1. Create a todo <br/></b>
POST http://localhost:4000/todos <br/>
Body
{
  "description": "hello"
}

<b>2. Get a todo <br/></b>
GET http://localhost:4000/todos/:id <br/>

<b>3. Get all todos <br/></b>
GET http://localhost:4000/todos <br/>

<b>4. Update a todo <br/></b>
PUT http://localhost:4000/todos/:id <br/>

<b>5. Delete a todo <br/></b>
DELETE http://localhost:4000/todos/:id <br/>


