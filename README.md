# DevOps Assignment

## Description
This is a simple Node.js application containerized with Docker.

## How to Run
1. **Build the Image:**
   ```bash
   docker build -t node-hello-world .
   ```

2. **Run Container:**
   ```bash
   docker run -d -p 3000:3000 node-hello-world
   ```

3. **Bonus (Docker Compose):**
   ```bash
   docker-compose up -d
   ```

## Access
Visit: http://localhost:3000

