A quick way to install nextcloud with MariaDB.

How?

Easy.

Create a folder with mkdir,

cd into that folder,

put the docker-compose.yml there,

type "docker-compose up -d"

and then in the web ui (your ip here):8080 


Fill out the admin account info

Use Database: MySQL/MariaDB

Database user: nextclouduser

Password: nextcloudpass

Database name: nextcloud

Host: db:3306 (Docker internal network lets the app find the db by service name)

Thats it!

Enjoy!
