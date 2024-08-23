# Dockerfile for Go Application 1

# Use the official Golang image as the base image
FROM golang:1.22-alpine

# Set the Current Working Directory inside the container
WORKDIR /app

# Copy the Go application code to the container
COPY . .

# Build the Go application
RUN go build -o app

# Expose the application port (replace 8080 with your app port if different)
EXPOSE 8080

# Command to run the executable
CMD ["./app"]
