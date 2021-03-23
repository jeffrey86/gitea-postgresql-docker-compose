# Gitea and Postgres running with Docker Compose

## How to start

---

1. Run `docker-compose up -d` to start gitea and postgresql.
2. To check that your gitea application is running enter url `http://localhost:3000`.
3. Set up and Initial your gitea application at `http://localhost:3000`, on DataBase section choose PostgreSQL, Host: `db:5432`, User:`gitea`, Password:`gitea`, Database Name:`gitea`. you can define these on `docker-compose.yaml`.

## How to close

---

1. Run `docker-compose stop` to stop gitea and postgresql containers.
2. Run `docker-compose rm -f` to remove gitea and postgresql containers.
3. Run `./clean.sh` if you want remove gitea and postgresql all datas.

## Reference

---

1. https://docs.gitea.io/en-us/install-with-docker/
2. https://github.com/hui000444/gogs-postgresql-docker-compose.git
