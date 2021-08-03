# README

Just add application to app directory and build the image

```docker build -t fastapi-img .```


docker run -d --name fastapi-container -p 80:80 fastapi-img

http://127.0.0.1/items/5?q=somequery 

http://127.0.0.1/docs