# nodejs-rest-api
API


http://localhost:3000/users/register 
![alt text](Img/Register.png)

http://localhost:3000/users/authenticate 

![alt text](Img/Authenticate.png)


 POST    http://localhost:3000/movies 
![alt text](Img/PostMovies.png)
JWT token received in above request will be used to access protected movie routes. We will pass token in header with key=x-access-token and value=jwt token 
![alt text](Img/PostMovies1.png)




 GET  http://localhost:3000/movies 
![alt text](Img/GetMovies.png)


http://localhost:3000/movies/5bffd19b0262b02d9cbffa44 
![alt text](Img/GetMovieswithToken.png)


http://localhost:3000/movies/5bffd19b0262b02d9cbffa44 
![alt text](Img/PutMovieswithtoken.png)


http://localhost:3000/movies/5bffd19b0262b02d9cbffa44 
![alt text](Img/deleteMovies.png)

http://localhost:3000/account 
![alt text](Img/Account.png)
