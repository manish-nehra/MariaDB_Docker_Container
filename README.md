# MariaDB_Docker_Container
We have the MariaDB database in the center where almost all the other services will depend. Adminer and Phymyadmin are both database management tools that we can use to execute crud operations into the database.

This project is a demonstration of how docker works.

 - MariaDB, Phpmyadmin, Adminer

## Requirements:

- RHEL8 with Docker installed

## MariaDB, Phpmyadmin, Adminer

MariaDB database is created and Phpmyadmin and adminer connects to it.


## How to run?

Once you have docker and docker-compose installed, go to the root of this project and execute:

```sh
// start the services
docker-compose up -d --build

// stop the services
docker-compose down

// if you want to run the services again, there is no need for the --build parameter
docker-compose up -d
```

And the following URLs should be available:

 - Adminer - http://localhost:8001
 - Phpmyadmin - http://localhost:8002
