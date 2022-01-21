# PatikaSqlHomeworks

Questions:

1-film tablosunda bulunan replacement_cost sütununda bulunan birbirinden farklı değerleri sıralayınız.

2-film tablosunda bulunan replacement_cost sütununda birbirinden farklı kaç tane veri vardır?

3-film tablosunda bulunan film isimlerinde (title) kaç tanesini T karakteri ile başlar ve aynı zamanda rating 'G' ye eşittir?

4-country tablosunda bulunan ülke isimlerinden (country) kaç tanesi 5 karakterden oluşmaktadır?

5-city tablosundaki şehir isimlerinin kaç tanesi 'R' veya r karakteri ile biter?

Homeworks 1.1 QUERY:

SELECT DISTINCT replacement_cost  FROM film

![image](https://user-images.githubusercontent.com/73027559/150536229-6888c9f8-61ef-49f8-9814-cc67dc12510e.png)

Data Output :
Only some of the data were photographed.

![image](https://user-images.githubusercontent.com/73027559/150536251-81e06e3c-aaa4-455a-b4ef-ff6a59dbd543.png)

Homeworks 1.2 QUERY:

SELECT DISTINCT COUNT(replacement_cost)  FROM film

![image](https://user-images.githubusercontent.com/73027559/150536342-857b1e83-4ed7-45da-a6f8-b162a1bf48f3.png)

Data Output :

![image](https://user-images.githubusercontent.com/73027559/150536375-a590394f-9f97-4812-8580-26807f3a802b.png)

Homeworks 1.3 QUERY:

SELECT COUNT(title) FROM film
WHERE title LIKE 'T%' AND rating = 'G'

![image](https://user-images.githubusercontent.com/73027559/150536838-8a82ef6a-5d20-4686-8787-cd1ef37299c5.png)


Data Output :

![image](https://user-images.githubusercontent.com/73027559/150536856-b9bb0dc1-99ab-4bae-a408-9588fbda75b4.png)

Homeworks 1.4 QUERY:

SELECT COUNT(country) FROM country
WHERE country LIKE '_____' 

![image](https://user-images.githubusercontent.com/73027559/150537142-62fbfe71-fb87-4dbc-9276-612a137a1238.png)

Data Output :

![image](https://user-images.githubusercontent.com/73027559/150537167-756e59e8-db79-49f2-8915-e4929b6833dd.png)

Homeworks 1.5 QUERY:

SELECT COUNT(city) FROM city
WHERE city LIKE 'R%r' 

![image](https://user-images.githubusercontent.com/73027559/150537409-8490ec7e-322f-4899-a26f-19c84bc8d17f.png)

Data Output : 

![image](https://user-images.githubusercontent.com/73027559/150537381-0bb474f3-4be9-425b-a11e-19dce5609efe.png)
