# Use the official Nginx image as the base image
FROM nginx:alpine

# Copy the contents of the frontend directory into the Nginx server's default HTML directory
COPY ./index.html /usr/share/nginx/html/index.html
COPY ./profile-picture /usr/share/nginx/html/profile-picture

# Expose port 80 to the outside world
EXPOSE 80

# Command to run the Nginx server
CMD ["nginx", "-g", "daemon off;"]
