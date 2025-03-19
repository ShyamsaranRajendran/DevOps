# Use official Node.js image
FROM node:20

# Set the working directory
WORKDIR /app

# Copy package.json and install dependencies
COPY package.json .
RUN npm install

# Copy the app files
COPY . .

# Expose port
EXPOSE 3000

# Start the application
CMD ["node", "index.js"]
