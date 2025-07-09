# qa-portfolio
My Personal QA Portfolio

 Cel:

Po tygodniu 1 – umiesz pisać testy API i znasz podstawy JS

Po tygodniu 2 – piszesz realne testy UI w Cypress, rozumiesz DOM i asynchroniczność

Po tygodniu 3 – budujesz projekt E2E, ogarniasz SQL i łączysz to z testami

Zakładam:

Kurs to “Cypress od podstaw - Automatyzacja testów JavaScript” od Dawid Bugajski/Udemy

Masz min. 2h dziennie, 5 dni w tygodniu

📅 TYDZIEŃ 1 – JS + API + Setup Cypress
Cel: Wejść w JavaScript, testować API w Postmanie, przygotować środowisko Cypress.

🔥 Dzień 1 – JavaScript: Podstawy
Przerób: zmienne (let, const), typy, operatory, instrukcje warunkowe

Zrób 10 małych snippetów JS (np. liczby parzyste, sprawdzanie hasła, itp.)

Zacznij czytać: https://javascript.info

🔥 Dzień 2 – JavaScript: Funkcje, pętle, tablice
Funkcje: deklaracja, parametry, zwracanie wartości

Pętle: for, forEach, while

Tablice i operacje: .push(), .map(), .filter()

🔥 Dzień 3 – API Testing (Postman)
Przetestuj https://reqres.in i https://jsonplaceholder.typicode.com

Zrób:

GET /users

POST /users z body JSON

PUT /users/2

DELETE /users/2

Dodaj testy do zakładki Tests w Postmanie (np. pm.response.to.have.status(200))

🔥 Dzień 4 – Setup Cypress + Pierwszy test
Zainstaluj Cypress (npm init -y, npm install cypress, npx cypress open)

W kursie Udemy przerób: instalacja, struktura folderów, pierwszy test UI

Stwórz test otwierający stronę i klikający przycisk

🔥 Dzień 5 – JavaScript: Obiekty + Async
Obiekty: const user = { name: "John", age: 30 }

Dostęp do pól, destrukturyzacja

async/await: rozumiesz, co to jest promise, jak działa fetch()

Napisz async funkcję pobierającą dane z API

📅 TYDZIEŃ 2 – Cypress UI Testing w praktyce
Cel: Umiesz pisać sensowne testy UI, klikać formularze, walidować dane.

🔥 Dzień 6 – Cypress: DOM + get/contains
cy.get(), cy.contains(), cy.should()

Tworzysz test dla prostego formularza

Zrób test: otwórz stronę, wypełnij pola, kliknij submit, sprawdź rezultat

🔥 Dzień 7 – Cypress: Assertions + input + checkbox
cy.type(), cy.check(), cy.select()

Zrób test: wypełnij formę z różnymi polami i zweryfikuj odpowiedzi

🔥 Dzień 8 – Cypress: Network Requests + intercept
cy.intercept() – mockowanie API

Zrób test, który przechwytuje odpowiedź API i zamienia dane

Przerób lekcję z intercept z kursu Udemy

🔥 Dzień 9 – Custom Commands + Page Objects
Dodaj własny command (np. cy.login())

Stwórz plik z funkcją logowania i reużyj ją w 2 testach

Zastosuj wzorzec Page Object (organizacja kodu)

🔥 Dzień 10 – Projekt Mini
Zrób 3 testy dla wybranej strony (np. todoMVC, fakestoreapi.com):

Test logowania

Test dodania nowego elementu

Test filtrowania lub wyszukiwania

Wrzuć projekt na GitHub z README

📅 TYDZIEŃ 3 – SQL + Integracja + Finalizacja projektu
Cel: Ogarniać dane z backendu + stworzyć projekt QA Portfolio

🔥 Dzień 11 – SQL: SELECT, WHERE, JOIN
Przerób: https://sqlbolt.com

Napisz:

SELECT * FROM users WHERE age > 30

SELECT orders.id, users.name FROM orders JOIN users ON orders.user_id = users.id

🔥 Dzień 12 – Integracja testów z danymi
Stwórz fixtures/users.json

Użyj cy.fixture() do pobierania danych do testu

W testach: dodaj użytkownika z JSONa, sprawdź dane

🔥 Dzień 13 – Git + CI
Wrzuć projekt na GitHub

Dodaj plik .github/workflows/tests.yml – odpala npx cypress run na push

Przerób prosty GitHub Actions flow

🔥 Dzień 14 – Dokumentacja + README
W README napisz:

Jak uruchomić testy

Co testujesz

Jak wygląda struktura katalogów

Dodaj 3–4 screeny wyników testów

🔥 Dzień 15 – Finał: Demo i Ewaluacja
Nagraj krótki screen lub GIF (np. z LICEcap), jak działają Twoje testy

Zrób checklistę:

 UI testy

 API testy

 SQL

 CI

 GitHub repo z README

🧨 DODATKOWE ZASADY:
Nie oglądaj pasywnie. Każdy dzień kończy się działającym kodem.

Kopiowanie = niezaliczone. Rozumiesz → piszesz sam.

Brak commitów = brak progresu. Codziennie coś ląduje na GitHubie.
