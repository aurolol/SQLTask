`Soru 1 : actor ve customer tablolarında bulunan first_name sütunları için tüm verileri sıralayalım.` 
```SQL
(
SELECT first_name FROM actor
ORDER BY first_name ASC
)
UNION 
(
SELECT first_name FROM customer
ORDER BY first_name ASC
)
```
`Soru 2 : actor ve customer tablolarında bulunan first_name sütunları için kesişen verileri sıralayalım.` 
```SQL
SELECT first_name FROM actor
ORDER BY first_name ASC
)
INTERSECT
(
SELECT first_name FROM customer
ORDER BY first_name ASC
)
```
`Soru 3 : actor ve customer tablolarında bulunan first_name sütunları için ilk tabloda bulunan ancak ikinci tabloda bulunmayan verileri sıralayalım.`
```SQL
(
SELECT first_name FROM actor
ORDER BY first_name ASC
)
EXCEPT
(
SELECT first_name FROM customer
ORDER BY first_name ASC
)

```
`Soru 4 : İlk 3 sorguyu tekrar eden veriler için de yapalım.`
```SQL
(
SELECT first_name FROM actor
ORDER BY first_name ASC
)
UNION ALL
(
SELECT first_name FROM customer
ORDER BY first_name ASC
)
```
