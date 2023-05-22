# Assign official Apache image as base
FROM httpd:latest

# Copy local custom index.html file into container
COPY ./index.html/ /usr/local/apache2/htdocs 

# Expose listening port
EXPOSE 8080

# Command to start Apache
CMD ["httpd-foreground"]

