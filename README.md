[![pagepro_logo](https://miro.medium.com/fit/c/96/96/0*cVHxjMcinW8ale32.png)](https://daftcode.pl/)

# React Developer - Rekrutacja

## Zadanie
Twoim zadaniem jest stworzenie aplikacji SPA do zarządzania użytkownikami oraz ich postami.

## Zalecany stack technologiczny:
* API: [API DOCS](https://jsonplaceholder.typicode.com/)
* Starter: [Create react app starter](https://github.com/facebook/create-react-app)
* State Managment: [Redux](https://github.com/reduxjs/react-redux)
* Routing: [React-router](https://github.com/ReactTraining/react-router)
* Middleware: [redux-saga](https://redux-saga.js.org)

## Widoki:
* Projekt graficzny:
   [tutaj](https://www.figma.com/file/4DiXIKzfq48wyDN2Z6YLGm/Frontend-Developer---Recruitment-Task?node-id=0%3A1)
* `Strona główna` 
    * Lista użytkowników. 
    * Dla każdego z użytkowników wyświetlamy dodatkowe informacje.
    * Po kliknięciu na użytkownika przechodzimy do strony `Panel użytkownika`
* `Panel użytkownika`
    * Strona na samej górze zawiera nazwę użytkownika
    * Następnie wyświetlamy listę postów danego użytkownika
    * Po kliknięciu na post przekierowujemy użytkownika do widoku z pojedyńczym postem.
    * Przycisk `+` otwiera modal z możliwością dodania nowego posta
    * Strzałka 'wstecz' cofa użytkownika do `Strony głównej`
* `Widok postu`
    * Na górze wyświetlamy nazwę użytkownika
    * Następnie wyświetlamy post body.
    * Strzałka `wstecz` cofa użytkownika do `Panelu użytkownika`
    * Przycisk show comments rozwija listę komentarzy.
    * Przycist `add comment` wyświetla modala z możliwością dodania komentarza

## Wymagania:
1. React &amp; Redux
2. Połączenia z API
3. Użycie react-router
4. Dodanie ladera podaczs ładowania danych
5. Walidacja formularzy
6. Wykorzystanie es6+

## Mile widziane:
1. Czysty kod (linters, prettier)
2. Redux-saga
3. Testy

## Na co będziemy zwracali szczególną uwagę:
1. Jak wygląda podział kodu na komponenty.
2. Jak wygląda redax store oraz komunikacja z nim.
3. Reużywalność komponentów
4. Sposób implementacji logiki biznesowej.
5. Optymalizacje w kodzie, dobre praktyki.
6. Sposób komunikacji z API.
7. Obsługa wyjątków.
