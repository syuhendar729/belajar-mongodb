# Installer MongoDB
Install mongodb with docker
```
git clone https://github.com/syuhendar729/install-mongodb.git
cd install-mongodb/mongodb
docker-compose -f docker-compose.yml up -d
```
- check if mongodb was successfull install
```
docker container ls
```

If the version mongodb update
- edit file `docker-compose.yml`
- search `image: mongo:4.4`
- you can edit version up to date `image: mongo:<version>`

