# Dockerfile nginx
FROM nginx:alpine

# Copy app directory to nginx
COPY . /usr/share/nginx/html

# Expose port 8082 (when running container, use -p 8082:80)
EXPOSE 8082:80

# Run nginx
CMD ["nginx", "-g", "daemon off;"]
