# ToDo API

## REST endpoints
* List: Get /todos
* Create: POST /todos
* Update: PUT /todos


## - Response
Status: 200
Content-type: application/json
Body: { todoos: todos }

# Create: POST /todos
## - Request
Method: POST
Path: /todos
Content-type: application/json
Body: { name: "New todo name" }

## - Response
### If they did not send over a name field:
Status: 400
Content-type: application/json
Body: {msg: "Message" }

### Else: add the tod to the list and send response
Status: 201
Content-type: none
Body: none 

