# PatikaSqlHomeworks

Questions:

1-film tablosunda bulunan title ve description sütunlarındaki verileri sıralayınız.

2-film tablosunda bulunan tüm sütunlardaki verileri film uzunluğu (length) 60 dan büyük VE 75 ten küçük olma koşullarıyla sıralayınız.

3-film tablosunda bulunan tüm sütunlardaki verileri rental_rate 0.99 VE replacement_cost 12.99 VEYA 28.99 olma koşullarıyla sıralayınız.

4-customer tablosunda bulunan first_name sütunundaki değeri 'Mary' olan müşterinin last_name sütunundaki değeri nedir?

5-film tablosundaki uzunluğu(length) 50 ten büyük OLMAYIP aynı zamanda rental_rate değeri 2.99 veya 4.99 OLMAYAN verileri sıralayınız.

Homeworks 1.1 QUERY:

SELECT title,description FROM film

![image](https://user-images.githubusercontent.com/73027559/150530038-6dbc5e07-137a-4aec-8d26-f375229f7a9a.png)

Data Output :
Only some of the data were photographed.

![image](https://user-images.githubusercontent.com/73027559/150530073-bc5539d2-3ffc-42c3-9410-f97ad77cce21.png)

Homeworks 1.2 QUERY:

SELECT * FROM film
WHERE length>60 AND length<75

![image](https://user-images.githubusercontent.com/73027559/150530315-35a6b406-1916-4bc1-817f-48860b381c55.png)

Data Output :
Only some of the data were photographed.

![image](https://user-images.githubusercontent.com/73027559/150530335-f8f34f2e-b6d9-44b4-b6f3-936370e42fe5.png)

Homeworks 1.3 QUERY:

SELECT * FROM film
WHERE rental_rate=0.99 AND replacement_cost=12.99 OR replacement_cost=28.99

![image](https://user-images.githubusercontent.com/73027559/150530837-9f9d689d-ce7c-4826-94b9-0f96ace6ba8d.png)

Data Output :
Only some of the data were photographed.

![image](https://user-images.githubusercontent.com/73027559/150530756-00e253e1-e60c-4e9d-89a1-d39797af02c1.png)

Homeworks 1.4 QUERY:

SELECT last_name FROM customer
WHERE first_name='Mary'

![image](https://user-images.githubusercontent.com/73027559/150531204-fcfd4de6-71bd-48ee-8cac-efbab59fae09.png)

Data Output :
Only some of the data were photographed.

![image](https://user-images.githubusercontent.com/73027559/150531242-9a756335-80e4-40d1-8891-e22bb3ec9a2c.png)

Homeworks 1.5 QUERY:

SELECT * FROM film
WHERE length<50 AND rental_rate!=2.99 OR rental_rate!=4.99

![image](https://user-images.githubusercontent.com/73027559/150531556-b387a0a1-3a19-4c85-95cd-b3ef74c0136d.png)

Data Output : 
Only some of the data were photographed.

![image](https://user-images.githubusercontent.com/73027559/150531379-a15fae2b-a530-498d-b0ec-dc19b183112f.png)
