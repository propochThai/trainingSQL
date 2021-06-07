docker-compose run db sh -c "mysql -h appsDB -P 3306 -u root -phelloworld -e 'create database ORG;'"

docker-compose run db sh -c "mysql -h appsDB -P 3306 -u root -phelloworld -e 'SHOW DATABASES'"