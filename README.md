# Docker-nginxWebsite

A sample website that I created as a personal project hosted on an NGINX server using Docker. 
This will create a container which runs an NGINX webserver which hosts the HTML files for the website. 


Instructions:
```
- cd into the nginxsample folder
- docker build -t <name_of_image>:<tag> .
- docker run -d --name <name_of_container> -p 8080:80 <name_of_image>:<tag>

```

Once these instructions are completed, visit the ``` localhost:8080 ``` in the browser.


Instructions to Stop & Destroy:
```
- docker stop <name_of_container>
- docker system prune -a

```
