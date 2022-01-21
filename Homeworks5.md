# PatikaSqlHomeworks

Questions:

1-film tablosunda bulunan ve film ismi (title) 'n' karakteri ile biten en uzun (length) 5 filmi sıralayınız.

2-film tablosunda bulunan ve film ismi (title) 'n' karakteri ile biten en kısa (length) ikinci(6,7,8,9,10) 5 filmi(6,7,8,9,10) sıralayınız.

3-customer tablosunda bulunan last_name sütununa göre azalan yapılan sıralamada store_id 1 olmak koşuluyla ilk 4 veriyi sıralayınız.


Homeworks 5.1 QUERY:

SELECT title FROM film
WHERE title LIKE '%n'
ORDER BY length DESC
LIMIT 5

![image](https://user-images.githubusercontent.com/73027559/150538848-8a571d20-611f-4f09-93cf-a3827ff3ca01.png)

Data Output :

![image](https://user-images.githubusercontent.com/73027559/150538819-879f0a38-4b93-4807-a4bc-30ab90ae09c6.png)

Homeworks 5.2 QUERY:

SELECT title FROM film
WHERE title LIKE '%n'
ORDER BY length ASC
OFFSET 5
LIMIT 5

![image](https://user-images.githubusercontent.com/73027559/150539021-d4b23ab0-6ccb-45e5-908e-c9e3eeae6672.png)

Data Output :

![image](https://user-images.githubusercontent.com/73027559/150539049-bb804750-62a7-422b-bcb7-783e3392d8ba.png)

Homeworks 5.3 QUERY:

SELECT * FROM customer
WHERE store_id=1
ORDER BY last_name DESC
LIMIT 4

![image](https://user-images.githubusercontent.com/73027559/150539285-2aaf9591-63b6-4b84-8424-8669aa8878b0.png)

Data Output :

![image](https://user-images.githubusercontent.com/73027559/150539355-94b3c561-60f8-414c-b110-46e835191de8.png)
