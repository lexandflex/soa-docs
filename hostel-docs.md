
HOST: http://soa-hostel.herokuapp.com/

# SOA - hostel
For authentication, you need to pass an API token in the format <b>"Bearer {token}"</b>

## Authentication
This API uses Custom Header for its authentication.

The parameters that are needed to be sent for this type of authentication are as follows:
+ `Authorization`

# Group studentcontroller

## Api V1 Student [/api/v1/student]

### createUsingPOST [POST]
create

+ Request (application/json)

  + Attributes (Student)



+ Response 200 (application/json)

        OK

  + Attributes (object)



+ Response 201

        Created




+ Response 401

        Unauthorized




+ Response 403

        Forbidden




+ Response 404

        Not Found





## Api V1 Student All [/api/v1/student/all]

### getAllUsingPOST [POST]
getAll

+ Request (application/json)

  + Attributes (StudentsFilter)



+ Response 200 (application/json)

        OK

  + Attributes (Flux«Student»)



+ Response 201

        Created




+ Response 401

        Unauthorized




+ Response 403

        Forbidden




+ Response 404

        Not Found





## Api V1 Student Evict [/api/v1/student/evict]

### evictStudentsByCardIdsUsingPOST [POST]
evictStudentsByCardIds

+ Request (application/json)

  + Attributes (array[number])



+ Response 200 (application/json)

        OK

  + Attributes (Flux«Student»)



+ Response 201

        Created




+ Response 401

        Unauthorized




+ Response 403

        Forbidden




+ Response 404

        Not Found





## Api V1 Student Populate [/api/v1/student/populate]

### populateStudentsByCardIdsUsingPOST [POST]
populateStudentsByCardIds

+ Request (application/json)

  + Attributes (array[number])



+ Response 200 (application/json)

        OK

  + Attributes (Flux«Student»)



+ Response 201

        Created




+ Response 401

        Unauthorized




+ Response 403

        Forbidden




+ Response 404

        Not Found





## Api V1 Student By Id [/api/v1/student/{id}]

+ Parameters
  + id (number, required)

    id


### getByIdUsingGET [GET]
getById

+ Response 200 (application/json)

        OK

  + Attributes (object)



+ Response 401

        Unauthorized




+ Response 403

        Forbidden




+ Response 404

        Not Found




### updateUsingPUT [PUT]
update

+ Request (application/json)

  + Attributes (Student)



+ Response 200 (application/json)

        OK

  + Attributes (object)



+ Response 201

        Created




+ Response 401

        Unauthorized




+ Response 403

        Forbidden




+ Response 404

        Not Found




### deleteByIdUsingDELETE [DELETE]
deleteById

+ Response 200 (application/json)

        OK

  + Attributes (object)



+ Response 204

        No Content




+ Response 401

        Unauthorized




+ Response 403

        Forbidden






# Group testcontroller

## Api V1 Test Test [/api/v1/test/test]

### testUsingGET [GET]
test

+ Response 200 (application/json)

        OK

  + Attributes (object)



+ Response 401

        Unauthorized




+ Response 403

        Forbidden




+ Response 404

        Not Found






# Data Structures

## AppUser (object)


### Properties
+ `id` (number, optional)
+ `isLocked` (boolean, optional)
+ `name` (string, optional)
+ `password` (string, optional)
+ `roles` (array, optional)
  + (enum[string])
    + Members
      + `ADMIN`
      + `STUDENT`
      + `TEACHER`
+ `username` (string, optional)


## Flux«Student» (object)


### Properties
+ `prefetch` (number, optional)


## Student (object)


### Properties
+ `cardId` (number, optional)
+ `id` (number, optional)
+ `live` (boolean, optional)
+ `name` (string, optional)
+ `surname` (string, optional)


## StudentsFilter (object)


### Properties
+ `live` (boolean, optional) 
