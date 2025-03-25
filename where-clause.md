# WHERE clause and AND

## WHERE

Allows us to filter data based on conditions.

- Where columns meet certain criteria.

```sql
SELECT * FROM person WHERE gender = 'Female';
```

We will get results that only contain females.

## AND

### We can also have multiple conditions to filter a column.

```sql
SELECT * FROM person WHERE gender = 'Female' AND country_of_birth = 'Poland';
```

## OR

We can also combine using OR.

```sql
SELECT * FROM person WHERE gender = 'Female' AND (country_of_birth = 'Poland' OR country_of_birth = 'China');
```