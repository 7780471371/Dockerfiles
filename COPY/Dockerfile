FROM nginx
#removing default html file
RUN rm -rf /usr/share/nginx/html/index.html
#files should be availbe in current directory,when docker file exit
COPY index.html /usr/share/nginx/html/index.html