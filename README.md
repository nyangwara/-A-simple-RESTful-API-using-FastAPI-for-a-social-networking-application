# -A-simple-RESTful-API-using-FastAPI-for-a-social-networking-application

Description
	Create a simple RESTful API using FastAPI for a social networking application
Functional requirements:
There should be some form of authentication and registration (JWT, Oauth, Oauth 2.0, etc..)
As a user I need to be able to signup and login
As a user I need to be able to create, edit, delete and view posts
As a user I can like or dislike other users’ posts but not my own 
The API needs a UI Documentation (Swagger/ReDoc)

Bonus section (not required):
Use https://clearbit.com/platform/enrichment for getting additional data for the user on signup
Use emailhunter.co for verifying email existence on registration
Use an in-memory DB for storing post likes and dislikes (As a cache, that gets updated whenever new likes and dislikes get added) 


First, we will install FastAPI and set up our basic API structure:
Next, we will set up our authentication system. For this example, we will use JWT authentication.
Now we can create our registration and login routes.
Next, we will create our post routes.
Finally, we will create our like/dislike routes.
To add UI documentation to our API, we can use Swagger or ReDoc. For this example, we will use Swagger.
Now, when we run our API and navigate to the /docs endpoint, we will see our Swagger documentation.
