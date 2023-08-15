# Use an official nginx image as a base
FROM nginx:alpine

# Remove the default Nginx configuration
RUN rm /etc/nginx/conf.d/default.conf

# Copy our custom configuration
COPY nginx.conf /etc/nginx/conf.d/

# Copy frontend files into the container
COPY . /usr/share/nginx/html
