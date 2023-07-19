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
alias.column_name
```

- We can also use fully qualifying names especially when using joins as follows:

```sql
table_name.column_name
```
