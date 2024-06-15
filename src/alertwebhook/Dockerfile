# Use the official GoLang image as the base image
FROM golang:1.16-alpine

# Set the working directory inside the container
WORKDIR /app

# Copy the source code into the container
COPY ./src/alertwebhook .

# Build the Go application
RUN go build -o app

# Set the command to run the application
CMD ["./app"]