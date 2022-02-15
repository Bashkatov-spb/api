# api



POST - https://kata.academy:8021/api/users

body/raw 
{
  "user": {
    "username": "AnatolyBashkatov",
    "email": "aaabbb@mail.ru",
    "password": "passWord123"
  }
}

POST - https://kata.academy:8021/api/users/login

body/raw 
{
  "user": {
    "email": "aaabbb@mail.ru",
    "password": "passWord123"
  }
}

GET - https://kata.academy:8021/api/user

{
    "user": {
        "username": "anatolybashkatov",
        "email": "aaabbb@mail.ru",
        "token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpZCI6IjYyMGI5ZGJhNjkxNzQwMjEwMDhmNDk3YSIsInVzZXJuYW1lIjoiYW5hdG9seWJhc2hrYXRvdiIsImV4cCI6MTY1MDExMzc3NCwiaWF0IjoxNjQ0OTI5Nzc0fQ.mJ0G9k2j4YoEJW7XNBuD-KWwHjIIDh8uoJxYrQTkNiA"
    }
}

GET - https://kata.academy:8021/api/profiles/anatolybashkatov

{
    "profile": {
        "username": "anatolybashkatov",
        "image": "https://static.productionready.io/images/smiley-cyrus.jpg",
        "following": false
    }
}
