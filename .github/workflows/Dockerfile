# Use an official MongoDB as the base image
FROM mongo:latest

# Set the working directory in the container
WORKDIR /data

# Copy MongoDB configuration file to the container
COPY mongod.conf /etc/mongod.conf

# Expose MongoDB port
EXPOSE 27017

# Set the command to run when the container starts
CMD ["mongod", "--config", "/etc/mongod.conf"]
