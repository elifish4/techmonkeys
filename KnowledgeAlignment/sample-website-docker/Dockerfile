# Use the official Nginx image from Docker Hub
FROM nginx:alpine

# Copy the static website files to the Nginx HTML directory
COPY ./index.html /usr/share/nginx/html/index.html
COPY ./pictures /usr/share/nginx/html/pictures

# Expose port 80 to the outside world
EXPOSE 80

# Start Nginx when the container launches
CMD ["nginx", "-g", "daemon off;"]
