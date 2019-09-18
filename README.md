# laradock-light
Configured for many projects docker environment with php, apache, redis and mysql. docroot in container set to /home/user/code.

- clone to ~/code
- run `docker-compose up -d apache2 redis mariadb workspace` in laradock folder
- all projects directories in ~/code will be served at localhost:80
