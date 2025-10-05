# Hello Captain Docker Image

This project provides a simple Docker image that prints "Hello, Captain!" to the console when run.  
It is based on the lightweight Alpine Linux image.
Here is the project URL:
https://github.com/hpaharia11/Roadmap-projects/

Project URL
This is a local Docker project from the roadmap.sh, You can find the project details https://roadmap.sh/projects/basic-dockerfile.

## Usage

1. **Build the Docker image**

   Open a terminal in the root directory containing the `Dockerfile` and run:

   ```sh
   docker build -t hello-captain .
   ```

2. **Run the Docker container**

   Run the image with:

   ```sh
   docker run hello-captain
   ```

   You should see the output:

   ```
   Hello, Captain!
   ```

## Dockerfile

```dockerfile
FROM alpine:latest
CMD echo "Hello, Captain!"
```

## Description

- **Base Image:** `alpine:latest`
- **CMD:** Prints "Hello, Captain!" to the console and exits.

## License

This project is provided for educational/demo purposes.  
Feel free to use and modify as needed.
