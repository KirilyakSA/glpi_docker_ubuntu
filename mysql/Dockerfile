FROM docker.io/mysql
#
ENV MYSQL_RANDOM_ROOT_PASSWORD yes
ENV MYSQL_DATABASE glpi
ENV MYSQL_USER sergey
ENV MYSQL_PASSWORD genius123
#
VOLUME /var/lib/mysql
#
EXPOSE 3306
#
COPY src/*.sql /docker-entrypoint-initdb.d/

