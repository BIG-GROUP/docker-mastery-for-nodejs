# fill in the blanks to dockerize this node app
FROM

EXPOSE

RUN

WORKDIR

COPY

RUN

COPY

ENTRYPOINT

CMD


# Example
# Use an official Node.js runtime as a parent image
FROM node:14-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy the package.json and package-lock.json files into the container
COPY package*.json ./

# Install app dependencies
RUN npm install

# Copy the rest of the application code into the container
COPY . .

# Expose the port that the app listens on
EXPOSE 3000

# Start the app
CMD [ "npm", "start" ]
