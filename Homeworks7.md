# PatikaSqlHomeworks

Questions:

1-film tablosunda bulunan filmleri rating değerlerine göre gruplayınız.

2-film tablosunda bulunan filmleri replacement_cost sütununa göre grupladığımızda film sayısı 50 den fazla olan replacement_cost değerini ve karşılık gelen film sayısını sıralayınız.

3-customer tablosunda bulunan store_id değerlerine karşılık gelen müşteri sayılarını nelerdir? 4. city tablosunda bulunan şehir verilerini country_id sütununa göre gruplandırdıktan sonra en fazla şehir sayısı barındıran country_id bilgisini ve şehir sayısını paylaşınız.

4-city tablosunda bulunan şehir verilerini country_id sütununa göre gruplandırdıktan sonra en fazla şehir sayısı barındıran country_id bilgisini ve şehir sayısını paylaşınız.

Homeworks 7.1 QUERY:

SELECT rating,COUNT(rating) FROM film
GROUP BY rating

![image](https://user-images.githubusercontent.com/73027559/150542024-a9915283-9801-461d-857a-376c55a8f4d7.png)


Data Output :

![image](https://user-images.githubusercontent.com/73027559/150542059-4ef95657-3b4a-4b3f-b10f-69394a3474b1.png)

Homeworks 7.2 QUERY:

SELECT replacement_cost,COUNT(replacement_cost) AS moviecounter FROM film
GROUP BY replacement_cost
HAVING COUNT(replacement_cost)>50

![image](https://user-images.githubusercontent.com/73027559/150542918-82a435ed-6bf5-42f4-9045-086b6849b638.png)

Data Output :

![image](https://user-images.githubusercontent.com/73027559/150542939-b2d71e8a-ad6b-4fad-bbb0-28f69d8128e0.png)

Homeworks 7.3 QUERY:

SELECT store_id,COUNT(store_id) FROM customer
GROUP BY store_id

![image](https://user-images.githubusercontent.com/73027559/150543332-3d15dee6-cad0-439a-b629-f56647e51cc2.png)

Data Output :

![image](https://user-images.githubusercontent.com/73027559/150543352-a64e705a-3201-4186-bdfb-3dabe97e36f7.png)

Homeworks 7.4 QUERY:

SELECT country_id,COUNT(city) FROM city
GROUP BY country_id

![image](https://user-images.githubusercontent.com/73027559/150545276-57cf927d-4e84-42ff-965a-0631a78aba8c.png)

Data Output :
Only some of the data were photographed.

![image](https://user-images.githubusercontent.com/73027559/150545306-a3f73b3a-668b-41a6-a575-9ce9f5addc89.png)
