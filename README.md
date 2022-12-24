# jscore_4.4.9

POST 
```
  https://blog.kata.academy/api/users
```
BODY 
```
  {
    "user": {
      "username" : "kibni14",
      "email": "kibni14@gmail.com",
      "password": "1234567"
    }
  }
```
RESPONSE
```
  {
      "user": {
          "username": "kibni14",
          "email": "kibni14@gmail.com",
          "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzYTc1OWI4MjA3NTk0MWIwMGU0N2RhYiIsInVzZXJuYW1lIjoia2libmkxNCIsImV4cCI6MTY3NzA5NTg2NCwiaWF0IjoxNjcxOTExODY0fQ.wKNS63wNNvc8odmzGiugJnG2rkixegeM46OFGV0TWHI"
      }
  }
```

POST  
```
  https://blog.kata.academy/api/users/login
```
BODY 
```
    {
    "user": {
      "email": "kibni14@gmail.com",
      "password": "1234567"
    }
  }
```
RESPONSE 
```
  {
    "user": {
        "username": "kibni14",
        "email": "kibni14@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzYTc1OWI4MjA3NTk0MWIwMGU0N2RhYiIsInVzZXJuYW1lIjoia2libmkxNCIsImV4cCI6MTY3NzA5NjAwMCwiaWF0IjoxNjcxOTEyMDAwfQ.6s4AshUtwtYAijwkc2MOPIj-MNXGvK7oY2cibmME0yg"
    }
}
```

GET 
```
  https://blog.kata.academy/api/user
```
HEADER 
```
  Autorization : eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzYTc1OWI4MjA3NTk0MWIwMGU0N2RhYiIsInVzZXJuYW1lIjoia2libmkxNCIsImV4cCI6MTY3NzA5NjAwMCwiaWF0IjoxNjcxOTEyMDAwfQ.6s4AshUtwtYAijwkc2MOPIj-MNXGvK7oY2cibmME0yg
  ```
RESPONSE
```
{
    "user": {
        "username": "kibni14",
        "email": "kibni14@gmail.com",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYzYTc1OWI4MjA3NTk0MWIwMGU0N2RhYiIsInVzZXJuYW1lIjoia2libmkxNCIsImV4cCI6MTY3NzA5NjA4NCwiaWF0IjoxNjcxOTEyMDg0fQ.SSnHZe4rVRVdngqRnLchlSNqujA1koqJ8pBQ-sDod3w"
    }
}
```

  
