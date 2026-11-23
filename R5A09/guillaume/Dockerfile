FROM fedora:latest
RUN dnf -y install httpd
COPY index.html /var/www/html/
USER root
CMD ["httpd", "-D", "FOREGROUND"]
