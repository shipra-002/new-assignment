# new-assignment

In this assignment ,I have created login page for user in Backend development.
I have used postman for running the api's. 
I have used mongodb for database.
First user have to register himself with some of his details ,and after register ,user can login with email and password ,like we login in google or facebook.
I have used all types of validation here.
After login we will get jwt token ,that token we can store in cookies or headers.
So user don't have to give email or password again and again.

# output of first api
{
    "msg": {
        "title": "Miss",
        "name": "Pakhi",
        "phone": 9888909091,
        "email": "p123@gmail.com",
        "password": "pass1234",
        "address": {
            "street": "14th cross street",
            "city": "Bangalore",
            "pincode": "560078"
        },
        "_id": "638aff94c189d9dc9873ace1",
        "createdAt": "2022-12-03T07:49:40.338Z",
        "updatedAt": "2022-12-03T07:49:40.338Z",
        "__v": 0
    }
}

# output of 2nd api.
{
    "status": "LoggedIn",
    "TOKEN": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VySWQiOiI2MzhhZmY5NGMxODlkOWRjOTg3M2FjZTEiLCJpYXQiOjE2NzAwNTU2NDYsImV4cCI6MTY3MDA3MzY0Nn0.IdlWy8CWRJ4O0SZx28amoDOoWXG8YQK0-2we4IDbU7k"
}