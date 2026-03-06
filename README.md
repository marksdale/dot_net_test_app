# DotNet Test App

A simple "Hello World" ASP.NET Core web application for testing purposes.

## Building the Docker Image

To build the Docker image, run the following command in the project directory:

```bash
docker build -t dotnet-test-app .
```

## Running the Docker Container

To run the container, use:

```bash
docker run -p 8080:80 dotnet-test-app
```

The app will be available at http://localhost:8080

## Local Development

To run locally without Docker:

```bash
dotnet run
```

The app will be available at https://localhost:5001 (or similar, check the output).