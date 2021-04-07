HOST: https://soa-students.herokuapp.com

# SOA - Students
For authentication, you need to pass an API token in the format <b>"Bearer {token}"</b>

## Authentication
This API uses Custom Header for its authentication.

The parameters that are needed to be sent for this type of authentication are as follows:
+ `Authorization` - JWT Authorization header using the Bearer scheme. \r\n\r\n 
                      Enter 'Bearer' [space] and then your token in the text input below.
                      \r\n\r\nExample: 'Bearer 12345abcdef'

# Group AcademicPerformances

## Api AcademicPerformances GetAcademicPerformances [/api/AcademicPerformances/GetAcademicPerformances]

### ApiAcademicPerformancesGetAcademicPerformancesGET [GET]

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

    + Attributes (array[AcademicPerformanceView])



+ Response 200 (application/json)

        Success

    + Attributes (array[AcademicPerformanceView])



+ Response 200 (text/json)

        Success

    + Attributes (array[AcademicPerformanceView])




## Api AcademicPerformances GetAcademicPerformance [/api/AcademicPerformances/GetAcademicPerformance{?Id}]

### ApiAcademicPerformancesGetAcademicPerformanceGET [GET]
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

    + Attributes (AcademicPerformanceView)



+ Response 200 (application/json)

        Success

    + Attributes (AcademicPerformanceView)



+ Response 200 (text/json)

        Success

    + Attributes (AcademicPerformanceView)



+ Response 404 (text/plain)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (application/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (text/json)

        Not Found

    + Attributes (ProblemDetails)




## Api AcademicPerformances PutAcademicPerformance [/api/AcademicPerformances/PutAcademicPerformance/{id}]

+ Parameters
    + id (number, required)


### ApiAcademicPerformancesPutAcademicPerformancePUT [PUT]

+ Request (application/json)

    + Attributes (UpsertAcademicPerformanceRequest)



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





## Api AcademicPerformances PostAcademicPerformance [/api/AcademicPerformances/PostAcademicPerformance]

### ApiAcademicPerformancesPostAcademicPerformancePOST [POST]

+ Request (application/json)

    + Attributes (UpsertAcademicPerformanceRequest)



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

    + Attributes (AcademicPerformanceView)



+ Response 201 (application/json)

        Success

    + Attributes (AcademicPerformanceView)



+ Response 201 (text/json)

        Success

    + Attributes (AcademicPerformanceView)



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





## Api AcademicPerformances DeleteAcademicPerformance [/api/AcademicPerformances/DeleteAcademicPerformance{?Id}]

### ApiAcademicPerformancesDeleteAcademicPerformanceDELETE [DELETE]
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






# Group Exams

## Api Exams GetExams [/api/Exams/GetExams]

### ApiExamsGetExamsGET [GET]

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

    + Attributes (array[ExamView])



+ Response 200 (application/json)

        Success

    + Attributes (array[ExamView])



+ Response 200 (text/json)

        Success

    + Attributes (array[ExamView])




## Api Exams GetExam [/api/Exams/GetExam{?Id}]

### ApiExamsGetExamGET [GET]
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

    + Attributes (ExamView)



+ Response 200 (application/json)

        Success

    + Attributes (ExamView)



+ Response 200 (text/json)

        Success

    + Attributes (ExamView)



+ Response 404 (text/plain)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (application/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (text/json)

        Not Found

    + Attributes (ProblemDetails)




## Api Exams PutExam By Id [/api/Exams/PutExam/{id}]

+ Parameters
    + id (number, required)


### ApiExamsPutExamByIdPUT [PUT]

+ Request (application/json)

    + Attributes (UpsertExamRequest)



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





## Api Exams PostExam [/api/Exams/PostExam]

### ApiExamsPostExamPOST [POST]

+ Request (application/json)

    + Attributes (UpsertExamRequest)



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

    + Attributes (ExamView)



+ Response 201 (application/json)

        Success

    + Attributes (ExamView)



+ Response 201 (text/json)

        Success

    + Attributes (ExamView)



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





## Api Exams DeleteExam [/api/Exams/DeleteExam{?Id}]

### ApiExamsDeleteExamDELETE [DELETE]
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






# Group Students

## Api Students GetStudents [/api/Students/GetStudents]

### ApiStudentsGetStudentsGET [GET]

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

    + Attributes (array[StudentView])



+ Response 200 (application/json)

        Success

    + Attributes (array[StudentView])



+ Response 200 (text/json)

        Success

    + Attributes (array[StudentView])




## Api Students GetStudent [/api/Students/GetStudent{?Id}]

### ApiStudentsGetStudentGET [GET]
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

    + Attributes (StudentView)



+ Response 200 (application/json)

        Success

    + Attributes (StudentView)



+ Response 200 (text/json)

        Success

    + Attributes (StudentView)



+ Response 404 (text/plain)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (application/json)

        Not Found

    + Attributes (ProblemDetails)



+ Response 404 (text/json)

        Not Found

    + Attributes (ProblemDetails)




## Api Students PutStudent By Id [/api/Students/PutStudent/{id}]

+ Parameters
    + id (number, required)


### ApiStudentsPutStudentByIdPUT [PUT]

+ Request (application/json)

    + Attributes (UpsertStudentRequest)



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





## Api Students PostStudent [/api/Students/PostStudent]

### ApiStudentsPostStudentPOST [POST]

+ Request (application/json)

    + Attributes (UpsertStudentRequest)



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

    + Attributes (StudentView)



+ Response 201 (application/json)

        Success

    + Attributes (StudentView)



+ Response 201 (text/json)

        Success

    + Attributes (StudentView)



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





## Api Students DeleteStudent [/api/Students/DeleteStudent{?Id}]

### ApiStudentsDeleteStudentDELETE [DELETE]
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


## StudentView (object)


### Properties
+ `id` (number, optional) 
+ `surname` (string, optional, nullable) 
+ `firstName` (string, optional, nullable) 
+ `patronymic` (string, optional, nullable) 
+ `sex` (enum[number], optional) 
    + `0`
    + `1`
+ `dateOfBirthday` (string, optional) 
+ `address` (string, optional, nullable) 
+ `specialtyId` (number, optional) 


## ExamView (object)


### Properties
+ `id` (number, optional) 
+ `academicPlanVsDisciplineId` (number, optional) 
+ `examDate` (string, optional) 


## AcademicPerformanceView (object)


### Properties
+ `id` (number, optional) 
+ `studentView` (StudentView, optional) 
+ `examView` (ExamView, optional) 
+ `grage` (number, optional) 


## UpsertAcademicPerformanceRequest (object)


### Properties
+ `id` (number, optional) 
+ `studentId` (number, required) 
+ `examId` (number, required) 
+ `grage` (number, required) 


## UpsertExamRequest (object)


### Properties
+ `id` (number, optional) 
+ `academicPlanVsDisciplineId` (number, required) 
+ `examDate` (string, required) 


## UpsertStudentRequest (object)


### Properties
+ `id` (number, optional) 
+ `surname` (string, required) 
+ `firstName` (string, required) 
+ `patronymic` (string, required) 
+ `sex` (enum[number], required) 
    + `0`
    + `1`
+ `dateOfBirthday` (string, required) 
+ `address` (string, required) 
+ `specialtyId` (number, required) 

