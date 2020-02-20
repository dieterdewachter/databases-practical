# Creating Tables

Create a database called `exercise_03` and create the tables as described below.
Give the queries that will create those tables, and verify there structure with a `DESCRIBE [table]` query.

- Choose the names of the databases and columns. Make there names logical and descriptive.
- Pick the best datatype that will allow only correct data in the tables.
- Don't forget to select or create a primary key for each table.

## Twitter Messages

Create a table that can contain Twitter messages. The messages have the following properties:

- Username
- Tweet message
- Date and time

Create table query:

```sql

```

`DESCRIBE` result:

```text

```

## Webshop

Create a table that can store data for a webshop. The webshop sells different types of products using the following properties:

- Product name
- Description
- Price
- Stock (false value if out of stock)

Create table query:

```sql

```

`DESCRIBE` result:

```text

```

## Clients

Create a table that can contain information about customers or clients. The clients have the following properties:

- First name
- Last name
- Birthday
- Premium (if true, the value could be used to calculate premium discounts)

Create table query:

```sql

```

`DESCRIBE` result:

```text

```

## Components

When working on electronics projects, a lot of components are used. It is handy to have an overview of what types you have on your shelf. The components have the following properties:

- Type (can only be: resistor, capacitor or coil)
- Value
- Manufacturer
- Stock (a number, the amount of stock on the shelf)

Create table query:

```sql

```

`DESCRIBE` result:

```text

```

## Computers

Create a table that can manage custom computer configurations. The systems have the following properties:

- Cpu brand (Intel, AMD, ARM or Other)
- Cpu model
- RAM size (in GigaBytes)
- Interfaces (each computer could have _any_ combination of interfaces)
  - Ethernet
  - Wifi
  - USB 3.0
  - USB 2.0
  - Bluetooth
  - Audio jack
- Price
- Release data
- Title
- Description

Create table query:

```sql

```

`DESCRIBE` result:

```text

```

## Report

Don't forget to fill in the [REPORT.md](REPORT.md) at the end of the exercise.
