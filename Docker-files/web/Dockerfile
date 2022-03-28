FROM nginx
LABEL "Project"="reaction"
LABEL "Author"="vishal"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/reactionapp.conf
