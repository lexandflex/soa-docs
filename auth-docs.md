
HOST: http://soa-auth.herokuapp.com/

# title
For authentication, you need to pass an API token in the format <b>"Bearer {token}"</b>

## Authentication
This API uses Custom Header for its authentication.

The parameters that are needed to be sent for this type of authentication are as follows:
+ `Authorization`

# Group accountcontroller

## Api V1 Account Login [/api/v1/account/login]

### loginUsingPOST [POST]
login

+ Request (application/json)

  + Attributes (LoginRequest)



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





## Api V1 Account Reg [/api/v1/account/reg]

### registrationUsingPOST [POST]
registration

+ Request (application/json)

  + Attributes (LoginRequest)



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





## Api V1 Account Test [/api/v1/account/test]

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

## AppUserDto (object)


### Properties
+ `id` (number, optional)
+ `isLocked` (boolean, optional)
+ `name` (string, optional)
+ `roles` (array, optional)
  + (enum[string])
    + Members
      + `ADMIN`
      + `STUDENT`
      + `TEACHER`
+ `username` (string, optional)


## LoginRequest (object)


### Properties
+ `login` (string, optional)
+ `password` (string, optional) 
