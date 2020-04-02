# Gamereview database

## Import the Database

Go to the `/sql` directory in this exercise directory and import the `spacex.sql` file in your database to get access to the tables for this exercise.

Execute the following command in this project directory with the `mysql` client:

```sql
source spacex.sql
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

1. Amount of launches

  ```sql

  ```

  ```text

  ```

2. Amount of upcoming launches

  ```sql

  ```

  ```text

  ```

3. Amount of past launches

  ```sql

  ```

  ```text

  ```

4. Amount of successful launches

  ```sql

  ```

  ```text

  ```

5. How many launches have details?

  ```sql

  ```

  ```text

  ```

6. What are the different core serial numbers that have been used in launches? (no duplicates!)

  ```sql

  ```

  ```text

  ```

7. What are the amount of launches per year (for every year)

  ```sql

  ```

  ```text

  ```

8. What 'Iridium' missions (name) were launched? (using only launches table)

  ```sql

  ```

  ```text

  ```

9. What mission failed after 150 seconds?

  ```sql

  ```

  ```text

  ```

10. What is the amount of water landings for every status value?

  ```sql

  ```

  ```text

  ```

11. What are the core serial number that landed on water?

  ```sql

  ```

  ```text

  ```

12. What are the names of the missions that landed on water?

  ```sql

  ```

  ```text

  ```

13. How many missions landed on land (not water) in 2018?

  ```sql

  ```

  ```text

  ```

14. What are the mission names (with the mission year) that failed to land on water?

  ```sql

  ```

  ```text

  ```

15. What is the average payload weight?

  ```sql

  ```

  ```text

  ```

16. What is the average payload weight of 'SES' missions? (note: customers is an string contianing a list...)

  ```sql

  ```

  ```text

  ```

17. What is the heaviest payload that is launched in a 'LEO' orbit

  ```sql

  ```

  ```text

  ```

18. What are the payload manufacturers that lost there payload due to a failed launch?

  ```sql

  ```

  ```text

  ```

19. What is the amount of payload mass that each nationality has launched?

  ```sql

  ```

  ```text

  ```

20. What is the amount of payload mass that each nationality has launched in the year 2018?

  ```sql

  ```

  ```text

  ```

21. What is the average payload mass that each manufacturer has launched in 2017?

  ```sql

  ```

  ```text

  ```

22. In how many flights was the 'Falcon 9' rocket used?

  ```sql

  ```

  ```text

  ```

23. When was the first time that a core landed on water? (exclude empty dates)

  ```sql

  ```

  ```text

  ```

24. How many launches have taken place on any launchpad, give the name of those launchpads and their status?

  ```sql

  ```

  ```text

  ```

## Report

When you are ready and submitted the exercise, make sure to fill in the [report](./REPORT.md) file. Don't forget to commit it as well. Answer all questions and check the formatting by viewing the file on GitHub.
