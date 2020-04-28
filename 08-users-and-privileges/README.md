# MySQL permissions

The forta company has some employees that need access to the database.
The different users have need different permissions depending on their job.

1. Add the users to the database with the following credentials
2. Create permissions for the `forta` database with the following rules

user: *samson* (sales), password: *abc123*

* `INSERT` & `SELECT` on the tables `orders` and `orderitems`
* `SELECT` on the table `products`

```sql

```

user: *gert* (CEO), password: *123abc*

* `INSERT`, `SELECT`, `UPDATE` & `DELETE` on the tables `products`, `vendors` and `productnotes`
* `SELECT` on the tables `orders` and `orderitems`

```sql

```

user: *marlene* (accountancy), password: *xyz666*

* `INSERT`, `SELECT`, `UPDATE` & `DELETE` on the table `customers`
* `SELECT` on the tables `orders` and `orderitems`

```sql

```

user: *bobintje* (accountancy), password: *letmein*

* `INSERT`, `SELECT`, `UPDATE` & `DELETE` on all tables

```sql

```

## Report

When you are ready and submitted the exercise, make sure to fill in the
[report](./REPORT.md) file. Don't forget to commit it as well. Answer all
questions and check the formatting by viewing the file on GitHub.
