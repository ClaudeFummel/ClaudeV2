# Hello World Node.js Docker App

A simple Node.js website that displays "Hello World" in a Docker container.

## Build and Run

```bash
docker build -t claudev2 .
docker run -p 3000:3000 claudev2
```

Visit http://localhost:3000 to see "Hello World"