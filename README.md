Project has 3 tables.

- User (uid,username,email,password)
- Movies (mID,movie_name,director,year)
- Movies_rented (uid,mID,movie_name)

Signing up adds value to the user table. Logging in checks whether it is a valid user.
Renting movies is done by searching the movies table.
Adding selected movies to movies_rented table
