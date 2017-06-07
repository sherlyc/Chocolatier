# Chocolatier
A Practice on Project Design &amp; TDD 

## API Documentation

## List of API

|Task|Method|Requires Authentication|
|-|-|-|
|Create a new user|POST|no|
|Create a new user profile|POST|yes|
|Login as a user|POST|yes|
|Return a list of products|GET|no|
|Return a list of orders by a specific user|GET|yes|
|Return an order detail by a specific user|GET|yes|


### Create a new user

|Method|Endpoint|Usage|Returns|
|-|-|-|-|
|POST|/api/users/signup|Create a user|boolean|

The post object must take the form:

    {
      "username": "someone",
      "password": "1234",
      "email": "someone@gmail.com"
    }



