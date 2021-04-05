
HOST: http://soa-reception-company.herokuapp.com/

# SOA - reception forms
For authentication, you need to pass an API token in the format <b>"Bearer {token}"</b>

## Authentication
This API uses Custom Header for its authentication.

The parameters that are needed to be sent for this type of authentication are as follows:
+ `Authorization`

# Group receptionformcontroller

## Api V1 Reception Form [/api/v1/reception-form]

### createUsingPOST [POST]
create

+ Request (application/json)

    + Attributes (ReceptionForm)



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





## Api V1 Reception Form All [/api/v1/reception-form/all]

### getAllUsingPOST [POST]
getAll

+ Request (application/json)

    + Attributes (ReceptionFormFilter)



+ Response 200 (application/json)

        OK

    + Attributes (Flux«ReceptionForm»)



+ Response 201

        Created




+ Response 401

        Unauthorized




+ Response 403

        Forbidden




+ Response 404

        Not Found





## Api V1 Reception Form Approve [/api/v1/reception-form/approve]

### approveFormsByCardIdsUsingPOST [POST]
approveFormsByCardIds

+ Request (application/json)

    + Attributes (array[number])



+ Response 200 (application/json)

        OK

    + Attributes (Flux«ReceptionForm»)



+ Response 201

        Created




+ Response 401

        Unauthorized




+ Response 403

        Forbidden




+ Response 404

        Not Found





## Api V1 Reception Form Decline [/api/v1/reception-form/decline]

### declineFormsByCardIdsUsingPOST [POST]
declineFormsByCardIds

+ Request (application/json)

    + Attributes (array[number])



+ Response 200 (application/json)

        OK

    + Attributes (Flux«ReceptionForm»)



+ Response 201

        Created




+ Response 401

        Unauthorized




+ Response 403

        Forbidden




+ Response 404

        Not Found





## Api V1 Reception Form By Id [/api/v1/reception-form/{id}]

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

    + Attributes (ReceptionForm)



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


## Flux«ReceptionForm» (object)


### Properties
+ `prefetch` (number, optional)


## ReceptionForm (object)


### Properties
+ `approved` (boolean, optional)
+ `id` (number, optional)
+ `name` (string, optional)
+ `professionId` (number, optional)
+ `surname` (string, optional)


## ReceptionFormFilter (object)


### Properties
+ `approved` (boolean, optional) 

