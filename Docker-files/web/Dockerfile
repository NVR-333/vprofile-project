FROM nginx 
LABEL "Project"="NVR_Vprofile"
LABEL "Author"="NVR"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/ngnix/conf.d/vproapp.conf
