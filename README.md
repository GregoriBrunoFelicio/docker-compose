# 📦 Docker Compose Stack - MongoDB, Redis, RabbitMQ and PostgreSQL

This repository contains a `docker-compose.yml` file with four essential services for local development:

- 🐳 MongoDB
- 🚀 Redis
- 🐰 RabbitMQ
- 🐘 PostgreSQL

---

## ▶️ How to Use

1. **Clone the repository**

```bash
git clone https://github.com/your-username/docker-stacks.git
cd docker-stacks
````

2. **Start the containers**

```bash
docker-compose up -d
```

3. **Access the services**

| Service    | URL / Port               | Username / Password  |
| ---------- | ------------------------ | -------------------- |
| MongoDB    | `localhost:27017`        | `root` / `example`   |
| Redis      | `localhost:6379`         | –                    |
| RabbitMQ   | `http://localhost:15672` | `guest` / `guest`    |
| PostgreSQL | `localhost:5432`         | `admin` / `admin123` |

---

## 🧼 Stop the containers

```bash
docker-compose down
```

---

## 📁 Volumes

* `mongo_data`
* `redis_data`
* `postgres_data`

---

## 🌐 Network

All services are connected to the `devnet` network and can talk to each other using:

* `mongo`
* `redis`
* `rabbitmq`
* `postgres`

---

## 🛠 Requirements

* Docker
* Docker Compose (`docker-compose` or `docker compose`)
