# go-http-server

1. Modify Exposed port as you like in the docker file ex : 11222

2. Build Container : 
    docker build -t hello2parikshit/go-http-server .

3. Push to your repo
    docker push hello2parikshit/go-http-server

4. Run your hello world server on your desired port
    docker run -d -p 8080:11222 hello2parikshit/go-http-server
