#Docker build 
...
git clone https://github.com/hongjs0215/dockertesthjs.git
cd dockertesthjs
docker build --rm -t hongjs0215/ut .
docker images

# Docker run 
```
docker run -it --name ut -v C:\\Users\\kitri\\df:/df --rm hongjs0215/ut
...
