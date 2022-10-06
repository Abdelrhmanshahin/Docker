
# Building an Apache Web Server through a Dockerfile:

```
Step 1: Create a directory for Apache server files
$ mkdir apache_folder
```
Step 2: Building a Dockerfile
```
Step 3: Tag and build the Docker image
$ docker build -t apache_image:1.0 .
```
Step 4: Run the Docker image as a container
docker run --name myapache -d -p 8080:80 apache_image:1.0
```
Step 5: Review the online presence of Apache Server