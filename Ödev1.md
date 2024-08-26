`Soru 1 : film tablosunda bulunan title ve description sütunlarındaki verileri sıralayınız.` <br>
```SELECT title, description FROM film;``` <br>
`Soru 2 : film tablosunda bulunan tüm sütunlardaki verileri film uzunluğu (length) 60 dan büyük VE 75 ten küçük olma koşullarıyla sıralayınız.` <br>
```SELECT * FROM film <br>
WHERE length > 60 AND  length < 75; ```<br>
`Soru 3 : film tablosunda bulunan tüm sütunlardaki verileri rental_rate 0.99 VE replacement_cost 12.99 VEYA 28.99 olma koşullarıyla sıralayınız.` <br>
```SELECT * FROM film  <br>
WHERE rental_rate = 0.99 AND replacement_cost = 12.99 OR replacement_cost = 28.99;``` <br>
`Soru 4 : customer tablosunda bulunan first_name sütunundaki değeri 'Mary' olan müşterinin last_name sütunundaki değeri nedir?` <br>
```SELECT first_name, last_name FROM customer <br>
WHERE first_name = 'Mary';``` <br>
`Soru 5 : film tablosundaki uzunluğu(length) 50 ten büyük OLMAYIP aynı zamanda rental_rate değeri 2.99 veya 4.99 OLMAYAN verileri sıralayınız.` <br>
```SELECT length, rental_rate FROM film <br>
WHERE NOT (length > 50) AND NOT (rental_rate = 2.99 OR rental_rate = 4.99); ```<br>
