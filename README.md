### Dockerfile for Sudoku Web App under Nginx Reverse Proxy

# 1. Cloning Git 
`git https://github.com/hotdeveloper/sudoku-nginx-docker.git`

# 2. Build Docker image
`docker build -t sudoku-ws:level-4`

# 3. Running the container
`docer run -d -it -p 8080:8080 sudoku-ws:level-4`

# 4. Run the app
in CLI 
`curl http://localhost:8080/sudoku/board`
in Web browser
`localhost:8080`
