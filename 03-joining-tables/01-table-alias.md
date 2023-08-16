# Table alias

- Assign a new temporary name to a table.
- Similar to column alias.

## Syntax

```sql
SELECT select_list
FROM table_name AS alias_name;
```

- `AS` is optional.
- Widely used in joins.
- You can also use it when your table name is very long.
- We can access a column in a table with alias as follows:

```sql
-- Syntax
alias.column_name

-- Example
SELECT e.emp_name
FROM employee e;
```

- We can also use fully qualifying names especially when using joins as follows:

```sql
-- Syntax
table_name.column_name

-- Example
SELECT employee.emp_name
FROM employee;
```
