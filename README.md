# TraefikSetup

## Requirements

Clone the HeightMap repository into a folder parallel to the TraefikSetup repository and build the height_map_docker container. 

Create a file .env in this repository folder containing your email address and the host/domainname pointing to this service. 

The format looks like 
```
MY_EMAIL=me@my-provider
MY_DOMAIN=my-domain
```

## Startup

Run 
```
docker-compose up -d
``` 
for startup and 
```
docker-compose down
``` 
for shutdown.
