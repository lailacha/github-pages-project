# Learner creator 

## How to setup the project

### Clone the Project
`git clone https://github.com/lailacha/docker_projet_esgi`

### Build docker container
`docker-compose up -d`  </br> </br>
This command will create the docker container and its images (Apache server, Phpmyadmin, MYSQL)

### Define environment variables

You need to define some variables to use databases. </br>

1. Create php file _conf.inc.php_
2. define variables into the file like that:

```<?php

define("DBDRIVER", "mysql");
define("DBUSER", "root");
define("DBPWD", "password");
define("DBHOST", "database");
define("DBNAME", "database_name");
define("DBPORT", "3306");
define("DBPREFIXE", "esgi_");
```

### Got to **_http://localhost:8080/_**
The project is ready :tada:
