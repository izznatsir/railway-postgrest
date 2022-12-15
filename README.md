---
title: Postgrest
description: A PostgREST instance with a PostgreSQL database.
tags:
    - postgresql
    - postgrest
---

# PostgREST template

This template sets up a [PostgREST](https://postrest.org) instance with a
[PostgreSQL](https://www.postgresql.org/) database.

[![Deploy on Railway](https://railway.app/button.svg)](https://railway.app/new/template/Ya1Bae?referralCode=ItHqgg)

## ✨ Features

-   Postgres
-   PostgREST

## 💁‍♀️ How to use

-   Click the `Deploy on Railway` button
-   Set `PGRST_DB_URI` environment variable to `${{ DATABASE_URL }}`.
-   Set `PGRST_JWT_SECRET` environment variable to secure your endpoints.
-   Set `PORT` environment variable to `3000`.
-   Set `PGRST_SERVER_PORT` environment variable to `${{ PORT }}`.
-   Set a domain to expose your app.

You can configure your PostgREST instance with some other
[environment variables](https://postgrest.org/en/stable/configuration.html#list-of-parameters).

## 📝 Notes

-   This starter automagically provisions a PostgreSQL database for you when you click the
    `Deploy on Railway`.
