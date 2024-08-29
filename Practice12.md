`Soru 1 : film tablosunda film uzunluğu length sütununda gösterilmektedir. Uzunluğu ortalama film uzunluğundan fazla kaç tane film vardır?` 
```SQL
SELECT COUNT(*) FROM film
WHERE length >
(
SELECT AVG(length)
FROM film
);
```
`Soru 2 : film tablosunda en yüksek rental_rate değerine sahip kaç tane film vardır?` 
```SQL
SELECT COUNT(*) FROM film
WHERE rental_rate =
(
SELECT MAX(rental_rate)
FROM film
);
```
`Soru 3 : film tablosunda en düşük rental_rate ve en düşün replacement_cost değerlerine sahip filmleri sıralayınız.`
```SQL
SELECT title, rental_rate FROM film
WHERE rental_rate = ANY
(
SELECT MAX(rental_rate) FROM film
UNION
SELECT MIN(rental_rate) FROM film
)
ORDER BY rental_rate DESC;
```
`Soru 4 : payment tablosunda en fazla sayıda alışveriş yapan müşterileri(customer) sıralayınız.`
```SQL
SELECT customer_id, COUNT(*) AS S
FROM payment
GROUP BY customer_id
ORDER BY S DESC;
```
