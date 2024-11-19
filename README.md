# PostgreSQL

1) test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.
CREATE TABLE employee(
	id INTEGER PRIMARY KEY,
	name VARCHAR(50),
	birthday DATE,
	email VARCHAR(100)
);

2) Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.
insert into employee (id, name, birthday, email) values (1, 'Eve Morphew', '2010-12-21', 'emorphew0@wordpress.com');
insert into employee (id, name, birthday, email) values (2, 'Caritta Shottin', '2015-10-07', 'cshottin1@slate.com');
insert into employee (id, name, birthday, email) values (3, 'Julita Worboy', '2012-04-23', 'jworboy2@imageshack.us');
insert into employee (id, name, birthday, email) values (4, 'Bjorn Scrivinor', '2006-11-29', 'bscrivinor3@illinois.edu');
insert into employee (id, name, birthday, email) values (5, 'Kingsley Blaw', '2013-01-20', 'kblaw4@devhub.com');
insert into employee (id, name, birthday, email) values (6, 'Johnathon Josovich', '2006-03-14', 'jjosovich5@disqus.com');
insert into employee (id, name, birthday, email) values (7, 'Sophie Radnedge', '2019-04-21', 'sradnedge6@cbslocal.com');
insert into employee (id, name, birthday, email) values (8, 'Jodee Ewan', '2012-01-25', 'jewan7@amazon.de');
insert into employee (id, name, birthday, email) values (9, 'Klaus Darrington', '2019-01-22', 'kdarrington8@washington.edu');
insert into employee (id, name, birthday, email) values (10, 'Jaymee Scamp', '2014-07-02', 'jscamp9@ed.gov');
insert into employee (id, name, birthday, email) values (11, 'Edee Prestidge', '1996-11-26', 'eprestidgea@flickr.com');
insert into employee (id, name, birthday, email) values (12, 'Celestina Fearn', '2000-09-18', 'cfearnb@si.edu');
insert into employee (id, name, birthday, email) values (13, 'Tedie Bottleson', '2003-01-16', 'tbottlesonc@people.com.cn');
insert into employee (id, name, birthday, email) values (14, 'Federica Polhill', '2020-01-21', 'fpolhilld@wikimedia.org');
insert into employee (id, name, birthday, email) values (15, 'Freda Infantino', '1996-10-27', 'finfantinoe@uol.com.br');
insert into employee (id, name, birthday, email) values (16, 'Nichole Sibyllina', '2007-02-25', 'nsibyllinaf@prweb.com');
insert into employee (id, name, birthday, email) values (17, 'Nichol Heinlein', '2007-06-23', 'nheinleing@abc.net.au');
insert into employee (id, name, birthday, email) values (18, 'Harriette Twyford', '2003-12-11', 'htwyfordh@cloudflare.com');
insert into employee (id, name, birthday, email) values (19, 'Joannes Calbreath', '1998-04-25', 'jcalbreathi@homestead.com');
insert into employee (id, name, birthday, email) values (20, 'Milka Newburn', '2012-05-25', 'mnewburnj@booking.com');
insert into employee (id, name, birthday, email) values (21, 'Berti Verheyden', '2023-12-15', 'bverheydenk@sun.com');
insert into employee (id, name, birthday, email) values (22, 'Bunnie Thirst', '2001-10-22', 'bthirstl@elegantthemes.com');
insert into employee (id, name, birthday, email) values (23, 'Engelbert Broomhall', '2014-05-27', 'ebroomhallm@latimes.com');
insert into employee (id, name, birthday, email) values (24, 'Aurora Realph', '2016-01-28', 'arealphn@yellowpages.com');
insert into employee (id, name, birthday, email) values (25, 'Bernice Philipeau', '2000-06-03', 'bphilipeauo@is.gd');
insert into employee (id, name, birthday, email) values (26, 'Zane Loffill', '2006-06-25', 'zloffillp@nih.gov');
insert into employee (id, name, birthday, email) values (27, 'Douglas Faley', '2024-02-18', 'dfaleyq@symantec.com');
insert into employee (id, name, birthday, email) values (28, 'Jacquenette Alenin', '2003-04-04', 'jaleninr@nydailynews.com');
insert into employee (id, name, birthday, email) values (29, 'Jinny McGaugey', '2005-09-27', 'jmcgaugeys@privacy.gov.au');
insert into employee (id, name, birthday, email) values (30, 'Perla Mowson', '2012-03-22', 'pmowsont@ted.com');
insert into employee (id, name, birthday, email) values (31, 'Murdoch Sandwick', '2008-09-14', 'msandwicku@nature.com');
insert into employee (id, name, birthday, email) values (32, 'Josephina Swanwick', '2012-02-26', 'jswanwickv@xinhuanet.com');
insert into employee (id, name, birthday, email) values (33, 'Keene Castree', '2010-09-27', 'kcastreew@opera.com');
insert into employee (id, name, birthday, email) values (34, 'Fayette Zaple', '2002-07-16', 'fzaplex@arizona.edu');
insert into employee (id, name, birthday, email) values (35, 'Mariana Van Daalen', '2000-09-22', 'mvany@github.io');
insert into employee (id, name, birthday, email) values (36, 'Tremain O''Lehane', '1999-01-14', 'tolehanez@dot.gov');
insert into employee (id, name, birthday, email) values (37, 'Rolph Marusyak', '2012-09-08', 'rmarusyak10@barnesandnoble.com');
insert into employee (id, name, birthday, email) values (38, 'Casey Guillart', '1998-05-19', 'cguillart11@foxnews.com');
insert into employee (id, name, birthday, email) values (39, 'Gauthier Hotchkin', '2003-12-18', 'ghotchkin12@example.com');
insert into employee (id, name, birthday, email) values (40, 'Gnni Webborn', '2013-06-03', 'gwebborn13@msu.edu');
insert into employee (id, name, birthday, email) values (41, 'Broddie Hackney', '2004-08-31', 'bhackney14@etsy.com');
insert into employee (id, name, birthday, email) values (42, 'Nolan Durnall', '2019-03-06', 'ndurnall15@weibo.com');
insert into employee (id, name, birthday, email) values (43, 'Valentijn Coggeshall', '2015-06-24', 'vcoggeshall16@admin.ch');
insert into employee (id, name, birthday, email) values (44, 'Carlie Scorthorne', '2001-05-24', 'cscorthorne17@nifty.com');
insert into employee (id, name, birthday, email) values (45, 'Sharron Farrey', '2016-08-15', 'sfarrey18@wikimedia.org');
insert into employee (id, name, birthday, email) values (46, 'Lucian Coverdill', '2012-09-03', 'lcoverdill19@biglobe.ne.jp');
insert into employee (id, name, birthday, email) values (47, 'Garreth Cokly', '2020-08-04', 'gcokly1a@diigo.com');
insert into employee (id, name, birthday, email) values (48, 'Jammie Collimore', '2024-05-11', 'jcollimore1b@mac.com');
insert into employee (id, name, birthday, email) values (49, 'Ingra Childes', '2001-07-04', 'ichildes1c@ucsd.edu');
insert into employee (id, name, birthday, email) values (50, 'Byrom Samart', '2000-10-05', 'bsamart1d@photobucket.com');
insert into employee (id, name, birthday, email) values (51, 'Victor Spinage', '2021-05-30', 'vspinage1e@hc360.com');
insert into employee (id, name, birthday, email) values (52, 'Sonja Titterington', '2021-10-10', 'stitterington1f@example.com');
insert into employee (id, name, birthday, email) values (53, 'Giovanni Chapiro', '2011-10-07', 'gchapiro1g@mysql.com');
insert into employee (id, name, birthday, email) values (54, 'Kyla Libreros', '2021-05-18', 'klibreros1h@cocolog-nifty.com');
insert into employee (id, name, birthday, email) values (55, 'Kayne Gjerde', '1999-12-27', 'kgjerde1i@un.org');
insert into employee (id, name, birthday, email) values (56, 'Nikolos Durman', '2007-12-14', 'ndurman1j@simplemachines.org');
insert into employee (id, name, birthday, email) values (57, 'Gonzales Bevar', '2012-12-25', 'gbevar1k@webnode.com');
insert into employee (id, name, birthday, email) values (58, 'Julie Sutterfield', '2017-10-06', 'jsutterfield1l@eventbrite.com');
insert into employee (id, name, birthday, email) values (59, 'Averyl Murty', '2015-03-11', 'amurty1m@virginia.edu');
insert into employee (id, name, birthday, email) values (60, 'Helene Blatcher', '2013-05-07', 'hblatcher1n@ox.ac.uk');
insert into employee (id, name, birthday, email) values (61, 'Bastian Kelsell', '2022-01-02', 'bkelsell1o@yahoo.co.jp');
insert into employee (id, name, birthday, email) values (62, 'Armin McMurray', '2016-02-01', 'amcmurray1p@redcross.org');
insert into employee (id, name, birthday, email) values (63, 'Cherianne Gierck', '2012-10-02', 'cgierck1q@craigslist.org');
insert into employee (id, name, birthday, email) values (64, 'Cleavland Mc Grath', '2010-02-07', 'cmc1r@tuttocitta.it');
insert into employee (id, name, birthday, email) values (65, 'Jayme Colloff', '2011-02-02', 'jcolloff1s@whitehouse.gov');
insert into employee (id, name, birthday, email) values (66, 'Gilburt Jenson', '2007-05-08', 'gjenson1t@qq.com');
insert into employee (id, name, birthday, email) values (67, 'Judah McOmish', '2017-09-12', 'jmcomish1u@un.org');
insert into employee (id, name, birthday, email) values (68, 'Micheline Opie', '2008-11-22', 'mopie1v@home.pl');
insert into employee (id, name, birthday, email) values (69, 'Abey Attwater', '2013-12-13', 'aattwater1w@ucoz.com');
insert into employee (id, name, birthday, email) values (70, 'Estel Speddin', '2010-10-31', 'espeddin1x@pbs.org');
insert into employee (id, name, birthday, email) values (71, 'Elyssa Crambie', '2012-10-03', 'ecrambie1y@google.co.jp');
insert into employee (id, name, birthday, email) values (72, 'Alan Cursons', '2004-12-08', 'acursons1z@princeton.edu');
insert into employee (id, name, birthday, email) values (73, 'Whitney Eberz', '2014-07-28', 'weberz20@toplist.cz');
insert into employee (id, name, birthday, email) values (74, 'Moore Boston', '2004-10-02', 'mboston21@slashdot.org');
insert into employee (id, name, birthday, email) values (75, 'Cris Corain', '2015-01-05', 'ccorain22@tuttocitta.it');
insert into employee (id, name, birthday, email) values (76, 'Phyllys Pelchat', '2013-12-25', 'ppelchat23@gizmodo.com');
insert into employee (id, name, birthday, email) values (77, 'Dru Morby', '2006-02-21', 'dmorby24@economist.com');
insert into employee (id, name, birthday, email) values (78, 'Seana Nockalls', '2008-05-11', 'snockalls25@theatlantic.com');
insert into employee (id, name, birthday, email) values (79, 'Hartley Lait', '1998-03-07', 'hlait26@dailymotion.com');
insert into employee (id, name, birthday, email) values (80, 'Earlie Coppenhall', '2016-03-26', 'ecoppenhall27@howstuffworks.com');
insert into employee (id, name, birthday, email) values (81, 'Dacia Koppel', '2024-03-24', 'dkoppel28@joomla.org');
insert into employee (id, name, birthday, email) values (82, 'Edith Boyfield', '2010-10-01', 'eboyfield29@state.gov');
insert into employee (id, name, birthday, email) values (83, 'Inglebert Farahar', '2008-08-29', 'ifarahar2a@techcrunch.com');
insert into employee (id, name, birthday, email) values (84, 'Bartolemo Luten', '1997-02-12', 'bluten2b@vistaprint.com');
insert into employee (id, name, birthday, email) values (85, 'Veronique Rodgman', '2001-01-17', 'vrodgman2c@paginegialle.it');
insert into employee (id, name, birthday, email) values (86, 'Maribeth Bolino', '2015-11-25', 'mbolino2d@vkontakte.ru');
insert into employee (id, name, birthday, email) values (87, 'Andrej McGow', '2019-07-05', 'amcgow2e@soundcloud.com');
insert into employee (id, name, birthday, email) values (88, 'Jephthah Hellard', '2001-07-12', 'jhellard2f@1688.com');
insert into employee (id, name, birthday, email) values (89, 'Kimble Marmyon', '2016-08-01', 'kmarmyon2g@shareasale.com');
insert into employee (id, name, birthday, email) values (90, 'Frederick Pendreigh', '2006-02-09', 'fpendreigh2h@amazon.co.jp');
insert into employee (id, name, birthday, email) values (91, 'Von Frigout', '1999-08-22', 'vfrigout2i@barnesandnoble.com');
insert into employee (id, name, birthday, email) values (92, 'Bethena Mallion', '2010-07-14', 'bmallion2j@cbslocal.com');
insert into employee (id, name, birthday, email) values (93, 'Korella Bergin', '2011-10-29', 'kbergin2k@intel.com');
insert into employee (id, name, birthday, email) values (94, 'Welbie Grundle', '2010-11-28', 'wgrundle2l@wordpress.com');
insert into employee (id, name, birthday, email) values (95, 'Jessalyn Bowser', '2009-07-15', 'jbowser2m@ovh.net');
insert into employee (id, name, birthday, email) values (96, 'Cristen Hastings', '2013-03-18', 'chastings2n@stanford.edu');
insert into employee (id, name, birthday, email) values (97, 'Corinna Utting', '2020-03-31', 'cutting2o@dion.ne.jp');
insert into employee (id, name, birthday, email) values (98, 'Hubie Swiers', '2023-10-09', 'hswiers2p@miibeian.gov.cn');
insert into employee (id, name, birthday, email) values (99, 'Irene Ricker', '2020-03-18', 'iricker2q@naver.com');
insert into employee (id, name, birthday, email) values (100, 'Celeste Senecaux', '2008-12-22', 'csenecaux2r@sohu.com');

3) Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.
UPDATE employee SET name = 'Selim' WHERE id = 52;

UPDATE employee SET birthday = '1996-01-16' WHERE id = 7;

UPDATE employee SET email = 'selim@dogan.com' WHERE id = 34;

UPDATE employee SET name = 'Selami' WHERE id = 3;

UPDATE employee SET id = '1905' WHERE id = 100;


4) Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.
DELETE from employee WHERE name = '"Eve Morphew"' ;

DELETE from employee WHERE birthday = '"2006-11-29"';








//ödev 9
SELECT city, country FROM city
JOIN country ON country.country_id = city.country_id;

SELECT first_name, last_name FROM customer
JOIN payment ON payment.customer_id = customer.customer_id;


SELECT rental.rental_id, first_name, last_name FROM customer
JOIN rental ON rental.customer_id = customer.customer_id;

DELETE from employee WHERE email = '"jewan7@amazon.de"';

DELETE from employee WHERE name = '"Bunnie Thirst"';

DELETE from employee WHERE id = '6';





//ödev10
Aşağıdaki sorgu senaryolarını dvdrental örnek veri tabanı üzerinden gerçekleştiriniz.



1-> city tablosu ile country tablosunda bulunan şehir (city) ve ülke (country) isimlerini birlikte görebileceğimiz LEFT JOIN sorgusunu yazınız.
2-> customer tablosu ile payment tablosunda bulunan payment_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz RIGHT JOIN sorgusunu yazınız.
3-> customer tablosu ile rental tablosunda bulunan rental_id ile customer tablosundaki first_name ve last_name isimlerini birlikte görebileceğimiz FULL JOIN sorgusunu yazınız.

--QUERY1
	--SELECT city.city ,country.country
	--FROM city
	--LEFT JOIN country 
	--ON city.country_id = country.country_id;

--QUERY2
	--SELECT payment_id,customer.first_name,customer.last_name
	--FROM customer
	--RIGHT JOIN payment
	--ON customer.customer_id = payment.customer_id;

--QUERY3
--SELECT customer.first_name, customer.last_name
--FROM customer
--FULL JOIN rental
--ON rental.customer_id = customer.customer_id;




//ödev11
Question 1: actor ve customer tablolarında bulunan first_name sütunları için tüm verileri sıralayalım.

    (
    SELECT first_name FROM actor
    )
        
    UNION

    (
    SELECT first_name FROM customer
    )
Question 2: actor ve customer tablolarında bulunan first_name sütunları için kesişen verileri sıralayalım.

    (
    SELECT first_name FROM actor
    )
        
    INTERSECT

    (
    SELECT first_name FROM customer
    )
Question 3: actor ve customer tablolarında bulunan first_name sütunları için ilk tabloda bulunan ancak ikinci tabloda bulunmayan verileri sıralayalım.

    (
    SELECT first_name FROM actor
    )
        
    EXCEPT

    (
    SELECT first_name FROM customer
    )
Question 4: İlk 3 sorguyu tekrar eden veriler için de yapalım.

    
    SELECT first_name FROM actor
    
        
    UNION ALL

    (
    SELECT first_name FROM customer
    )
-----------------------------------------------
    (
    SELECT first_name FROM actor
    )
        
    INTERSECT ALL

    (
    SELECT first_name FROM customer
    )
-----------------------------------------------
    (
    SELECT first_name FROM actor
    )
        
    EXCEPT ALL

    (
    SELECT first_name FROM customer
    )





    //ödev12
    Question 1: film tablosunda film uzunluğu length sütununda gösterilmektedir. Uzunluğu ortalama film uzunluğundan fazla kaç tane film vardır?

    SELECT * FROM film
    WHERE length > 
    (
        SELECT AVG(length) FROM film
    );
Question 2: film tablosunda en yüksek rental_rate değerine sahip kaç tane film vardır?

    SELECT COUNT(*) FROM film
    WHERE rental_rate = 
    (
        SELECT MAX(rental_rate) FROM film
    );
Question 3: film tablosunda en düşük rental_rate ve en düşün replacement_cost değerlerine sahip filmleri sıralayınız.

    SELECT * FROM film
    WHERE replacement_cost = 
    (
        SELECT MIN(replacement_cost) FROM film
    )
    AND rental_rate = 
    (
        SELECT MIN(rental_rate) FROM film
    )
Question 4: payment tablosunda en fazla sayıda alışveriş yapan müşterileri(customer) sıralayınız.

    SELECT customer.customer_id, customer.first_name, customer.last_name,COUNT(payment.payment_id) 
    FROM customer
    JOIN payment ON customer.customer_id = payment.customer_id
    GROUP BY customer.customer_id
    ORDER BY COUNT(payment_id) DESC;
