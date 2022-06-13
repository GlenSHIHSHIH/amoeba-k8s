FROM mysql:8.0.26
COPY ./config/mysql_conf/mysql.cnf /etc/mysql/conf.d /\
    ./config/mysql_init/install_db.sql /docker-entrypoint-initdb.d /

ENV MYSQL_ROOT_PASSWORD: 1qaz@WSX \
    MYSQL_USER: amoeba \
    MYSQL_PASSWORD: 1qaz@WSX \
    MYSQL_DATABASE: amoeba