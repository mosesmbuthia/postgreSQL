# ROUND

Lets select everything from our car table.

> SELECT \* FROM car;

Lets say we want to run a promotional discount to every car that we want. Lets say 10%.

We need a query that return the actual price plus discounted price.

```sql
SELECT make, model, price FROM car;
```

- It will be the same as selecting everything on the table.

Now we need to do a bit of calculation, we need to grab the car price and perform calculation.

```sql
SELECT make, model, price, price * .10 FROM car;
```

.10 - 10%

There will be a 10% value of each price generated.

<img src="./img/round1.png" alt="table">

We can go ahead and round the !0% discount into 2 decimal places.

```SQL
SELECT make, model, price, ROUND(price * .10, 2) FROM car;
```

<img src="./img/round-2.png" alt="table">

Now we want to know the discounted price with 10%

- Inside a ROUND(), enter the price, subtract price \* .10.

```sql
 SELECT make, model, price, ROUND(price * .10, 2), ROUND( price - (price * .10), 2) FROM car;
```

It will generate the value after the 10% off.

- What we did is the price minus the discount.

 <img src="./img/round-3.png" alt="table">