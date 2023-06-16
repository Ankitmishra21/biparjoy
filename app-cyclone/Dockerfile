# Use the official NGINX base image
FROM nginx

# Remove the default NGINX welcome page
RUN rm /usr/share/nginx/html/*

# Copy your HTML files to the NGINX document root
COPY test.html /usr/share/nginx/html/test.html

# Expose port 80 for incoming traffic
EXPOSE 8088

# Start the NGINX server when the container launches
CMD ["nginx", "-g", "daemon off;"]
