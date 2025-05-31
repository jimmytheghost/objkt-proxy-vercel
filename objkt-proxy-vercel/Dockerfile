# Use official Node.js image
FROM node:18

# Set working directory
WORKDIR /app

# Copy files
COPY . .

# Install dependencies
RUN npm install

# Start the server
CMD ["npm", "start"]
