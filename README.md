# assignment-ram

# install mysql 
docker run -d --name permits-mysql \
  -e MYSQL_ROOT_PASSWORD=root \
  -e MYSQL_DATABASE=permits \
  -p 3306:3306 \
  mysql:8

