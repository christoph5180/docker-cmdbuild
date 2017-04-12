
# CMDBuild in Docker (Last version 2.4.3)

![cmdbuild_logo](http://www.cmdbuild.org/logo.png)

### Last update : 24/02/2017 . Add cmdbuild 2.4.3 and update readme
* **From cmdbuild 2.4.0 I will stop adding the docker-compose file with the link option**
* **From 10/2016, I will stop to add the tomcat 6 dockerfiles.**
* **Please open issues on [github](https://github.com/Quentinvarquet/docker-cmdbuild/issues)**

**I recommend to use the latest version of cmdbuild with Tomcat 7**


### CMDBuild

[CMDBuild](http://www.cmdbuild.org/en) is a web environment in which you can configure custom solutions for IT Governance, or more generally for asset management.

### Docker

[Docker](https://www.docker.com/) allows you to package an application with all of its dependencies into a standardized unit for software development.

More information : 

* [What is docker](https://www.docker.com/what-docker)
* [How to Create a Docker Business Case](https://www.brianchristner.io/how-to-create-a-docker-business-case/)

### Information

This is the unofficial (updated !) repository with all the versions of cmdbuild. You can choose wich version of tomcat you would like to use for your project.

I will update the repository every time there is a new version of cmdbuild available



### Supported tags and respective Dockerfile links




#### Example

```bash
docker run --name cmdbuild -p 8080:8080 -d quentinv/cmdbuild:t7-2.1.4 
```

* **t7** : Version of tomcat
* **2.1.4** : Version of cmdbuild


You want the last version ?

```bash
docker run --name cmdbuild -p 8080:8080 -d quentinv/cmdbuild:latest
```

#### Tags


### Docker Compose

I created a docker-compose.yml for every version of cmdbuild. (tomcat + postgresql). 

#### Docker Compose files


### Network

**Tomcat 7 with java 8**

 * [```t7-2.4.3(latest)```](https://github.com/Quentinvarquet/docker-cmdbuild/blob/master/tomcat7/t7-2.4.3/Docker-Compose/Network/docker-compose.yml)


#### Database configuration

##### Networks

* **Host:** pgsql_container_name
* **Port:** 5432
* **Username:** postgres
* **Password:** your_postgres_password
* **Database where stored in ./db folder
* **CMDB config where stored in ./config folder


## Please open issues on [github](https://github.com/christoph5180/docker-cmdbuild/issues)
