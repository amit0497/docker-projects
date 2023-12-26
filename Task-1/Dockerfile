# Taking Base Image
FROM alpine:latest

#Copy the script to container
COPY . /usr/src/app/

#Set the working directory
WORKDIR /usr/src/app/

# Make the script executable
RUN chmod +x hello_world.sh

# Command to run when the container starts
CMD ["./hello_world.sh"]