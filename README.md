# Pet-Store

An app of the management of pets with Python Flask framework and Jinja2 template framework. Pet data are stored in MySQL database. App and database are connected by PyMySQL. Swagger is used for Restful API specification. This app is deployed by Docker. To run it, put docker-compose.yml file and db folder including SQL schema in the same path. Then use the command:

    docker-compose up
    
It will pull two images, one is app image and the other is MySQL 5.7 image. After the app runs, in the browser type:

    http://0.0.0.0:5000/
    
Pet store will be shown.
