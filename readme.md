# sagyo
## build
```
sudo docker build -t --no-cache=true --rm=true web web
```
## run
```
sudo docker run --privileged -itd -p 80:80 -t web
```
