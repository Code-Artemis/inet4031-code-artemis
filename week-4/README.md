# Week 4: Docker Compose Stack

Flask app and Postgres database run together with Docker Compose.

## Run it

1. Copy `.env.example` to `.env` and fill in real values.
2. From `week-4/`, run `docker compose up -d --build`.
3. Open http://localhost:8080.

The database data lives in the `db-data` volume, so it survives `docker compose down`.
