# Base image
FROM node:12.18-alpine

# Specify an environment variable
ENV NODE_ENV=production

# Specify a working directory
WORKDIR /usr/src/app

# Copy contents of current directory into WORKDIR
COPY . .

# Install dependencies
RUN npm install

# Expose the port the app runs on
EXPOSE 3000

# Command to run the app
CMD ["npm", "start"]