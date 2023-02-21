# pyslawa-test
PT

TASK 1


Subtask1

7 pkt


Subtask3 

Cześć, nazywam się Beata. Wzięłam udział w projekcie, bo chcę starać się o pracę testera. Szukam dla siebie możliwości pracy w branży IT. Posiadam cechy przydatne w  pracy testera. Jestem komunikatywna i umiem w relacje. Potrafię wyrażać moje myśli w mowie i piśmie. Umiem być zdecydowana i konkretna. Posiadam zmysł krytycznego i analitycznego myślenia. Jestem też dokładna.


Subtask 4

1. Aplikacja służy do zarządzania graczami, meczami i do tworzenia raportów. W aplikacji można dodać informacje o graczach oraz o ich stylu gry oraz o meczach, które rozegrali. Tworzone są również raporty podsumowujące grę poszczególnych zawodników. Na stronie można wyszukać profil gracza.
2. Funkcjonalności, jakie zawiera aplikacja to możliwość dodania zawodnika i edytowania jego profilu. Z lewej strony aplikacji, znajduje się spis treści, a w nim: link do strony głównej, link do opisów graczy, mozliwość zmiany jezyka- na polski lub angielski. Na górze strony znajdują się statystyki dotyczące liczby graczy, ilości meczy, raportów, akcji. W głównym menu znajduje sie link do Dev Team Contact. Link pomocniczy, służący dodaniu gracza oraz listę kilku ostatnich aktywności osób tworzących stronę. Aplikacja wydaje się intuicyjna. Jeśli miałabym coś zmienić, to dodałabym do czterech prostokątów ze statystykami na górze strony, tych z ilością graczy, meczy, raportów akcji. możliwość kliknięcia na te pola i zeby one przekierowywały użytkownika do tych graczy, meczy, raportów oraz akcji. Pomogłoby to łatwiej wejść i przeczytać informacje dotyczące tych dziedzin funkcjonowania strony. Jeśli chodzi o wyszukiwarkę graczy, dodałabym ją tak, aby było ją widać od razu po wejściu na stronę, w bardziej widoczny sposób. Według mnie, jest ona zbyt mało wyeksponowana, a jest ona potrzebna oosbom, które chcą wyszukać profil gracza i zrobić to szybko. 
3. Interfejs jest estetyczny, ale sprawia na mnie wrażenie smutnego, bez energii. A przecież sport, gra w piłkę budzi w ludziach olbrzymie emocje. Pokombinowałabym z kolorami. Ten biały i niebieski to takie depresyjne, "szpitalne" barwy. Jesli chodzi o logo, to może warto byłoby poszukać czegoś bardziej nawiązującego do sportu lub piłki. Nie rozumiem, w jaki sposób odcisk palca, ma się łączyć z tym tematem. No chyba, że jest to odcisk palca jakiegoś słynnego piłkarza:-).
4. Aplikacja wydaje mi się intuicyjna, jeśli chodzi o dodawanie nowego gracza.
5. Jeśli chodzi o devtoolsy, to nie pokazują mi one żadnych błędów.![obraz](https://user-images.githubusercontent.com/122923764/213015402-3884fb73-e1de-4508-936e-8b2f3803c4ab.png)


TASK 3

https://docs.google.com/document/d/1AheJJ0ihnxq2By4u6zF8au2IvofsPDSfs-kYAzGNGcU/edit?usp=sharing



TASK 4

Subtask 1 i 2: https://docs.google.com/document/d/1_qq9xA3eZdU2f_etYi7xWnSZsCKCNYx_xoJSY1yv2V4/edit?usp=sharing


Subtask 3

1. Do czego służy ta aplikacja? Jaki jest cel tej aplikacji? Celem aplikacji jest zarabianie pieniędzy poprzez pobieranie opłat od użytkowników. Aplikacja pobiera również dane użytkowników. Służy ona do poprawy dobrostanu psychicznego poprzez relaksację, medytację, mindfulness, redukcję stresu.
2. Kto ma być użytkownikiem końcowym aplikacji? Użytkownikiem końcowym, mają być użytkownicy aplikacji. Osoby, które chcą poprawić swoje samopoczucie psychiczne.
3. Czy według Ciebie aplikacja jest user friendly? Według mnie, aplikacja jest przyjazna dla użytkownika. Jest intuicyjna oraz ładna graficznie.
4. Jak byś usprawnił aplikację? Co byś w niej poprawił. Czy masz jakiś pomysł na dodatkową funkcjonalność? Dodałabym funkcję zapisania, aby odtworzyć dane nagranie później. Pomyślałabym również nad tym, by zamieścić w tej aplikacji nagranie Treningu autogennego Schultza. Jako użytkowniczka oczekiwałabym, aby w opisie poszczególnych autorów, pojawiły się dokładniejsze informacje na temat wykształcenia autorów oraz ich kompetencji.
5. Jakie dostrzegasz różnice pomiędzy testowaniem aplikacji internetowej, a natywnej? Niestety za słabo się na tym znam, żeby dostrzec różnice.


TASK 5

1.
SELECT * FROM `actors` ORDER BY surname ASC; 

![image](https://user-images.githubusercontent.com/122923764/220460222-3269c026-20dd-434b-ba32-494d331585b4.png)


2.
SELECT * FROM `movies`WHERE year_of_production=2019;

![image](https://user-images.githubusercontent.com/122923764/220460363-5762a4af-d8f3-400d-b77c-eb47cca3efba.png)


3.
SELECT * FROM `movies` WHERE year_of_production BETWEEN 1900 AND 1999;

![image](https://user-images.githubusercontent.com/122923764/220460479-a3d350ec-e715-404e-ac80-90001f529840.png)


4.
SELECT  title, price
FROM movies
WHERE price< 7;

![image](https://user-images.githubusercontent.com/122923764/220460637-30e68964-ca67-457e-abb4-55345eeb5f9a.png)

5.

SELECT  actor_id, name, surname
FROM actors
WHERE actor_id > 3 and actor_id < 8;

![image](https://user-images.githubusercontent.com/122923764/220460791-cdb13f33-d2ba-4149-944f-ae88e0228aad.png)


6.

SELECT customer_id, name, surname, email
FROM customers
WHERE customer_id = 2 or customer_id = 4 or customer_id = 6;

![image](https://user-images.githubusercontent.com/122923764/220460921-178f62b5-7e61-4703-b103-9c97eb1e4f5f.png)


7.

SELECT customer_id, name, surname, email
FROM customers
WHERE customer_id IN (1, 3, 5);

![image](https://user-images.githubusercontent.com/122923764/220461042-b3bbe7b4-2a83-43d4-bb04-21d7aadd0800.png)


8.

SELECT actor_id, name, surname
FROM actors
WHERE name like 'An%';

![image](https://user-images.githubusercontent.com/122923764/220461142-f89b5ddf-40c9-4f0d-bae6-935f58327e26.png)


9.

SELECT customer_id, name, surname, email
FROM customers
WHERE email is null;

![image](https://user-images.githubusercontent.com/122923764/220462853-76798ba7-cc77-4f0a-9e2b-a5f505ae21b0.png)




10.

SELECT  movie_id, title, year_of_production, price
FROM movies
WHERE price > 9 and movie_id BETWEEN 2 AND 8;

![image](https://user-images.githubusercontent.com/122923764/220461978-cbad443d-5a4c-40cd-9b1a-a59ad1535645.png)


TASK 6

SUBTASK 1

11.

select customer_id, name, surname, replace(surname,'Muler','Miler') 
from customers;

![obraz](https://user-images.githubusercontent.com/122923764/220191720-f807a2aa-a1f2-4c14-8948-452baef9b4f0.png)

12.

SELECT name, email, movie_id FROM customers INNER JOIN sale ON customers.customer_id = sale.customer_id WHERE sale_date = '2021-04-13';


![image](https://user-images.githubusercontent.com/122923764/220458759-81b5fc0d-c015-49dc-b387-3686eb2e7659.png)

13.
DELETE FROM customers
WHERE customer_id = 4;
INSERT INTO customers (customer_id, name, surname, email) VALUES ('4', 'Patrycja', 'Komor', 'pati@mail.com');
SELECT *
FROM customers
ORDER BY customer_id ASC;


![image](https://user-images.githubusercontent.com/122923764/220458996-4751431d-bf80-4cf5-adc8-9130d75cebad.png)

 
14.
SELECT name, surname, title FROM customers INNER JOIN movies ON customers.customer_id = movies.movie_id WHERE year_of_production BETWEEN '1979' AND '2020';


![image](https://user-images.githubusercontent.com/122923764/220459096-89002b71-0b8c-4a25-a286-38d11b3ee2f8.png)


15.
ALTER TABLE customers ADD COLUMN pseudonym DECIMAL(11,2) NOT NULL;
SELECT CONCAT(LEFT(surname,2), LEFT(name,1)) AS "pseudonym" FROM customers;


![image](https://user-images.githubusercontent.com/122923764/220459195-28cbff16-106c-45b3-b182-43c66c747d15.png)

 
16.
SELECT DISTINCT title FROM movies;


![image](https://user-images.githubusercontent.com/122923764/220459278-c1aff63f-a0b1-4041-862d-634e7fad3119.png)

 
17.
select customer_id, name, surname FROM customers UNION Select actor_id, name, surname from actors order by customer_id asc;


 ![image](https://user-images.githubusercontent.com/122923764/220459341-89b4f886-bb94-421f-a91b-4fc307792afa.png)



18.
SELECT *, price+2.5 AS NewPrice2 FROM movies WHERE year_of_production > 2000;


![image](https://user-images.githubusercontent.com/122923764/220459422-2f3ef497-10a6-4be6-bf36-cc52beff2e76.png)

 

19.
select actor_id, name, surname, movie_id, title 
FROM actors, movies
WHERE actor_id = 4 and movie_id = 4;


![image](https://user-images.githubusercontent.com/122923764/220459531-15a932a4-1058-456e-a150-e18c78f52384.png)

 
20.
INSERT INTO customers (customer_id, name, surname, email, pseudonym) VALUES ('7', 'Honia', 'Stuczka-Kucharska', 'honia@mail.com', 'Hoa');


![image](https://user-images.githubusercontent.com/122923764/220459629-2bd14d8f-737f-4baf-ac57-56f8d71e73dc.png)


SUBTASK 2


SUBTASK 3
