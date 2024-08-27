FROM mysql:8.0.33
LABEL "Project"="NVR_Vprofile"
LABEL "Author"="NVR"

ENV MYSQL_ROOT_PASSWORD="nvrvprodbpass"
ENV MYSQL_DATABASE="accounts"

ADD db_backup.sql docker-entrypoint-initdb.d/db_backup.sql