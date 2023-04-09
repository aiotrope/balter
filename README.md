# balter

DevOPs with Docker Part 2

Date: 6.4.2023

---

## Exercise 2.1

- docker compose file: [https://github.com/aiotrope/balter/blob/2.1/docker-compose.yml](https://github.com/aiotrope/balter/blob/2.1/docker-compose.yml)

- script answer: [https://github.com/aiotrope/balter/blob/main/script-answers/exercise2_1.txt](https://github.com/aiotrope/balter/blob/main/script-answers/exercise2_1.txt)

- text log: [https://github.com/aiotrope/balter/blob/2.1/text.log](https://github.com/aiotrope/balter/blob/2.1/text.log)

### CLI Commands

```bash
# docker container prune && docker image prune && docker volume prune && docker system prune -a

# start the image from docker compose
$ docker compose up

```

## Exercise 2.2

- docker compose file: [https://github.com/aiotrope/balter/blob/2.2/docker-compose.yml](https://github.com/aiotrope/balter/blob/2.2/docker-compose.yml)

- script answer: [https://github.com/aiotrope/balter/blob/main/script-answers/exercise2_2.txt](https://github.com/aiotrope/balter/blob/main/script-answers/exercise2_2.txt)

## Exercise 2.3

- docker compose file: [https://github.com/aiotrope/balter/blob/2.3/material-applications/docker-compose.yml](https://github.com/aiotrope/balter/blob/2.3/material-applications/docker-compose.yml)

- script answer: [https://github.com/aiotrope/balter/blob/main/script-answers/exercise2_3.txt](https://github.com/aiotrope/balter/blob/main/script-answers/exercise2_3.txt)

### CLI Commands

```bash
# build/rebuild services for prod (full stack) environment; can be view on the browser at http://localhost:3000
$ cd material-applications && docker compose -f docker-compose.yml up --build

# build images of container or re-reun services (full stack); can be view on the browser at http://localhost:3000
$ cd material-applications && docker compose up

# stop the process
$ docker compose down
```

## Exercise 2.4

- docker compose file: [https://github.com/aiotrope/balter/blob/2.3/material-applications/docker-compose.yml](https://github.com/aiotrope/balter/blob/2.3/material-applications/docker-compose.yml)

- script answer: [https://github.com/aiotrope/balter/blob/main/script-answers/exercise2_4.txt](https://github.com/aiotrope/balter/blob/main/script-answers/exercise2_4.txt)

### CLI Commands

```bash
# build/rebuild services for prod (full stack) environment; can be view on the browser at http://localhost:3000
$ cd material-applications && docker compose -f docker-compose.yml up --build

# build images of container or re-reun services (full stack); can be view on the browser at http://localhost:3000
$ cd material-applications && docker compose up

# stop the process
$ docker compose down
```

## Exercise 2.6

- docker compose file: [https://github.com/aiotrope/balter/blob/2.3/material-applications/docker-compose.yml](https://github.com/aiotrope/balter/blob/2.3/material-applications/docker-compose.yml)

- script answer: [https://github.com/aiotrope/balter/blob/main/script-answers/exercise2_6.txt](https://github.com/aiotrope/balter/blob/main/script-answers/exercise2_6.txt)

### CLI Commands

```bash
# build/rebuild services for prod (full stack) environment; can be view on the browser at http://localhost:3000
$ cd material-applications && docker compose -f docker-compose.yml up --build

# build images of container or re-reun services (full stack); can be view on the browser at http://localhost:3000
$ cd material-applications && docker compose up

# stop the process
$ docker compose down
```

## Exercise 2.8

- Postgres and Redis instance in this exercise is not dockerized instead it uses cloud-based db instances from ElephantSql & Redis Enterprise Cloud.

- docker compose file: [https://github.com/aiotrope/balter/blob/2.3a/material-applications/docker-compose.yml](https://github.com/aiotrope/balter/blob/2.3a/material-applications/docker-compose.yml)

- Dockerfile with nginx: 
