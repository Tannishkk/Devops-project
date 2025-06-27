# Use official Node.js image
FROM node:18

# Create app directory
WORKDIR /app

# Copy files
COPY . .

# Install dependencies (none, but npm init still expected)
RUN npm install

# Expose port
EXPOSE 3000

# Start the server
CMD ["npm", "start"]
