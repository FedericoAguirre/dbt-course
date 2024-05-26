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

## Running tests

```bash
dbt test
dbt test --select customers
```

## Creating documentation

```bash
dbt docs generate
```

## Schema naming

You can name this file whatever you want (including ```whatever_you_want.yml```), so long as:

The file is in your ```models/``` directory¹
The file has .yml extension
Check out the [docs](https://docs.getdbt.com/reference/configs-and-properties) for more information.

¹If you're declaring properties for seeds, snapshots, or macros, you can also place this file in the related directory — ```seeds/```, ```snapshots/``` and ```macros/``` respectively.

## Important links

- [DBT project folder structure](https://docs.getdbt.com/best-practices/how-we-structure/1-guide-overview)

- [DBT custom aliases](https://docs.getdbt.com/docs/build/custom-aliases)

- [DBT tests](https://docs.getdbt.com/docs/build/data-tests)