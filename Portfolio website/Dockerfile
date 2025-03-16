FROM nginx:alpine

# Set working directory
WORKDIR /usr/share/nginx/html

# Copy the portfolio files into the container
COPY Portfolio.html index.html

# Expose port 80 for Fly.io
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]
