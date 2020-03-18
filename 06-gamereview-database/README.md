# Gamereview database

## Import the Database

Import the [`gamereviews_example.sql`](gamereviews_example.sql) file in your database to get access to the tables for this exercise.

Execute the following command in this project directory with the `mysql` client:

```sql
source gamereviews_example.sql
```

Answer every question with:

1. The query that answers the question.
2. The results of that query.

Every query that returns more than 10 row must be reduced to the first 10 rows. (HINT you can do this in you query).

## Example

1. Give all product id's en product descriptions of all products.

```sql
SELECT prod_id, prod_desc FROM products;
```

```text
+---------+----------------------------------------------------------------+
| prod_id | prod_desc                                                      |
+---------+----------------------------------------------------------------+
| ANV01   | .5 ton anvil, black, complete with handy hook                  |
| ANV02   | 1 ton anvil, black, complete with handy hook and carrying case |
| ANV03   | 2 ton anvil, black, complete with handy hook and carrying case |
| DTNTR   | Detonator (plunger powered), fuses not included                |
| FB      | Large bag (suitable for road runners)                          |
| FC      | Carrots (rabbit hunting season only)                           |
| FU1     | 1 dozen, extra long                                            |
| JP1000  | JetPack 1000, intended for single use                          |
| JP2000  | JetPack 2000, multi-use                                        |
| OL1     | Oil can, red                                                   |
| SAFE    | Safe with combination lock                                     |
| SLING   | Sling, one size fits all                                       |
| TNT1    | TNT, red, single stick                                         |
| TNT2    | TNT, red, pack of 10 sticks                                    |
+---------+----------------------------------------------------------------+
14 rows in set (0.00 sec)
```

## Exercise

1. Give a list of names of all tables in the `gamereview_example` database.

  Query:

  ```sql

  ```

  Result:

  ```text

  ```

2. Give all column names and types for the tables `games`.

  ```sql

  ```

  ```text

  ```

3. Answser short but complete on the next questions about the `users` table. Don't answer with a query for these questions.

   1. Do you need to provide a `name`? **ANSWER HERE**
   2. Do you need to provide a `lastname`? **ANSWER HERE**
   3. Do you need to provide an `email`? **ANSWER HERE**
   4. Wha is the maximal length of an password? **ANSWER HERE**

4. Give a list of all names of the `games`.

  ```sql

  ```

  ```text

  ```

5. Give a list of all names of the `users` in alphabetical order.

  ```sql

  ```

  ```text

  ```

6. Give a list of the 10th until the 20th `publishers` that are ranked alphabetically.

  ```sql

  ```

  ```text

  ```

7. What is the amount of `games` that are stored in the database?

  ```sql

  ```

  ```text

  ```

8. What is the amount of `games` in the database that are a multiplayer game?

  ```sql

  ```

  ```text

  ```

9. Give a single query that show the amount of users, amount of games and the amount of reviews in the database.

  ```sql

  ```

  ```text

  ```

10. How many `reviews` have a score less than 2?

  ```sql

  ```

  ```text

  ```

11. Give a top 3 of the best `reviews`.

  ```sql

  ```

  ```text

  ```

12. How many `reviews` has the `game` with id: `20626`?

  ```sql

  ```

  ```text

  ```

13. What is the `id` of the `game` with the most amount of reviews?

  ```sql

  ```

  ```text

  ```

14. What is the `name` of the `game` with the most amount of reviews?

  ```sql

  ```

  ```text

  ```

15. What is the average score for the `game` with `id`: `20991`

  ```sql

  ```

  ```text

  ```

16. What is the average score for the `game` with `name` "Halo 3"

  ```sql

  ```

  ```text

  ```

17. Give a list of games that contain the text `battle`.

  ```sql

  ```

  ```text

  ```

18. What is the `name` of the `user` that wrote the most reviews?

  ```sql

  ```

  ```text

  ```

19. Give a list of names and average scores for the 10 best `games`.

  ```sql

  ```

  ```text

  ```

20. Give the names of the `users`, and the amount of game they own.

  ```sql

  ```

  ```text

  ```

21. Give the names of the 3 most expensive `games`. Also give the `name` of the `publisher` of those `games`.

  ```sql

  ```

  ```text

```

22. Give the top 3 of the total amount of money that the `users` spent on `games`, and the name of those `users`.

  ```sql

  ```

  ```text

  ```

23. Give a top 3 of the names and the average score of the `publishers` of which the `games` have the best `reviews`.

  ```sql

  ```

  ```text

  ```

24. Return a JSON object that contains the `id`, `name` and `price` of the 5 last added `games` in the database.

  ```sql

  ```

  ```text

  ```

---

## Report

When you are ready and submitted the exercise, make sure to fill in the [report](./REPORT.md) file. Don't forget to commit it as well. Answer all questions and check the formatting by viewing the file on GitHub.
