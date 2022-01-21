# PatikaSqlHomeworks

Questions:

1-film tablosunda bulunan tüm sütunlardaki verileri replacement cost değeri 12.99 dan büyük eşit ve 16.99 küçük olma koşuluyla sıralayınız ( BETWEEN - AND yapısını kullanınız.)

2-.actor tablosunda bulunan first_name ve last_name sütunlardaki verileri first_name 'Penelope' veya 'Nick' veya 'Ed' değerleri olması koşuluyla sıralayınız. ( IN operatörünü kullanınız.)

3-film tablosunda bulunan tüm sütunlardaki verileri rental_rate 0.99, 2.99, 4.99 VE replacement_cost 12.99, 15.99, 28.99 olma koşullarıyla sıralayınız. ( IN operatörünü kullanınız.)

Homeworks 2.1 QUERY:

SELECT * FROM film
WHERE replacement_cost BETWEEN 12.99 AND 16.98  --(16.99 dan kücük olması için)

![image](https://user-images.githubusercontent.com/73027559/150533170-064709a6-17de-47c3-8fe5-c1e1d6a92a66.png)

Data Output :
Only some of the data were photographed.

![image](https://user-images.githubusercontent.com/73027559/150533214-d9be00c4-a915-41b0-af85-3ab2a384ce84.png)

Homeworks 2.2 QUERY:

SELECT * FROM actor
WHERE first_name IN ('Penelope','Nick','Ed')

![image](https://user-images.githubusercontent.com/73027559/150533503-28d43367-0227-4af2-8087-63930291c012.png)

Data Output :

![image](https://user-images.githubusercontent.com/73027559/150533543-e0714ac2-3597-40b5-b728-bd8d8a1840d1.png)

Homeworks 2.3 QUERY:

SELECT * FROM film
WHERE rental_rate IN (0.99,2.99,4.99) AND replacement_cost IN (12.99,15.99,28.99)

![image](https://user-images.githubusercontent.com/73027559/150533793-6fc0337d-fced-4392-94fa-fff93bf77f59.png)

Data Output :
Only some of the data were photographed.

![image](https://user-images.githubusercontent.com/73027559/150533760-067f85e2-5c2f-47fa-8bb6-b96609a2a885.png)
