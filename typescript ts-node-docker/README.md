docker build -t ts-node .
docker run -v "$PWD"/src:/app/src -p 3000:3000 -p 5858:5858 ts-node