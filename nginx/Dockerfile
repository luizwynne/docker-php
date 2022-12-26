FROM nginx:latest

#- ./nginx/conf.d/default.conf:/etc/nginx/conf.d/default.conf
COPY ./nginx/conf.d/default.conf /etc/nginx/conf.d/default.conf

# PUBLIC DIRECTORY WHERE THE PHP IS
COPY ./app/public /var/www/html/public