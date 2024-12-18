# spring-rest-rnd
REST APIs for User entity

# postman requests
student-services
﻿

# GET
# students-getall
http://localhost:8080/api/v1/students
﻿

Body
raw (text)

# GET
# student-getsingle
http://localhost:8080/api/v1/students/10002﻿

Request Headers
Cache-Control
no-cache
Postman-Token
<calculated when request is sent>
Host
<calculated when request is sent>
User-Agent
PostmanRuntime/7.39.1
Accept
*/*
Accept-Encoding
gzip, deflate, br
Connection
keep-alive
Body
raw (text)

# DELETE
# student-delete
http://localhost:8080/api/v1/students/1
﻿

Body
raw (json)

# POST
# student-add
http://127.0.0.1:8080/api/v1/students
﻿

Body
raw (json)
json
{
    "name":"guru",
    "passportNumber":"123123"
}

# PUT
# student-edit
http://127.0.0.1:8080/api/v1/students/10001
﻿

Body
raw (json)
json
{
    "name": "guru",
    "passportNumber": "123123"
}
