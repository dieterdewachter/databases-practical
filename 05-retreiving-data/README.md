
# Retreiving Data

Take the following table. It shows the scores of a 'Database' course examination. The exam consists out of 3 questions that received a score from 0 to 20. For each of the students the firstname, lastname and r-number are stored.

| R-Nummer | Voornaam | Naam     | Vraag 1 | Vraag 2 | Vraag 3 |
| -------- | -------- | -------- | ------- | ------- | ------- |
| 613      | Emma     | Dumont   | 12      | 9       | 4       |
| 896      | Olivia   | Claes    | 16      | 15      | 11      |
| 498      | Louise   | Willems  | 13      | 19      | 10      |
| 101      | Mila     | Hermans  | 7       | 4       | 6       |
| 114      | Alice    | Simon    | 16      | 6       | 6       |
| 654      | Juliette | Claeys   | 7       | 12      | 8       |
| 314      | Elena    | Segers   | 15      | 6       | 8       |
| 660      | Marie    | Wouters  | 19      | 11      | 8       |
| 141      | Sofia    | Maes     | 7       | 16      | 11      |
| 955      | Lina     | Goossens | 16      | 3       | 12      |

The table consist out of _raw_ data only. When storing the information into a database we could use the powers of the DBMS to extract other useful information.

## Create Table

First you need to create a table in MySQL that can store the information. Keep in the following rules in mind:

- use English names for table and column names
- use _snake_case_ notation if words should contain spaces (no capital letters and replace spaces by `_` characters)
- choose the correct datatypes for each of the columns

```sql

```

## Fill Table with Data

The next step is to fill the newly created database with the information of the table above. If possible use only a single query for the whole table.

```sql

```

## Extracting Useful Information

Extract useful data using `SELECT` queries.

Note: read the questions thoroughly, and respect the order of columns as given in the questions. The order must reflect in the solutions and must be the same.

1. Get all data stored into the table.

   Query:

   ```sql

   ```

   Result:

   ```text

   ```

1. Create a class list. Select only the R-Number, firstname and lastname of all students (no scores).

   Query:

   ```sql

   ```

   Result:

   ```text

   ```

1. Create a alphabetical class list. Select lastname and firstname. Order the list alphabetically on the last name.

   Query:

   ```sql

   ```

   Result:

   ```text

   ```

1. Generate a list of the firstname, lastname and score of question 1. Order the list by score of question 1 from greatest to least.

   Query:

   ```sql

   ```

   Result:

   ```text

   ```

1. Generate a list of lastname, firstname and score of question 3. Order the list by score of question 3 from least to greatest.

   Query:

   ```sql

   ```

   Result:

   ```text

   ```

1. Generate a list of only firstname and lastname. Order the list by score of question 2 from greatest to least. Do not show the scores.

   Query:

   ```sql

   ```

   Result:

   ```text

   ```

1. Generate a list of firstname, lastname of students that did not pass for question 1. (Only students that have a score less than 10).

   Query:

   ```sql

   ```

   Result:

   ```text

   ```

1. Generate a list of firstname, lastname of students that did pass for question 3. (Only students that have a score greater or equal than 10).

   Query:

   ```sql

   ```

   Result:

   ```text

   ```

1. Generate a list of lastname, firstname of students that did not pass for question 2. Order the list alphabetically on lastname.

   Query:

   ```sql

   ```

   Result:

   ```text

   ```

1. Generate a list of students (firstname and lastname) that could tolerate the score of question 3. (Only students that have a score between 8 and 10). Order the list by score from least to greatest.

   Query:

   ```sql

   ```

   Result:

   ```text

   ```

1. Generate a list of students (firstname and lastname) together with their 'total score' on a total of 60.

   Query:

   ```sql

   ```

   Result:

   ```text

   ```

1. Generate a list of students (firstname and lastname) together with their 'total score' on a total of 20.

   Query:

   ```sql

   ```

   Result:

   ```text

   ```

1. Generate a list of students (firstname and lastname) together with their 'total score' on 20, ordered by their total score from greatest to least.

   Query:

   ```sql

   ```

   Result:

   ```text

   ```

1. Generate a list of firstname, lastname, total score on 20. Only show students that did not pass on their total score (score less than 10). Order the list by their lastname alphabetically.

   Query:

   ```sql

   ```

   Result:

   ```text

   ```

1. Give first and lastname and total score of the 3 best students. Order by their total score from greatest to least.

   Query:

   ```sql

   ```

   Result:

   ```text

   ```
