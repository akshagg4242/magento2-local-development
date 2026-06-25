# Magento 2 Docker Setup Guide

## Step 1 — Clone Repository

```bash
git clone https://github.com/akshagg4242/magento2-local-development.git
cd magento2-local-development
```

---

## Step 2 — Verify Installation

Check:

```bash
docker --version
docker compose version
composer --version
```

---

## Step 3 — Start Containers

```bash
docker compose up -d
```

Verify:

```bash
docker ps
```

---

## Step 4 — Open Magento

Open:

http://localhost

Verify storefront loads successfully.

---

## Step 5 — Access Admin Panel

Open:

http://localhost/admin

Login using configured credentials.

---

## Step 6 — Verify Services

Check:

- Magento service
- MySQL service
- Elasticsearch service

Command:

```bash
docker ps
```

---

## Step 7 — Stop Environment

```bash
docker compose down
```

---

## Troubleshooting

Logs:

```bash
docker compose logs
```

Restart:

```bash
docker compose restart
```

Remove containers:

```bash
docker compose down -v
```

---

## Status

Magento 2 environment configured and verified successfully.
