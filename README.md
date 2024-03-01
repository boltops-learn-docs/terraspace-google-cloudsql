<!-- note marker start -->
NOTE: This repo contains only the documentation for the private BoltsOps repo code.
Original file: https://github.com/boltops-learn/terraspace-google-cloudsql/blob/master/README.md
The docs are publish so they are available for interested subscribers.
For access to the source code, you can become a BoltOps subscriber.
See: https://learn.boltops.com

<!-- note marker end -->

# Terraspace CloudSQL Example

[![BoltOps Badge](https://img.boltops.com/boltops/badges/boltops-badge.png)](https://www.boltops.com)

Creates a Google CloudSQL DB using the [google_sql_database_instance](https://registry.terraform.io/providers/hashicorp/google/latest/docs/resources/sql_database_instance) resource.

PostgreSQL is the default. You can change the database with the tfvar: `database_version`

## Env Vars

You should configure these env vars:

* GOOGLE_PROJECT
* GOOGLE_REGION

## Deploy

To deploy:

    terraspace up cloudsql

## Video

[![Watch the video](https://uploads-learn.boltops.com/pb5uiob3jg1e6v5zwbbd73hm7h9x)](https://learn.boltops.com/courses/terraspace-gcp/lessons/terraspace-google-cloudsql-with-google_sql_database_instance)

Note: Premium video content requires a subscription.
