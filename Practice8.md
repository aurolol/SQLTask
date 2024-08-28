`Soru 1 : test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.` 
```SQL
CREATE TABLE employee(
	id SERIAL PRIMARY KEY,
	name VARCHAR(50) NOT NULL,
	birthday DATE,
	email VARCHAR(100)
);
```
`Soru 2 : Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.` 
```SQL
insert into employee (name, birthday, email) values ('Donnie McQuaide', null, 'dmcquaide0@fastcompany.com');
insert into employee (name, birthday, email) values ('Nanni Lenthall', '2003-08-18', 'nlenthall1@dion.ne.jp');
insert into employee (name, birthday, email) values ('Pierce Kimmerling', '2001-12-20', 'pkimmerling2@europa.eu');
insert into employee (name, birthday, email) values ('Adah Tongs', '1979-08-09', 'atongs3@tuttocitta.it');
insert into employee (name, birthday, email) values ('Barton Ridings', '1988-12-13', 'bridings4@sitemeter.com');
insert into employee (name, birthday, email) values ('Klement Grimley', '2001-04-25', 'kgrimley5@mail.ru');
insert into employee (name, birthday, email) values ('Evanne Binch', '1955-06-27', 'ebinch6@si.edu');
insert into employee (name, birthday, email) values ('Derick Egdal', '1977-12-21', null);
insert into employee (name, birthday, email) values ('Fey McNeil', '1979-11-24', 'fmcneil8@cdbaby.com');
insert into employee (name, birthday, email) values ('Brandie Turville', '1976-05-22', 'bturville9@constantcontact.com');
insert into employee (name, birthday, email) values ('Winslow Korpolak', '1977-10-21', 'wkorpolaka@addtoany.com');
insert into employee (name, birthday, email) values ('Clemente Spiers', '1975-12-13', 'cspiersb@engadget.com');
insert into employee (name, birthday, email) values ('Doy Jansema', '1992-05-02', 'djansemac@huffingtonpost.com');
insert into employee (name, birthday, email) values ('Ailey Colbran', '1984-06-25', null);
insert into employee (name, birthday, email) values ('Tait Ayrton', '1979-10-20', 'tayrtone@imdb.com');
insert into employee (name, birthday, email) values ('Sheri Willatt', '1950-12-22', 'swillattf@ucsd.edu');
insert into employee (name, birthday, email) values ('Goldina Dimond', '1984-06-24', null);
insert into employee (name, birthday, email) values ('Lois Grise', '2004-10-31', 'lgriseh@dmoz.org');
insert into employee (name, birthday, email) values ('Caye Coldman', '1964-08-20', 'ccoldmani@arstechnica.com');
insert into employee (name, birthday, email) values ('Kyla Newark', '1990-10-30', 'knewarkj@jiathis.com');
insert into employee (name, birthday, email) values ('Annmaria Jacobson', '1999-05-04', 'ajacobsonk@webmd.com');
insert into employee (name, birthday, email) values ('Nickie Dunstone', null, 'ndunstonel@t-online.de');
insert into employee (name, birthday, email) values ('Burgess Toogood', '1962-10-04', 'btoogoodm@odnoklassniki.ru');
insert into employee (name, birthday, email) values ('Camilla Hovy', '2001-11-13', 'chovyn@lulu.com');
insert into employee (name, birthday, email) values ('Berti Salzberger', '1978-03-11', 'bsalzbergero@diigo.com');
insert into employee (name, birthday, email) values ('Kingsly Denford', '2002-10-16', 'kdenfordp@theatlantic.com');
insert into employee (name, birthday, email) values ('Patricio Santoro', '1955-06-05', 'psantoroq@epa.gov');
insert into employee (name, birthday, email) values ('Justus Georgiades', '1997-03-21', 'jgeorgiadesr@barnesandnoble.com');
insert into employee (name, birthday, email) values ('Vite Porrett', '1980-11-09', 'vporretts@craigslist.org');
insert into employee (name, birthday, email) values ('Annabell Stampe', '1980-12-06', 'astampet@bizjournals.com');
insert into employee (name, birthday, email) values ('Brunhilda Klosser', '1961-07-27', 'bklosseru@seesaa.net');
insert into employee (name, birthday, email) values ('Lynett Eidelman', '1970-08-12', 'leidelmanv@1und1.de');
insert into employee (name, birthday, email) values ('Vivia Panting', '1983-02-07', 'vpantingw@issuu.com');
insert into employee (name, birthday, email) values ('Jacenta Riddick', '1981-09-23', 'jriddickx@ucoz.com');
insert into employee (name, birthday, email) values ('Vinita Verty', '1993-11-12', 'vvertyy@webs.com');
insert into employee (name, birthday, email) values ('Babbie Gillicuddy', '1971-03-20', 'bgillicuddyz@addthis.com');
insert into employee (name, birthday, email) values ('Shani Brewster', '1997-07-01', 'sbrewster10@opera.com');
insert into employee (name, birthday, email) values ('Finlay Rigmand', '1999-02-05', 'frigmand11@github.io');
insert into employee (name, birthday, email) values ('Troy Beeby', '1956-08-09', 'tbeeby12@japanpost.jp');
insert into employee (name, birthday, email) values ('Donn Puffett', '1999-05-31', 'dpuffett13@apache.org');
insert into employee (name, birthday, email) values ('Malorie Woloschinski', '1982-05-06', 'mwoloschinski14@reuters.com');
insert into employee (name, birthday, email) values ('Pearle Lody', '2003-12-08', 'plody15@skyrock.com');
insert into employee (name, birthday, email) values ('Fawne Ishchenko', '2001-07-15', 'fishchenko16@lycos.com');
insert into employee (name, birthday, email) values ('Granny Maps', '1987-09-07', 'gmaps17@yellowpages.com');
insert into employee (name, birthday, email) values ('Adelina Bortoletti', '1993-05-14', 'abortoletti18@virginia.edu');
insert into employee (name, birthday, email) values ('Mirna Cooksley', '1976-07-07', 'mcooksley19@wunderground.com');
insert into employee (name, birthday, email) values ('Antons Bettison', '1956-02-23', 'abettison1a@wp.com');
insert into employee (name, birthday, email) values ('Elvin Marte', '1963-12-28', 'emarte1b@foxnews.com');
insert into employee (name, birthday, email) values ('Silvester Blazevic', '1993-05-04', 'sblazevic1c@deliciousdays.com');
insert into employee (name, birthday, email) values ('Blondelle Lapish', '1956-12-03', 'blapish1d@myspace.com');
```
`Soru 3 : Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.` 
```SQL

UPDATE employee
SET name = 'Updated Person'
WHERE id = 1;

UPDATE employee
SET name = 'Updated Person'
WHERE id = 2;

UPDATE employee
SET name = 'Updated Person'
WHERE id = 3;

UPDATE employee
SET name = 'Updated Person'
WHERE id = 4;

UPDATE employee
SET name = 'Updated Person'
WHERE id = 5;
```
`Soru 4 : Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.` 
```SQL
DELETE FROM employee
WHERE id = 1;

DELETE FROM employee
WHERE id = 2;

DELETE FROM employee
WHERE id = 3;

DELETE FROM employee
WHERE id = 4;

DELETE FROM employee
WHERE id = 5;
```





