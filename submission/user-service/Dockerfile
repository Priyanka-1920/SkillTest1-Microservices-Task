# Use Node.js LTS version
FROM node:18

# Set working directory
WORKDIR /app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the rest of the code
COPY . .

# Expose the port for this service
EXPOSE 3000

# Start the service
CMD ["node", "app.js"]
