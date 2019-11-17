[![Build Status](https://travis-ci.com/Steingrimurjonsson/CA3G3.svg?branch=master)](https://travis-ci.com/Steingrimurjonsson/CA3G3)

### CA3 - Group 3
- This is our backend of the CA3 project. In order to quick start from this project you will need to clone, change path in pom file, change db path on your tomcat and run the populator so you can get users on your db.
- Here is our API endpoints.  Use Postman

- POST ruffsacks.com/CA3G3/api/info/login (here you need to send username and password in json format. If the input is right, you will get a token that you can use to access GET ruffsacks.com/CA3G3/api/info/user or ruffsacks.com/CA3G3/api/info/admin)
- GET ruffsacks.com/CA3G3/api/info/all This shows you how many users that are made on the database.
- GET ruffsacks.com/CA3G3/api/info/planets/(ENTER ID) or people/ , vehicles/, films/, starships/ This will give you json data about the selected topic from swapi.com

-Link to the frontend of the CA3 https://github.com/Steingrimurjonsson/CA3G3F
