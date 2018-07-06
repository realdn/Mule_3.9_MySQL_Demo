# Mule_3.9_MySQL_Demo
Retrieve data from my sql database using mule database connector

1. install my sql sever locally (if not alrady exit) 
2. create a "course" table in "mysmsdb" with "id", "name" and "description" column 

3. run the project as "MUle application with Maven"

Test the endpoint in a browser or curl 
http://localhost:8081/getdata

## Response

[{"description":"Spring","name":"Course1","id":1},{"description":"Summer","name":"Course2","id":2}]

