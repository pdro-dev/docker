# Dockerfile nginx
FROM nginx:alpine

# Copy app directory to nginx
COPY . /usr/share/nginx/html

# Expose port 82
EXPOSE 8082:80

# Run nginx
CMD ["nginx", "-g", "daemon off;"]
