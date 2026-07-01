# dbt_demo

Demo dbt project for practicing analytics engineering workflows.

## Project Goal

This repository is a small dbt practice project. It keeps the standard dbt project layout and includes example models for learning how dbt organizes SQL transformations, model tests, and project configuration.

## Files and Folders

- `dbt_project.yml` - main dbt project configuration.
- `models/example/my_first_dbt_model.sql` - first example dbt model.
- `models/example/my_second_dbt_model.sql` - second example dbt model.
- `models/example/schema.yml` - model documentation and tests.
- `analyses/`, `macros/`, `seeds/`, `snapshots/`, `tests/` - standard dbt project folders.

## Running

Install dbt, configure your profile, then run:

```bash
dbt run
dbt test
```

## What This Demonstrates

- dbt project structure
- SQL model organization
- Basic model testing through `schema.yml`
- Running and validating transformations

## Tools

dbt and SQL.
