You can see the output: https://design-string-assignment-one.netlify.app/

# Ninja React Coding Challenge

**Please make sure to go through the below details before cloning the repository**

**Goal**: Dynamic page development & Integration, as per the below details

**Design Figma URL** - https://www.figma.com/file/6xhuursXAVWZiZlgH367HS/React-Ninja-Template

**Design consists of two pages**
- Login Page
- Home Page

**Scope of work**
- User should be able to successfully login using the email and password provided in the API details
- After login user should land on the Home page and the Users list should be loaded from the Users List API  
- Pagination is add on

**API Details**

1. Login API - POST - https://reqres.in/api/login 

_Sample Request_
**Login With these credentials**
```
{
    "email": "eve.holt@reqres.in",
    "password": "cityslicka"
}
```

2. Users Listing API - GET - https://reqres.in/api/users?page=1

_Sample Response_
```
{
    "page": 1,
    "per_page": 6,
    "total": 12,
    "total_pages": 2,
    "data": [
        {
            "id": 1,
            "email": "george.bluth@reqres.in",
            "first_name": "George",
            "last_name": "Bluth",
            "avatar": "https://reqres.in/img/faces/1-image.jpg"
        },
        {
            "id": 2,
            "email": "janet.weaver@reqres.in",
            "first_name": "Janet",
            "last_name": "Weaver",
            "avatar": "https://reqres.in/img/faces/2-image.jpg"
        }]
}
```

[![Run in Postman](https://run.pstmn.io/button.svg)](https://app.getpostman.com/run-collection/5dfbcd9789e5ec3722df?action=collection%2Fimport)

_APIs made for developers and designers by [Ben Howdle](https://benhowdle.im/)_


**Other Assets**
Font - https://fonts.google.com/specimen/Roboto

Once you have completed the development, Please raise the pull request from your forked repository, and your work will be reviewed against:
- **Design vs Developed screens**
- **Coding Standards**
- **Readability & Reusability of code**
- **Code Quality and Size**

_This repository is meant to facilitate the interview process @Designstring and only referred candidates for the interview process are requested to access_

Happy Coding!!!
