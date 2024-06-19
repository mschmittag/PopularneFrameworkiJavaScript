# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

# Popularne Frameworki JavaScript

React to popularny framework JavaScript, używany do budowania interfejsów użytkownika, szczególnie dla aplikacji jednostronicowych (SPA). Został stworzony przez Facebooka i jest obecnie zarządzany przez Facebook oraz społeczność open source.

## Podstawowe cechy Reacta

1. Komponenty:

- Modularność: React opiera się na komponentach, co oznacza, że aplikacje są budowane z wielu izolowanych i ponownie używalnych bloków. Komponenty te mogą mieć własny stan i logikę.
- Klasy vs Funkcje: Wcześniejsze wersje React używały klas do tworzenia komponentów, natomiast nowsze wersje promują funkcje z hookami, które umożliwiają zarządzanie stanem i cyklem życia komponentu.

2. JSX

JSX: Jest to składnia przypominająca HTML, używana do opisywania struktury komponentu React. Jest ona transpilowana do JavaScriptu, co pozwala na wygodne użycie wyrażeń JavaScript wewnątrz tej składni.

3. Stan i właściwości

- Stan (State): Stan to dane, które mogą zmieniać się w czasie. W React każdy komponent może mieć swój własny stan, który można aktualizować w odpowiedzi na działania użytkownika, odpowiedzi sieciowe itp.
- Właściwości (Props): Są to dane przekazywane do komponentów, zazwyczaj służą do konfiguracji komponentów i przekazywania danych między nimi. Są one niemutowalne, co oznacza, że komponent otrzymujący właściwości nie może ich zmieniać.

4. Cykl życia komponentu

Cykl życia: React zarządza cyklem życia każdego komponentu, od momentu jego montowania, przez aktualizacje, aż do demontażu. Hooki funkcjonalne, takie jak useEffect, pozwalają na efektywne zarządzanie tymi etapami.

5. Hooki

Hooki: Wprowadzone w React 16.8, hooki pozwalają na używanie stanu i innych funkcjonalności Reacta bez pisania klas. Najbardziej znanymi są useState i useEffect.

6. Kontekst

API Kontekstu: Pozwala na przekazywanie danych bezpośrednio między komponentami, pomijając średnie poziomy hierarchii. Jest to przydatne w przypadku danych aplikacyjnych, takich jak preferencje użytkownika czy temat aplikacji.

7. Renderyzacja i Virtual DOM

- Virtual DOM: React utrzymuje lekką kopię struktury DOM w pamięci, znaną jako Virtual DOM. Kiedy stan lub właściwości komponentu ulegają zmianie, React przelicza Virtual DOM, a następnie efektywnie aktualizuje tylko te części prawdziwego DOM, które się zmieniły.
- Renderyzacja: Proces przekształcania komponentów React (i ich JSX) w HTML, który można wyświetlić w przeglądarce.

8. Optymalizacja i narzędzia

- Narzędzia deweloperskie: React posiada zestaw narzędzi deweloperskich do debugowania i analizy aplikacji React.
- Optymalizacja wydajności: React oferuje różne techniki optymalizacyjne, takie jak lazy loading komponentów, memoizacja, i używanie czystych komponentów, aby zmniejszyć ilość niepotrzebnych renderowań.

## Narzędzia użyte w projekcie

1. MUI (Material-UI) to jedna z najpopularniejszych bibliotek komponentów interfejsu użytkownika dla React.

Główne cechy MUI:
- Komponenty gotowe do użycia: MUI oferuje szeroką gamę komponentów UI, takich jak przyciski, karty, dialogi, listy, ikony, które są już gotowe do implementacji w projektach.
- Zgodność z Material Design: Komponenty MUI są zgodne z zasadami Material Design od Google, co zapewnia atrakcyjność wizualną oraz spójność interfejsu użytkownika.
- Personalizacja i dostosowywanie: MUI pozwala na łatwe dostosowanie komponentów za pomocą tematów i niestandardowych stylów, umożliwiając tworzenie unikalnych wyglądów i zachowań.
- Responsywność: Komponenty są zaprojektowane z myślą o responsywności, dzięki czemu aplikacje mogą działać płynnie na różnych urządzeniach i rozmiarach ekranów.
- Oparte na CSS-in-JS: MUI korzysta z systemów takich jak Emotion lub styled-components do zarządzania stylami, co pozwala na bardziej dynamiczną stylizację w kontekście składni JavaScript.
- Wydajność: MUI jest zoptymalizowane pod kątem wydajności, z funkcjami takimi jak leniwe ładowanie komponentów, co pomaga utrzymać aplikacje działające szybko i efektywnie.
- Bogata dokumentacja i wsparcie społeczności: MUI posiada obszerną dokumentację oraz aktywną społeczność użytkowników i deweloperów, co ułatwia naukę i rozwiązywanie problemów.
- Elastyczność i integracja: Biblioteka łatwo integruje się z różnymi systemami zarządzania stanem, narzędziami do routingu oraz innymi bibliotekami React, co czyni ją elastyczną opcją dla wielu projektów.
- Narzędzia dla deweloperów: MUI oferuje narzędzia, które pomagają w projektowaniu, prototypowaniu i personalizacji interfejsów, co przyspiesza proces deweloperski.
- Międzynarodowe wsparcie (i18n): MUI wspiera internacjonalizację, co pozwala na łatwą adaptację aplikacji dla różnych języków i regionów.

2. React (Framework frontendowy)

Architektura i podejście:

- Komponentowy model: React opiera się na modelu komponentowym, gdzie interfejs użytkownika jest zbudowany z niezależnych, wielokrotnie używalnych części, które zarządzają swoim stanem. To podejście sprzyja modularności i łatwości utrzymania kodu.
- One-Way Data Binding: React stosuje jednokierunkowe wiązanie danych, co oznacza, że dane są przekazywane z góry na dół (od rodzica do dziecka) przez komponenty. Umożliwia to łatwiejsze śledzenie zmian w stanie aplikacji i przewidywanie jej zachowania.

Szablony HTML (JSX):

- JSX: React używa JSX dla szablonów, co umożliwia pisania HTML wewnątrz JavaScript. JSX przekształca elementy interfejsu użytkownika zdefiniowane w JavaScript w HTML, który jest renderowany w przeglądarce.

Zarządzanie stanem:

- useState, useContext, useReducer: React oferuje hooki, takie jak useState dla zarządzania stanem lokalnym komponentu, useContext dla stanu globalnego i useReducer dla bardziej złożonych stanów, które wymagają akcji podobnych do reduktorów w Reduxie.

3. Node.js - Środowisko serwerowe

Użycie w projekcie:

- Runtime dla JavaScript: Node.js umożliwia uruchamianie JavaScript po stronie serwera, co jest kluczowe dla obsługi API, operacji na bazach danych, i zarządzania logiką biznesową serwera.

Konektory do baz danych:

- npm packages: Jeśli projekt korzysta z bazy danych, Node.js może łączyć się z nią za pomocą odpowiednich pakietów npm, np. mongoose dla MongoDB, które oferują zarządzanie schematami, walidację danych i zapytania do bazy.

4. Express.js - Web Framework dla Node.js

Routing i middleware:

- Routing: Express.js pozwala na definiowanie tras (endpoints), które serwer może obsłużyć, przyjmując żądania HTTP i odpowiadając na nie, np. /api/recipes dla żądań do API przepisów.
- Middleware: Funkcje middleware w Express.js mogą przetwarzać żądania, odpowiedzi oraz przeprowadzać operacje takie jak logowanie, autentykacja, parsowanie danych wejściowych itp.

5. Integracja z REST API

Zapytania do zewnętrznego API:

- Axios/Fetch: Możesz używać biblioteki takiej jak Axios lub natywnego Fetch API do wysyłania żądań do zewnętrznych serwisów API, aby pobrać dane o przepisach. Te biblioteki obsługują asynchroniczne żądania HTTP, co pozwala na efektywne zarządzanie odpowiedziami i błędami.

Obsługa i zarządzanie danymi:

- Asynchroniczność: Użycie async/await w JavaScript ułatwia zarządzanie operacjami asynchronicznymi, takimi jak zapytania do API czy bazy danych, czyniąc kod bardziej czytelnym i łatwiejszym w debugowaniu.





















