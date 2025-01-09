# Prerequisite: Docker installed on your machine
1. Have .env file ready --> refer ".env.example" for this
2. Open a new command line window and go to the project's directory
3. Run the setup: make build
4. create superuser: make superuser
4. Access http://localhost:8080/admin on your browser.
5. Explore API starting here:
```
    http://localhost:8080/v1/api 
```
6. For registration and login we have djoser implementation please refer this documentation for that(https://djoser.readthedocs.io/en/latest/base_endpoints.html):


Other Commands:
- To run the project:
```
make up
```
- To stop the project:
```
make down
```
- To rebuild the project: 
```
make build
```
- To create the migrations for app: 
```
make makemigrations
```
- To run the migrations:
```
make migrate
```
- To output logs:
```
make show-logs
```
- To create superuser:
```
make superuser
```
- To run collectstatic:
```
make collectstatic
```
