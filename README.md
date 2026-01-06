Docker execution steps:

1. Open the terminal and navigate to the directory containing the index.html file and the Dockerfile.

2. docker build -t todo-app .
(Check inside Docker IMAGE)
    
3. docker run -d -p 8080:80 --name todo-container todo-app
(Check inside Docker CONTAINER)

4. docker start todo-container

5. docker stop todo-container
