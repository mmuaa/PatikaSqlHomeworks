# PatikaSqlHomeworks

Questions:

1-country tablosunda bulunan country sütunundaki ülke isimlerinden 'A' karakteri ile başlayıp 'a' karakteri ile sonlananları sıralayınız.

2-country tablosunda bulunan country sütunundaki ülke isimlerinden en az 6 karakterden oluşan ve sonu 'n' karakteri ile sonlananları sıralayınız.

3-film tablosunda bulunan title sütunundaki film isimlerinden en az 4 adet büyük ya da küçük harf farketmesizin 'T' karakteri içeren film isimlerini sıralayınız.

4-film tablosunda bulunan tüm sütunlardaki verilerden title 'C' karakteri ile başlayan ve uzunluğu (length) 90 dan büyük olan ve rental_rate 2.99 olan verileri sıralayınız.

Homeworks 3.1
QUERY:

SELECT * FROM country 
WHERE country LIKE 'A%a'

![image](https://user-images.githubusercontent.com/73027559/150534430-930f5b4d-fd6c-414a-a14b-ae8ea44886f4.png)

Data Output :

![image](https://user-images.githubusercontent.com/73027559/150534410-9364420b-d6fe-4dc8-ac7b-12dd0a2d3ff4.png)

Homeworks 3.2
QUERY:

SELECT * FROM country 
WHERE country LIKE '_____%n'

![image](https://user-images.githubusercontent.com/73027559/150534655-2bd00013-715e-4ac1-bb46-1815ac4757a2.png)

Data Output :

![image](https://user-images.githubusercontent.com/73027559/150534681-7104b5bf-0cb1-4449-95b8-0935c6a82600.png)

Homeworks 3.3
QUERY:

SELECT title FROM film  
WHERE title ILIKE '%t%t%t%t%'

![image](https://user-images.githubusercontent.com/73027559/150535173-76ef15d2-bafd-4d1e-9fa3-92ecddde336d.png)

Data Output :

![image](https://user-images.githubusercontent.com/73027559/150535196-ef652b5e-97ac-49e0-a296-118d998e21ec.png)

Homeworks 3.4
QUERY:

SELECT * FROM film
WHERE title LIKE 'C%' AND length>90 AND rental_rate = 2.99

![image](https://user-images.githubusercontent.com/73027559/150535508-5c411244-8851-4f32-8e6f-65c640daab09.png)

Data Output :

![image](https://user-images.githubusercontent.com/73027559/150535493-3d4eb4ba-5ddd-4490-829d-7bb28a1a6378.png)
