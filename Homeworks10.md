# PatikaSqlHomeworks

Questions:

1-city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz LEFT JOIN sorgusunu yazınız.

2-customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz RIGHT JOIN sorgusunu yazınız.

3-customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz FULL JOIN sorgusunu yazınız

Homeworks 10.1 QUERY:

SELECT city,country FROM city
LEFT JOIN country ON city.country_id=country.country_id

![image](https://user-images.githubusercontent.com/73027559/151764520-96e8a0cc-a695-4f79-b2d3-3d8c009373f6.png)

Data Output : Only some of the data were photographed.

![image](https://user-images.githubusercontent.com/73027559/151764489-4d65427c-8ccf-47ec-82ad-9db5edf1e455.png)

Homeworks 10.2 QUERY:

SELECT payment_id,first_name,last_name FROM customer
RIGHT JOIN payment ON customer.customer_id=payment.customer_id

![image](https://user-images.githubusercontent.com/73027559/151764903-e9b28886-b88c-46c3-acca-93700b6b2d16.png)

Data Output : Only some of the data were photographed.

![image](https://user-images.githubusercontent.com/73027559/151764947-e73e3a36-2733-4208-89dd-4580b73c2a33.png)

Homeworks 10.3 QUERY:

SELECT rental_id,first_name,last_name FROM customer
FULL JOIN rental ON rental.customer_id=customer.customer_id

![image](https://user-images.githubusercontent.com/73027559/151765116-048f8e4a-758e-4c02-a414-2b78d12da96e.png)

Data Output :  Only some of the data were photographed.

![image](https://user-images.githubusercontent.com/73027559/151765138-ea7bf875-9109-4c4a-b387-491052404741.png)
