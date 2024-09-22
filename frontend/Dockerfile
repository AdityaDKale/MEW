# Use Node.js 16 as the base image
FROM node:16

# Set working directory to /app
WORKDIR /app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the application
COPY . .

# Expose port 3000
EXPOSE 3000

# Run the command to start the development server
CMD ["npm", "start"]
