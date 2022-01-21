# PatikaSqlHomeworks

Questions:

1-film tablosunda bulunan rental_rate sütunundaki değerlerin ortalaması nedir?

2-film tablosunda bulunan filmlerden kaç tanesi 'C' karakteri ile başlar?

3-film tablosunda bulunan filmlerden rental_rate değeri 0.99 a eşit olan en uzun (length) film kaç dakikadır?

4-film tablosunda bulunan filmlerin uzunluğu 150 dakikadan büyük olanlarına ait kaç farklı replacement_cost değeri vardır?

Homeworks 6.1 QUERY:

SELECT ROUND(AVG(rental_rate),3)  FROM film 

![image](https://user-images.githubusercontent.com/73027559/150540007-cb314e8f-12d2-412b-bb04-5ea7d10e9e44.png)

Data Output :

![image](https://user-images.githubusercontent.com/73027559/150540038-1138f0e1-17d1-48f1-adf2-33651da6196c.png)


Homeworks 6.2 QUERY:

SELECT COUNT(rental_rate) FROM film 
WHERE title LIKE 'C%'

![image](https://user-images.githubusercontent.com/73027559/150540201-0faa79d3-b424-4a42-8940-5c08e33ed358.png)

Data Output :

![image](https://user-images.githubusercontent.com/73027559/150540217-bafe8019-6093-4ba2-b405-cffedae56b41.png)

Homeworks 6.3 QUERY:

SELECT MAX(length) FROM film
WHERE rental_rate=0.99

![image](https://user-images.githubusercontent.com/73027559/150540577-2b6e50d3-a9f1-4d93-bbaf-a4cfa31900f0.png)

Data Output :

![image](https://user-images.githubusercontent.com/73027559/150540601-32435310-1810-4b5c-a686-373d7c854351.png)

Homeworks 6.4 QUERY:

SELECT COUNT(DISTINCT replacement_cost) FROM film
WHERE length>150

![image](https://user-images.githubusercontent.com/73027559/150541273-640b66f7-ffe5-48e3-95ab-06f1c3a62d07.png)

Data Output :

![image](https://user-images.githubusercontent.com/73027559/150541293-80209c12-7c49-41e9-afb0-88bd5a24a894.png)
