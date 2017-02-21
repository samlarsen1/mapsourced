# mapsourced

docker build -t nginx-mapsourced-web [PATH]
docker run --name mapsourced.com -p 80:80 nginx-mapsourced-web

docker stop mapsourced.com && docker rm mapsourced.com