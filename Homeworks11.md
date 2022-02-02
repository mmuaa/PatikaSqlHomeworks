# PatikaSqlHomeworks

Questions:

1-actor ve customer tablolarında bulunan first_name sütunları için tüm verileri sıralayalım.

2-actor ve customer tablolarında bulunan first_name sütunları için kesişen verileri sıralayalım.

3-actor ve customer tablolarında bulunan first_name sütunları için ilk tabloda bulunan ancak ikinci tabloda bulunmayan verileri sıralayalım.

Homeworks 10.1 QUERY:

(
	SELECT first_name FROM actor
	ORDER BY first_name
)
UNION ALL
(
	SELECT first_name FROM customer
	ORDER BY first_name
)

![image](https://user-images.githubusercontent.com/73027559/152127335-61d65262-c28e-4525-b585-2855f6c1a19a.png)

Data Output : Only some of the data were photographed.

![image](https://user-images.githubusercontent.com/73027559/152127674-a95a68fb-8266-4a58-a458-ed08f88db196.png)

Homeworks 10.2 QUERY:

(
	SELECT first_name FROM actor
)
INTERSECT
(
	SELECT first_name FROM customer
)

![image](https://user-images.githubusercontent.com/73027559/152127756-a03203db-fc6b-4518-96c1-34bb6cdf0a5a.png)

Data Output : Only some of the data were photographed.

![image](https://user-images.githubusercontent.com/73027559/152127790-70336c5a-9e5c-4e96-a2d2-8de000030d9d.png)

Homeworks 10.3 QUERY:

(
	SELECT first_name FROM actor
)
EXCEPT
(
	SELECT first_name FROM customer
)

![image](https://user-images.githubusercontent.com/73027559/152127940-87e0e71d-1540-4379-9f72-f7686c670232.png)

Data Output :  Only some of the data were photographed.

![image](https://user-images.githubusercontent.com/73027559/152127963-6b8f082b-93b1-4a31-aad6-28c7cf74d37d.png)
