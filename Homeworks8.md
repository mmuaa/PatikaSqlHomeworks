# PatikaSqlHomeworks

Questions:

1-test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

2-Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

3-Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

4-Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

Homeworks 8.1 QUERY:

CREATE TABLE employee(
	id INTEGER, 
	name VARCHAR(50), 
	birthday DATE, 
	email VARCHAR(100)
);

![image](https://user-images.githubusercontent.com/73027559/150548170-3244ef1b-4722-4df6-91f5-d79eacfa3a10.png)


Homeworks 8.3 QUERY:

UPDATE employee
SET name = 'Muharrem',
	birthday='1975-03-27'
WHERE id = 20

UPDATE employee
SET id=47
WHERE name = 'Muharrem',

UPDATE employee
SET name = 'Mua'
  id=78
WHERE birthday='1975-03-27',

UPDATE employee
SET email = 'ornek@gmail.com'
  id=54
WHERE email = ibeachem18@webs.com,

UPDATE employee
SET  birthday='1975-04-29
WHERE email = 'ornek@gmail.com' AND id=54,

Homeworks 8.4 QUERY:

DELETE FROM employee
Where id=20

DELETE FROM employee
Where id>49

DELETE FROM employee
Where email=ornek@gmail.com
RETURNING *

DELETE FROM employee
Where name='Mua'

DELETE FROM employee
Where birthday='1975-04-29'
