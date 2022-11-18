# Dockerfile apache 
FROM httpd:2.4
# Copy app directory to apache
COPY . /usr/local/apache2/htdocs/
# Expose port 8082 (when running container, use -p 8082:80)
EXPOSE 8082:80
# Run apache detached (-D) in the foreground (-DFOREGROUND)
CMD ["httpd", "-D", "FOREGROUND"] 
