# Use Node.js image
FROM node:19-alpine

# Set working directory
WORKDIR /app

# Copy package.json and package-lock.json
COPY package*.json .

# Install dependencies
RUN npm install

# Copy application code
COPY . .

# Expose port
EXPOSE 3003
EXPOSE 8005

# Start the application
CMD ["npm", "start"]
