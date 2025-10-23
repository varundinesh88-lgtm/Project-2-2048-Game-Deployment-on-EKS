# Use a lightweight NGINX image to serve the 2048 game
FROM nginx:alpine

# Copy all 2048 files into the default nginx web directory
COPY . /usr/share/nginx/html

# Expose the default HTTP port
EXPOSE 80

# Run nginx in the foreground
CMD ["nginx", "-g", "daemon off;"]

