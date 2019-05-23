FROM debian
ADD debian.list /etc/apt/sources.list.d/
RUN apt-get update && apt-get -y upgrade && apt -y install nginx && apt-get clean && \
    cd /var/www/ && rm -rf ./* && \
    mkdir -p igritt.com/images && \
    chmod -R 755 /var/www/igritt.com/ && \
    useradd Victoria && groupadd Filippova && usermod -aG Filippova Victoria && \
    chown -R Victoria:Filippova /var/www/igritt.com/ && \
    sed -i 's/\/var\/www\/html/\/var\/www\/igritt.com/g' /etc/nginx/sites-enabled/default && \
    sed -i 's/user www-data/user Victoria/g' /etc/nginx/nginx.conf
ADD index.html /var/www/igritt.com/
ADD image.jpg /var/www/igritt.com/images/
CMD ["nginx", "-g", "daemon off;"]
