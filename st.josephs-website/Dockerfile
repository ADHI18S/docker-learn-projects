# Step 1: Use an official Nginx base image
FROM nginx:alpine

# Step 2: Set the working directory inside the container
WORKDIR /usr/share/nginx/html

# Step 3: Copy your application files into the container
COPY ./files /usr/share/nginx/html

# Step 4: Expose port 80 (default port for Nginx)
EXPOSE 80

# Step 5: Start Nginx server (this is the default command, so it's optional to add this line)
CMD ["nginx", "-g", "daemon off;"]
