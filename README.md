# Blynk Server Dockerized (0.41.0)

<p align="center"><img src="logo.png" alt="logo"></p>

### BUILD

```bash
docker build -t blynk .
```

### RUN

```bash
docker run -d -v ${PWD}/data:/data -p 8080:8080 -p 8441:8441 -p 8442:8442 -p 9443:9443 blynk
```

now you can open the following URL to access the admin page

```
https://YOUR_SERVER_IP:9443/admin
```

default user
```
user: admin@blynk.cc
password: admin
```

**PLEASE CHANGE THE DEFAULT USER !**


## License

MIT License - 2018 - [Dominic Kolbe](https://dominickolbe.dk)