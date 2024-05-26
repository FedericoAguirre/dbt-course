# dbt-course
This is a quick starter DBT course

## Creating a model

1. Create and populate the Snowflake database, running the queries in **sql** folder.
2. Create the DBT model, running the command:

```bash
dbt run --full-refresh
```

## Running a single model

```bash
dbt run --select customers
```

## Important links

[DBT project folder structure](https://docs.getdbt.com/best-practices/how-we-structure/1-guide-overview)
[DBT custom aliases](https://docs.getdbt.com/docs/build/custom-aliases)