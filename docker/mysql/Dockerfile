FROM mysql:8
LABEL Konstantin Lysenko <gameron27@gmail.com>

ENV MYSQL_ROOT_PASSWORD wordpress
ENV MYSQL_DATABASE wordpress

ADD backup.sql /docker-entrypoint-initdb.d/

# ADD wordpress_data.sql /docker-entrypoint-initdb.d/