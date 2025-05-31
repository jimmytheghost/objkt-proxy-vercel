# Use Node.js base image
FROM node:18

# Create app directory
WORKDIR /app

# Copy files
COPY . .

# Install dependencies
RUN npm install

# Expose port Fly expects
EXPOSE 8080

# Start the proxy server
CMD [ "node", "api/index.js" ]
