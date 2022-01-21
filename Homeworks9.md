# PatikaSqlHomeworks

Sorular:

1-city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

2-customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

3-customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz INNER JOIN sorgusunu yazınız.

Homeworks 9.1
QUERY:

SELECT city,country FROM city
JOIN country ON city.country_id = country.country_id

![image](https://user-images.githubusercontent.com/73027559/150529083-9e519113-ed4f-4d98-96a0-a9625ad85815.png)

Data Output :

![image](https://user-images.githubusercontent.com/73027559/150529115-61578dae-261c-46cb-972a-3c0a8418e9a8.png)

Homeworks 9.2
QUERY:

SELECT payment_id,first_name,last_name FROM payment
JOIN customer ON payment.customer_id = customer.customer_id

![image](https://user-images.githubusercontent.com/73027559/150528731-b2289efb-3fbb-4a2d-a369-f34a49a351c5.png)

Data Output : 

![image](https://user-images.githubusercontent.com/73027559/150528774-a2f3fa31-cc0d-4d35-9216-db804c161dad.png)

Homeworks 9.3
QUERY:

SELECT rental_id,first_name,last_name FROM rental
JOIN customer ON rental.rental_id = customer.customer_id

![image](https://user-images.githubusercontent.com/73027559/150528152-a40a80a9-a82d-4453-b364-1bed0f0b05c5.png)

Data Output : 

![image](https://user-images.githubusercontent.com/73027559/150528213-eb0c9181-bb39-4c80-abae-f52e586998a8.png)
