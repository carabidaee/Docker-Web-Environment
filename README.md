# Docker Web Environment

---

## Technologies used

---

* PHP-FPM
* Nginx
* Memcached
* MySQL

## Getting started

---
1. Add an entry to the hosts file: `127.0.0.1 application.local`.
2. Create an env file based on env.example.
3. Install [Docker](https://docs.docker.com/get-docker/).
4. Launch docker.
5. Run the command in the project folder:
```
docker-compose up -d
```
Run the command to stop: 
```
docker-compose down
```
