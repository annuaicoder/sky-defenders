# Use an official lightweight Nginx image as a base
FROM nginx:alpine

# Set the working directory inside the container
WORKDIR /usr/share/nginx/html

# Copy the content of the local src directory to the working directory
COPY . .

# Expose the port that Nginx will listen on
EXPOSE 80

# Command to run Nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]

