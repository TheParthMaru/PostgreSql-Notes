# `WHERE` Clause

- We use `WHERE` to select rows that satisfies a specific condition.

## Syntax

```sql
SELECT select_list
FROM table_name
WHERE condition
ORDER BY sort_expression;
```

- The conditon must evaluate to true, false or unknown.
- We use `AND` and `OR` operators to combine conditions.
- `FROM` → `WHERE` → `SELECT` → `ORDER BY`
- If we have used column alias in `SELECT`, we cannot use that in `WHERE` clause.
- We can also use `WHERE` clause in `UPDATE` and `DELETE` statements.

## Comparison Operators

- `=` → Equal
- `>` → Greater than
- `<` → Less than
- `>=` → Greater than or equal
- `<=` → Less than or equal
- `<>` or `!=` → Not equal

## Logical Operators

- `AND` → Logical AND
- `OR` → Logical OR
- `NOT` → Logical NOT

## Example

### Using `WHERE` with `=` operator

```sql
SELECT
    first_name,
    last_name
FROM
    customer
WHERE
    first_name = 'Jamie';

```

![Alt text](images/image.png)

### Using `WHERE` with `AND` operator

```sql
SELECT
    first_name,
    lsat_name
FROM
    customer
WHERE
    first_name = 'Jamie' AND
    last_name = 'Rice';
```

![Alt text](images/image-1.png)
