# Use the official Nginx image
FROM nginx:1.25.3

# Copy the custom Nginx configuration
COPY ./nginx/nginx.conf /etc/nginx/nginx.conf

CMD ["nginx", "-g", "daemon off;"]
