FROM node:18-alpine

WORKDIR /app

# Copy package files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy application code
COPY . .

# Expose API port
EXPOSE 4000

# Start the server
CMD ["npm", "start"]