# springboot-mongodb-crud
springboot-mongodb-crud
# Steps
* Step 1:
* create “ProductDB” database and “ProductDB” collection in mongodb
* create Springboot starter project
* Dependencies: Spring Web and Spring Data MongoDB
* Step 2:
* Add mongo DB configuration in application.properties
* Step 3:
* Add jakarta.validation dependency in pom.xml, refer updated pom.xml
* Step 4:
* Create all classes mentioned in the github
* Step 5:
* Run Application class as Springboot application
* Step 6:
* POST: http://localhost:8080/products
* input: -> Body -> Raw
* {
    "id": 1,
    "name": "Nothing 2",
    "description": "5G Android Mobile"
}
* Output:
*Status: 200 ok
* {
    "id": 1,
    "name": "Nothing 2",
    "description": "5G Android Mobile"
}
* ![image](https://github.com/sathees-saty/springboot-mongodb-crud/assets/65384711/e8dd795d-098f-4bfc-9863-f02f5d31742c)
* GET
* ![image](https://github.com/sathees-saty/springboot-mongodb-crud/assets/65384711/f5832480-4785-4bcc-b5aa-3a1a0cb0fe6c)
* GET
* ![image](https://github.com/sathees-saty/springboot-mongodb-crud/assets/65384711/cc73ed3d-78d6-4edc-b870-4389f3296c5f)
* PUT:  http://localhost:8080/products/1 input: -> Body -> Raw
* {
    "id": 1,
    "name": "Nothing 2",
    "description": "5G Android Mobile India"
}
* ![image](https://github.com/sathees-saty/springboot-mongodb-crud/assets/65384711/7d6ac084-88f1-4e92-8161-2ebdf4a9bc32)
* MongoDB
* ![image](https://github.com/sathees-saty/springboot-mongodb-crud/assets/65384711/843dfe08-616b-4e92-ae87-e44f5cc53ac2)
* DELETE: http://localhost:8080/products/1
* ![image](https://github.com/sathees-saty/springboot-mongodb-crud/assets/65384711/f0b0c273-2aa6-4660-a4c7-2474eb3466a8)
* ![image](https://github.com/sathees-saty/springboot-mongodb-crud/assets/65384711/1b7b33cd-41b3-4a9e-a407-92b9a1976c59)






