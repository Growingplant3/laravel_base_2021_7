FROM mysql/mysql-server:8.0.25

ENV MYSQL_DATABASE=laravel_project \
  MYSQL_USER=phpuser \
  MYSQL_PASSWORD=secret \
  MYSQL_ROOT_PASSWORD=secret \
  TZ=Asia/Tokyo

COPY ./my.cnf /etc/my.cnf
RUN chmod 644 /etc/my.cnf