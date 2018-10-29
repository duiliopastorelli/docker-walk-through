# docker-walk-through
This repo is functional to the article "A little dive into Docker" (https://medium.com/@mezgec.danilo/docker-cli-dockerfile-and-docker-compose-from-scratch-13291656a0ca).

For use this repo follow the following instructions:

```
npm install
docker-compose up
```

On the terminal the walk-through-app should attempt to connect to the database,
fail and retry. Eventually, when the database is ready, the connection will 
be established.
