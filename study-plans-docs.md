# SOA - Study plans
For authentication, you need to pass an API token in the format <b>"Bearer {token}"</b>

## Authentication
This API uses Custom Header for its authentication.

The parameters that are needed to be sent for this type of authentication are as follows:
+ `Authorization` - JWT Authorization header using the Bearer scheme. \r\n\r\n 
                      Enter 'Bearer' [space] and then your token in the text input below.
                      \r\n\r\nExample: 'Bearer 12345abcdef'

# Group AcademicPlans

## Api AcademicPlans GetAcademicPlans [/api/AcademicPlans/GetAcademicPlans]

### ApiAcademicPlansGetAcademicPlansGET [GET]

+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 200 (text/plain)

        Success

    + Attributes (array[AcademicPlanView])



+ Response 200 (application/json)

        Success

    + Attributes (array[AcademicPlanView])



+ Response 200 (text/json)

        Success

    + Attributes (array[AcademicPlanView])




## Api AcademicPlans GetAcademicPlan [/api/AcademicPlans/GetAcademicPlan{?Id}]

### ApiAcademicPlansGetAcademicPlanGET [GET]
+ Parameters
    + Id (number, required)


+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 200 (text/plain)

        Success

    + Attributes (AcademicPlanView)



+ Response 200 (application/json)

        Success

    + Attributes (AcademicPlanView)



+ Response 200 (text/json)

        Success

    + Attributes (AcademicPlanView)



+ Response 404 (text/plain)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (application/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (text/json)

        Not Found

    + Attributes (ProblemDetails)




## Api AcademicPlans PutAcademicPlan By Id [/api/AcademicPlans/PutAcademicPlan/{id}]

+ Parameters
    + id (number, required)


### ApiAcademicPlansPutAcademicPlanByIdPUT [PUT]

+ Request (application/json)

    + Attributes (UpsertAcademicPlanRequest)



+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 200 

        Success




+ Response 400 (text/plain)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 400 (application/json)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 400 (text/json)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 404 (text/plain)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (application/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (text/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 500 

        Server Error





## Api AcademicPlans PostAcademicPlan [/api/AcademicPlans/PostAcademicPlan]

### ApiAcademicPlansPostAcademicPlanPOST [POST]

+ Request (application/json)

    + Attributes (UpsertAcademicPlanRequest)



+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 201 (text/plain)

        Success

    + Attributes (AcademicPlanView)



+ Response 201 (application/json)

        Success

    + Attributes (AcademicPlanView)



+ Response 201 (text/json)

        Success

    + Attributes (AcademicPlanView)



+ Response 400 (text/plain)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 400 (application/json)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 400 (text/json)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 500 

        Server Error





## Api AcademicPlans DeleteAcademicPlan [/api/AcademicPlans/DeleteAcademicPlan{?Id}]

### ApiAcademicPlansDeleteAcademicPlanDELETE [DELETE]
+ Parameters
    + Id (number, required)


+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 200 

        Success




+ Response 404 (text/plain)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (application/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (text/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 500 

        Server Error






# Group AcademicPlanVsDisciplines

## Api AcademicPlanVsDisciplines GetAcademicPlanVsDisciplines [/api/AcademicPlanVsDisciplines/GetAcademicPlanVsDisciplines]

### ApiAcademicPlanVsDisciplinesGetAcademicPlanVsDisciplinesGET [GET]

+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 200 (text/plain)

        Success

    + Attributes (array[AcademicPlanVsDisciplineView])



+ Response 200 (application/json)

        Success

    + Attributes (array[AcademicPlanVsDisciplineView])



+ Response 200 (text/json)

        Success

    + Attributes (array[AcademicPlanVsDisciplineView])




## Api AcademicPlanVsDisciplines GetAcademicPlanVsDiscipline [/api/AcademicPlanVsDisciplines/GetAcademicPlanVsDiscipline{?Id}]

### ApiAcademicPlanVsDisciplinesGetAcademicPlanVsDisciplineGET [GET]
+ Parameters
    + Id (number, required)


+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 200 (text/plain)

        Success

    + Attributes (AcademicPlanVsDisciplineView)



+ Response 200 (application/json)

        Success

    + Attributes (AcademicPlanVsDisciplineView)



+ Response 200 (text/json)

        Success

    + Attributes (AcademicPlanVsDisciplineView)



+ Response 404 (text/plain)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (application/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (text/json)

        Not Found

    + Attributes (ProblemDetails)




## Api AcademicPlanVsDisciplines PutAcademicPlanVsDiscipline [/api/AcademicPlanVsDisciplines/PutAcademicPlanVsDiscipline/{id}]

+ Parameters
    + id (number, required)


### ApiAcademicPlanVsDisciplinesPutAcademicPlanVsDisciplinePUT [PUT]

+ Request (application/json)

    + Attributes (UpsertAcademicPlanVsDisciplineRequest)



+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 200 

        Success




+ Response 400 (text/plain)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 400 (application/json)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 400 (text/json)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 404 (text/plain)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (application/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (text/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 500 

        Server Error





## Api AcademicPlanVsDisciplines PostAcademicPlanVsDiscipline [/api/AcademicPlanVsDisciplines/PostAcademicPlanVsDiscipline]

### ApiAcademicPlanVsDisciplinesPostAcademicPlanVsDisciplinePOST [POST]

+ Request (application/json)

    + Attributes (UpsertAcademicPlanVsDisciplineRequest)



+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 201 (text/plain)

        Success

    + Attributes (AcademicPlanVsDisciplineView)



+ Response 201 (application/json)

        Success

    + Attributes (AcademicPlanVsDisciplineView)



+ Response 201 (text/json)

        Success

    + Attributes (AcademicPlanVsDisciplineView)



+ Response 400 (text/plain)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 400 (application/json)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 400 (text/json)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 500 

        Server Error





## Api AcademicPlanVsDisciplines DeleteAcademicPlanVsDiscipline [/api/AcademicPlanVsDisciplines/DeleteAcademicPlanVsDiscipline{?Id}]

### ApiAcademicPlanVsDisciplinesDeleteAcademicPlanVsDisciplineDELETE [DELETE]
+ Parameters
    + Id (number, required)


+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 200 

        Success




+ Response 404 (text/plain)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (application/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (text/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 500 

        Server Error






# Group Disciplines

## Api Disciplines GetDisciplines [/api/Disciplines/GetDisciplines]

### ApiDisciplinesGetDisciplinesGET [GET]

+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 200 (text/plain)

        Success

    + Attributes (array[DisciplineView])



+ Response 200 (application/json)

        Success

    + Attributes (array[DisciplineView])



+ Response 200 (text/json)

        Success

    + Attributes (array[DisciplineView])




## Api Disciplines GetDiscipline [/api/Disciplines/GetDiscipline{?Id}]

### ApiDisciplinesGetDisciplineGET [GET]
+ Parameters
    + Id (number, required)


+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 200 (text/plain)

        Success

    + Attributes (DisciplineView)



+ Response 200 (application/json)

        Success

    + Attributes (DisciplineView)



+ Response 200 (text/json)

        Success

    + Attributes (DisciplineView)



+ Response 404 (text/plain)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (application/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (text/json)

        Not Found

    + Attributes (ProblemDetails)




## Api Disciplines PutDiscipline By Id [/api/Disciplines/PutDiscipline/{id}]

+ Parameters
    + id (number, required)


### ApiDisciplinesPutDisciplineByIdPUT [PUT]

+ Request (application/json)

    + Attributes (UpsertDisciplineRequest)



+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 200 

        Success




+ Response 400 (text/plain)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 400 (application/json)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 400 (text/json)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 404 (text/plain)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (application/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (text/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 500 

        Server Error





## Api Disciplines PostDiscipline [/api/Disciplines/PostDiscipline]

### ApiDisciplinesPostDisciplinePOST [POST]

+ Request (application/json)

    + Attributes (UpsertDisciplineRequest)



+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 201 (text/plain)

        Success

    + Attributes (DisciplineView)



+ Response 201 (application/json)

        Success

    + Attributes (DisciplineView)



+ Response 201 (text/json)

        Success

    + Attributes (DisciplineView)



+ Response 400 (text/plain)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 400 (application/json)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 400 (text/json)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 500 

        Server Error





## Api Disciplines DeleteDiscipline [/api/Disciplines/DeleteDiscipline{?Id}]

### ApiDisciplinesDeleteDisciplineDELETE [DELETE]
+ Parameters
    + Id (number, required)


+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 200 

        Success




+ Response 404 (text/plain)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (application/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (text/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 500 

        Server Error






# Group Faculties

## Api Faculties GetFaculties [/api/Faculties/GetFaculties]

### ApiFacultiesGetFacultiesGET [GET]

+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 200 (text/plain)

        Success

    + Attributes (array[FacultyView])



+ Response 200 (application/json)

        Success

    + Attributes (array[FacultyView])



+ Response 200 (text/json)

        Success

    + Attributes (array[FacultyView])




## Api Faculties GetFaculty [/api/Faculties/GetFaculty{?Id}]

### ApiFacultiesGetFacultyGET [GET]
+ Parameters
    + Id (number, required)


+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 200 (text/plain)

        Success

    + Attributes (FacultyView)



+ Response 200 (application/json)

        Success

    + Attributes (FacultyView)



+ Response 200 (text/json)

        Success

    + Attributes (FacultyView)



+ Response 404 (text/plain)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (application/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (text/json)

        Not Found

    + Attributes (ProblemDetails)




## Api Faculties PutFaculty By Id [/api/Faculties/PutFaculty/{id}]

+ Parameters
    + id (number, required)


### ApiFacultiesPutFacultyByIdPUT [PUT]

+ Request (application/json)

    + Attributes (UpsertFacultyRequest)



+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 200 

        Success




+ Response 400 (text/plain)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 400 (application/json)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 400 (text/json)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 404 (text/plain)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (application/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (text/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 500 

        Server Error





## Api Faculties PostFaculty [/api/Faculties/PostFaculty]

### ApiFacultiesPostFacultyPOST [POST]

+ Request (application/json)

    + Attributes (UpsertFacultyRequest)



+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 201 (text/plain)

        Success

    + Attributes (FacultyView)



+ Response 201 (application/json)

        Success

    + Attributes (FacultyView)



+ Response 201 (text/json)

        Success

    + Attributes (FacultyView)



+ Response 400 (text/plain)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 400 (application/json)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 400 (text/json)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 500 

        Server Error





## Api Faculties DeleteFaculty [/api/Faculties/DeleteFaculty{?Id}]

### ApiFacultiesDeleteFacultyDELETE [DELETE]
+ Parameters
    + Id (number, required)


+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 200 

        Success




+ Response 404 (text/plain)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (application/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (text/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 500 

        Server Error






# Group Specialtys

## Api Specialtys GetSpecialties [/api/Specialtys/GetSpecialties]

### ApiSpecialtysGetSpecialtiesGET [GET]

+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 200 (text/plain)

        Success

    + Attributes (array[SpecialtyView])



+ Response 200 (application/json)

        Success

    + Attributes (array[SpecialtyView])



+ Response 200 (text/json)

        Success

    + Attributes (array[SpecialtyView])




## Api Specialtys GetSpecialty [/api/Specialtys/GetSpecialty{?Id}]

### ApiSpecialtysGetSpecialtyGET [GET]
+ Parameters
    + Id (number, required)


+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 200 (text/plain)

        Success

    + Attributes (SpecialtyView)



+ Response 200 (application/json)

        Success

    + Attributes (SpecialtyView)



+ Response 200 (text/json)

        Success

    + Attributes (SpecialtyView)



+ Response 404 (text/plain)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (application/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (text/json)

        Not Found

    + Attributes (ProblemDetails)




## Api Specialtys PutSpecialty By Id [/api/Specialtys/PutSpecialty/{id}]

+ Parameters
    + id (number, required)


### ApiSpecialtysPutSpecialtyByIdPUT [PUT]

+ Request (application/json)

    + Attributes (UpsertSpecialtyRequest)



+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 200 

        Success




+ Response 400 (text/plain)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 400 (application/json)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 400 (text/json)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 404 (text/plain)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (application/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (text/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 500 

        Server Error





## Api Specialtys PostSpecialty [/api/Specialtys/PostSpecialty]

### ApiSpecialtysPostSpecialtyPOST [POST]

+ Request (application/json)

    + Attributes (UpsertSpecialtyRequest)



+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 201 (text/plain)

        Success

    + Attributes (SpecialtyView)



+ Response 201 (application/json)

        Success

    + Attributes (SpecialtyView)



+ Response 201 (text/json)

        Success

    + Attributes (SpecialtyView)



+ Response 400 (text/plain)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 400 (application/json)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 400 (text/json)

        Bad Request

    + Attributes (ProblemDetails)



+ Response 500 

        Server Error





## Api Specialtys DeleteSpecialty [/api/Specialtys/DeleteSpecialty{?Id}]

### ApiSpecialtysDeleteSpecialtyDELETE [DELETE]
+ Parameters
    + Id (number, required)


+ Response 401 (text/plain)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (application/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 401 (text/json)

        Unauthorized

    + Attributes (ProblemDetails)



+ Response 200 

        Success




+ Response 404 (text/plain)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (application/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (text/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 500 

        Server Error






# Data Structures

## ProblemDetails (object)


### Properties
+ `type` (string, optional, nullable) 
+ `title` (string, optional, nullable) 
+ `status` (number, optional, nullable) 
+ `detail` (string, optional, nullable) 
+ `instance` (string, optional, nullable) 


## FacultyView (object)


### Properties
+ `id` (number, optional) 
+ `title` (string, optional, nullable) 
+ `cabinetNumber` (number, optional) 


## SpecialtyView (object)


### Properties
+ `id` (number, optional) 
+ `title` (string, optional, nullable) 
+ `facultyView` (FacultyView, optional) 
+ `admissionPlan` (number, optional) 


## AcademicPlanView (object)


### Properties
+ `id` (number, optional) 
+ `specialtyId` (number, optional) 
+ `specialtyView` (SpecialtyView, optional) 
+ `semester` (number, optional) 


## UpsertAcademicPlanRequest (object)


### Properties
+ `id` (number, optional) 
+ `specialtyId` (number, required) 
+ `semester` (number, required) 


## DisciplineView (object)


### Properties
+ `id` (number, optional) 
+ `title` (number, optional) 


## AcademicPlanVsDisciplineView (object)


### Properties
+ `id` (number, optional) 
+ `academicPlanView` (AcademicPlanView, optional) 
+ `disciplineView` (DisciplineView, optional) 
+ `formOfControl` (enum[number], optional) 
    + `0`
    + `1`
+ `totalHours` (number, optional) 


## UpsertAcademicPlanVsDisciplineRequest (object)


### Properties
+ `id` (number, optional) 
+ `academicPlanId` (number, required) 
+ `disciplineId` (number, required) 
+ `formOfControl` (enum[number], required) 
    + `0`
    + `1`
+ `totalHours` (number, required) 


## UpsertDisciplineRequest (object)


### Properties
+ `id` (number, optional) 
+ `title` (number, required) 


## UpsertFacultyRequest (object)


### Properties
+ `id` (number, optional) 
+ `title` (string, required) 
+ `cabinetNumber` (number, required) 


## UpsertSpecialtyRequest (object)


### Properties
+ `id` (number, optional) 
+ `title` (string, required) 
+ `facultyId` (number, required) 
+ `admissionPlan` (number, required) 

