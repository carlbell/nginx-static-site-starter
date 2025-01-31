FROM nginx:alpine

# Ensure /workspace exists for VS Code
RUN mkdir -p /workspace

# Set the correct working directory for VS Code
WORKDIR /workspace

# Copy the site files to the correct Nginx directory
COPY src /usr/share/nginx/html

