# SQL-ODEV-8
Patika.dev > SQL > Tablolarla Çalışmak > Ödev8

## 1. test veritabanınızda employee isimli sütun bilgileri id(INTEGER), name VARCHAR(50), birthday DATE, email VARCHAR(100) olan bir tablo oluşturalım.

      CREATE TABLE employee (
      id INTEGER,
      name VARCHAR(50),
      birthday DATE,
      email VARCHAR(100)
      );

## 2. Oluşturduğumuz employee tablosuna 'Mockaroo' servisini kullanarak 50 adet veri ekleyelim.

      insert into employee (id, name, birthday, email) values (1, 'Carlee Scarrott', '1914-05-08', 'cscarrott0@shop-pro.jp');
      insert into employee (id, name, birthday, email) values (2, 'Binky Stobo', '1956-02-23', 'bstobo1@latimes.com');
      insert into employee (id, name, birthday, email) values (3, 'Free Gamil', '1984-10-30', 'fgamil2@gmpg.org');
      insert into employee (id, name, birthday, email) values (4, 'Jenifer Faucherand', '1915-02-28', 'jfaucherand3@technorati.com');
      insert into employee (id, name, birthday, email) values (5, 'Kristy Lusher', '1922-04-04', 'klusher4@twitter.com');
      insert into employee (id, name, birthday, email) values (6, 'Thomasa Mewis', '1923-10-13', 'tmewis5@rakuten.co.jp');
      insert into employee (id, name, birthday, email) values (7, 'Lauraine Symms', '1907-07-08', 'lsymms6@google.fr');
      insert into employee (id, name, birthday, email) values (8, 'Kania Castagne', '1991-01-05', 'kcastagne7@addtoany.com');
      insert into employee (id, name, birthday, email) values (9, 'Randolph Moultrie', '1955-10-29', 'rmoultrie8@facebook.com');
      insert into employee (id, name, birthday, email) values (10, 'Lexy Crackel', '1952-04-05', 'lcrackel9@census.gov');
      insert into employee (id, name, birthday, email) values (11, 'Brennan Braunle', '1936-05-01', 'bbraunlea@ycombinator.com');
      insert into employee (id, name, birthday, email) values (12, 'Felicle Eberst', '1925-03-17', 'feberstb@biglobe.ne.jp');
      insert into employee (id, name, birthday, email) values (13, 'Flinn Radoux', '1909-01-06', 'fradouxc@blogger.com');
      insert into employee (id, name, birthday, email) values (14, 'Patricio Blick', '1942-09-15', 'pblickd@cmu.edu');
      insert into employee (id, name, birthday, email) values (15, 'Maressa Cleveland', '1952-05-29', 'mclevelande@wp.com');
      insert into employee (id, name, birthday, email) values (16, 'Ethel Redhole', '1935-05-06', null);
      insert into employee (id, name, birthday, email) values (17, 'Petronia Brinkworth', '1945-08-05', 'pbrinkworthg@ehow.com');
      insert into employee (id, name, birthday, email) values (18, 'Collie Romayn', '1937-07-15', 'cromaynh@webeden.co.uk');
      insert into employee (id, name, birthday, email) values (19, 'Coletta Gillopp', '1988-06-24', 'cgilloppi@over-blog.com');
      insert into employee (id, name, birthday, email) values (20, 'Christiana Ten Broek', '1938-07-28', 'ctenj@mtv.com');
      insert into employee (id, name, birthday, email) values (21, 'Charlotta Showt', '1945-03-16', 'cshowtk@samsung.com');
      insert into employee (id, name, birthday, email) values (22, 'Rochette Guitton', '1971-08-24', 'rguittonl@howstuffworks.com');
      insert into employee (id, name, birthday, email) values (23, 'Patience Rassmann', '1974-04-07', 'prassmannm@berkeley.edu');
      insert into employee (id, name, birthday, email) values (24, 'Kimberley Kirby', '1921-10-26', 'kkirbyn@flavors.me');
      insert into employee (id, name, birthday, email) values (25, 'Edan Melton', '1928-09-11', 'emeltono@t.co');
      insert into employee (id, name, birthday, email) values (26, 'Winifred Febry', '1942-08-09', 'wfebryp@newyorker.com');
      insert into employee (id, name, birthday, email) values (27, 'Portia de Villier', '1929-11-19', 'pdeq@un.org');
      insert into employee (id, name, birthday, email) values (28, 'Betteann Silvester', '1914-06-16', 'bsilvesterr@soup.io');
      insert into employee (id, name, birthday, email) values (29, 'Luigi Bernasek', '1958-04-30', 'lbernaseks@washington.edu');
      insert into employee (id, name, birthday, email) values (30, 'Mikel Schoroder', '1931-04-12', 'mschorodert@blogtalkradio.com');
      insert into employee (id, name, birthday, email) values (31, 'Carlynne Soltan', '1956-03-23', 'csoltanu@hibu.com');
      insert into employee (id, name, birthday, email) values (32, 'Bartholomeo Sivewright', '1947-06-23', 'bsivewrightv@va.gov');
      insert into employee (id, name, birthday, email) values (33, 'Chet Gollin', '1910-03-20', 'cgollinw@illinois.edu');
      insert into employee (id, name, birthday, email) values (34, 'Rudy Siehard', '1965-06-12', null);
      insert into employee (id, name, birthday, email) values (35, 'Norrie Terbrug', '1930-07-04', null);
      insert into employee (id, name, birthday, email) values (36, 'Jermaine Brumen', '1938-01-10', 'jbrumenz@twitter.com');
      insert into employee (id, name, birthday, email) values (37, 'Merrily Le Barr', '1936-11-21', null);
      insert into employee (id, name, birthday, email) values (38, 'Berny Linebarger', '1911-04-28', 'blinebarger11@miibeian.gov.cn');
      insert into employee (id, name, birthday, email) values (39, 'Guinna O''Moylan', '1947-05-14', 'gomoylan12@sphinn.com');
      insert into employee (id, name, birthday, email) values (40, 'Cathie Morse', '1920-11-15', 'cmorse13@wikipedia.org');
      insert into employee (id, name, birthday, email) values (41, 'Eamon Becke', '1991-10-30', 'ebecke14@topsy.com');
      insert into employee (id, name, birthday, email) values (42, 'Fitzgerald Ogilvy', '1982-09-07', 'fogilvy15@biblegateway.com');
      insert into employee (id, name, birthday, email) values (43, 'Estel Petran', '1944-09-21', 'epetran16@example.com');
      insert into employee (id, name, birthday, email) values (44, 'Kirbie Harradine', '1919-12-29', 'kharradine17@examiner.com');
      insert into employee (id, name, birthday, email) values (45, 'Zerk Tuckey', '1956-11-09', 'ztuckey18@parallels.com');
      insert into employee (id, name, birthday, email) values (46, 'Dianemarie Mattiuzzi', '1962-07-08', 'dmattiuzzi19@cocolog-nifty.com');
      insert into employee (id, name, birthday, email) values (47, 'Mercedes Maughan', '1904-09-24', 'mmaughan1a@imageshack.us');
      insert into employee (id, name, birthday, email) values (48, 'Madlen Snar', '1947-03-06', 'msnar1b@merriam-webster.com');
      insert into employee (id, name, birthday, email) values (49, 'Bridgette Tremathack', '1996-04-14', null);
      insert into employee (id, name, birthday, email) values (50, 'Malena Guite', '1981-01-09', 'mguite1d@google.co.uk');

## 3. Sütunların her birine göre diğer sütunları güncelleyecek 5 adet UPDATE işlemi yapalım.

      UPDATE employee
        SET name = 'Nero Conwell',
            birthday = '1945-10-16',
            email = 'nconwell0@elegantthemes.com'
      WHERE id = 4;

      UPDATE employee
        SET name = 'Allianora Forst',
            birthday = '1923-04-02',
            email = 'aforst1@tripod.com'
      WHERE id = 9;

      UPDATE employee
        SET name = 'Fedora Livesley',
            birthday = '1954-12-08',
            email = 'flivesley2@redcross.org'
      WHERE id = 18;

      UPDATE employee
        SET name = 'Daveta Roisen',
            birthday = '1971-04-12',
            email = 'droisen3@printfriendly.com'
      WHERE id = 24;

      UPDATE employee
        SET name = 'Napoleon Walford',
            birthday = '1971-04-23',
            email = 'nwalford4@wunderground.com'
      WHERE id = 34;

## 4. Sütunların her birine göre ilgili satırı silecek 5 adet DELETE işlemi yapalım.

      DELETE FROM employee
      WHERE id IN (2,9,15,17,26)
      RETURNING *;
