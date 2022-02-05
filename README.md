# techBlog

## Config

In the config folder we have connection.js; connection.js will help us connect the dot.env through sequelize. That's why dotenv is required. 
Dotenv will have the database name, database user and the database password.
The the module must export in sequelize.

## Controllers

Next we have the controllers folder; inside we have an additional folder for the api's. Starting with the api folder we have the blogRoutes.js this will allow the user to create a newBlog and delete a blog. 
Then the module must be exported through the router.

The index.js just helps us to receieve the data from the user or from the blogs. Required we do need express, the user routes and the blog routes in order to retrieve the information provided. Then the module is exported to the router. 

The userRoutes.js will help the user login and logout, if the email or password is incorrect - an error message will pop up prompting the user to try again.

Outside of the api folder, we have the homeRoutes.js and another index.js file. The homeRoutes.js file helps the user get to the homepage as well as the blog page in order to create a new blog. the homeRoutes.js will also allow the user to get the login
The other index.js just requires express and it lets us use the homeRoutes and the apiRoutes. The module must export to the router. 

## db

In the db folder we have the schema.sql file inorder to drop the techblog_db if it exists and create the techblog_db. 

## models

In the models folder we have blog.js, index.js and user.js files. 
The blog.js requires sequelize and the class blog will initiate the id, name, disciption, date created, and the user id. the module will export to the blog. 
Index.js will requir the user and the blog. the user can have as many blogs wantedm and the blog will belong to the user id. This will help the module to export to the user and the blog.
Lastly, the user.js
## public



## seeds



## utils



## view



## server.js


## deployed app