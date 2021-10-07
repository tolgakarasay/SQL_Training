# Ödev 8

1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

```  sql
CREATE TABLE employee (
	id SERIAL PRIMARY KEY,
	name VARCHAR(50) NOT NULL,
	birthday DATE,
	email VARCHAR(100)
);
```

2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

```  sql
insert into employee (name, birthday, email) values ('Wynny Medler', '1959-06-30', 'wmedler0@oakley.com');
insert into employee (name, birthday, email) values ('Victoria Skeeles', '1955-02-04', 'vskeeles1@youtube.com');
insert into employee (name, birthday, email) values ('Gabriellia Haversum', '1996-04-24', 'ghaversum2@nytimes.com');
insert into employee (name, birthday, email) values ('Ferne Moralee', '1955-06-06', 'fmoralee3@omniture.com');
insert into employee (name, birthday, email) values ('Willey Bolesworth', '1971-09-03', 'wbolesworth4@usgs.gov');
insert into employee (name, birthday, email) values ('Lou Swadling', '1966-02-06', 'lswadling5@360.cn');
insert into employee (name, birthday, email) values ('Cathi Ciottoi', '1982-02-04', 'cciottoi6@wordpress.com');
insert into employee (name, birthday, email) values ('Giuseppe Kindred', '1964-05-20', 'gkindred7@themeforest.net');
insert into employee (name, birthday, email) values ('Ash Boise', '1980-02-09', 'aboise8@craigslist.org');
insert into employee (name, birthday, email) values ('Naomi Chevalier', '1951-11-07', 'nchevalier9@mozilla.org');
insert into employee (name, birthday, email) values ('Irvin Verryan', '2000-12-23', 'iverryana@jimdo.com');
insert into employee (name, birthday, email) values ('Frederick Tulley', '1990-04-14', 'ftulleyb@slate.com');
insert into employee (name, birthday, email) values ('Aldo Jakubovski', '1963-08-06', 'ajakubovskic@ycombinator.com');
insert into employee (name, birthday, email) values ('Roshelle McCarron', '1979-12-18', 'rmccarrond@tinyurl.com');
insert into employee (name, birthday, email) values ('Phelia Marrian', '1941-08-22', 'pmarriane@cornell.edu');
insert into employee (name, birthday, email) values ('Dorian Dronsfield', '1982-09-21', 'ddronsfieldf@mit.edu');
insert into employee (name, birthday, email) values ('Pearle Merring', '1944-07-22', 'pmerringg@vimeo.com');
insert into employee (name, birthday, email) values ('Merwin Turneaux', '1984-03-22', 'mturneauxh@sohu.com');
insert into employee (name, birthday, email) values ('Abie Barks', '1940-06-12', 'abarksi@dailymotion.com');
insert into employee (name, birthday, email) values ('Annissa Sisland', '2000-03-02', 'asislandj@ebay.com');
insert into employee (name, birthday, email) values ('Burg Stringfellow', '1990-05-03', 'bstringfellowk@lycos.com');
insert into employee (name, birthday, email) values ('Nerty Barz', '1989-06-01', 'nbarzl@narod.ru');
insert into employee (name, birthday, email) values ('Ruddy Josefowicz', '1951-12-27', 'rjosefowiczm@purevolume.com');
insert into employee (name, birthday, email) values ('Delly Withey', '1944-05-04', 'dwitheyn@hud.gov');
insert into employee (name, birthday, email) values ('Ulises Tapsell', '1952-12-25', 'utapsello@census.gov');
insert into employee (name, birthday, email) values ('Joete Thieme', '1986-08-09', 'jthiemep@amazon.co.uk');
insert into employee (name, birthday, email) values ('Arnoldo Gloyens', '1957-07-09', 'agloyensq@tiny.cc');
insert into employee (name, birthday, email) values ('Charline Metterick', '1954-07-09', 'cmetterickr@amazon.co.uk');
insert into employee (name, birthday, email) values ('Rutter Karpf', '1986-09-28', 'rkarpfs@lycos.com');
insert into employee (name, birthday, email) values ('Sarita Bartholomaus', '1968-05-24', 'sbartholomaust@dell.com');
insert into employee (name, birthday, email) values ('Elroy Cleere', '1973-10-27', 'ecleereu@ucoz.ru');
insert into employee (name, birthday, email) values ('Krishnah Abbots', '1998-07-31', 'kabbotsv@tamu.edu');
insert into employee (name, birthday, email) values ('Beret McDuffy', '1964-01-07', 'bmcduffyw@homestead.com');
insert into employee (name, birthday, email) values ('Curr Yerson', '1991-03-12', 'cyersonx@admin.ch');
insert into employee (name, birthday, email) values ('Lil Buckoke', '1960-01-21', 'lbuckokey@google.com.hk');
insert into employee (name, birthday, email) values ('Cindra Maestro', '1950-10-16', 'cmaestroz@freewebs.com');
insert into employee (name, birthday, email) values ('Alena Muncaster', '1985-06-30', 'amuncaster10@dailymail.co.uk');
insert into employee (name, birthday, email) values ('Lynette Syder', '1963-10-22', 'lsyder11@va.gov');
insert into employee (name, birthday, email) values ('Ramona Tuffley', '1969-06-12', 'rtuffley12@feedburner.com');
insert into employee (name, birthday, email) values ('Jocelin Caplen', '1978-11-16', 'jcaplen13@etsy.com');
insert into employee (name, birthday, email) values ('Lina Mickleburgh', '1975-04-24', 'lmickleburgh14@icq.com');
insert into employee (name, birthday, email) values ('Ashlee Crucitti', '1996-01-28', 'acrucitti15@scientificamerican.com');
insert into employee (name, birthday, email) values ('Loydie Hughs', '1980-08-25', 'lhughs16@samsung.com');
insert into employee (name, birthday, email) values ('Eartha Hadrill', '1962-06-06', 'ehadrill17@sogou.com');
insert into employee (name, birthday, email) values ('Glori Stovine', '1940-05-28', 'gstovine18@google.co.jp');
insert into employee (name, birthday, email) values ('Nonah Tooby', '1991-06-12', 'ntooby19@1688.com');
insert into employee (name, birthday, email) values ('Andreas MacMeeking', '1963-04-23', 'amacmeeking1a@hugedomains.com');
insert into employee (name, birthday, email) values ('Erhart Ilive', '1955-06-07', 'eilive1b@prweb.com');
insert into employee (name, birthday, email) values ('Janeva Hentze', '1950-04-13', 'jhentze1c@foxnews.com');
insert into employee (name, birthday, email) values ('Gizela Keeting', '1986-01-29', 'gkeeting1d@baidu.com');
```

3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

```  sql
-- update 1 :
UPDATE employee
SET birthday = '1980-01-01',
    email = 'nonah@patika.dev'
WHERE name = 'Nonah Tooby';

-- update 2 :
UPDATE employee
SET name = 'Thomas Edison',
    birthday = '1970-01-01',
    email = 'thomas@patika.dev'
WHERE id = 6;

-- update 3 :
UPDATE employee
SET email = 'arnoldo@patika.dev'
WHERE id = 27;

-- update 4 :
UPDATE employee
SET email = 'elvis@patika.dev',
    name = 'Elvis Presley'
WHERE birthday = '1998-07-31';

-- update 5 :
UPDATE employee
SET name = 'Nikola Tesla',
    email = 'nikola@patika.dev',
    birthday = '1950-01-01'
WHERE email = 'jthiemep@amazon.co.uk';
```

4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

```  sql
-- delete 1 :
DELETE FROM employee
WHERE id = 23;

-- delete 2 :
DELETE FROM employee
WHERE name = 'Beret McDuffy';

-- delete 3 :
DELETE FROM employee
WHERE birthday = '1940-05-28';

-- delete 4 :
DELETE FROM employee
WHERE email = 'sbartholomaust@dell.com';

-- delete 5 :
DELETE FROM employee
WHERE name LIKE  'P%';
```