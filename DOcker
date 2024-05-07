# Copy custom configuration file from the host into the container
COPY nginx.conf /etc/nginx/nginx.conf

# Copy static HTML files (if any) from the host into the container
COPY html /usr/share/nginx/html

# Expose port 80 to allow outside access
EXPOSE 80

# Start Nginx server when the container launches
CMD ["nginx", "-g", "daemon off;"]
