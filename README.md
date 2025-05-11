# My shop

*English version below ↓*

## Opis

**My shop** to prosta aplikacja do przeglądania produktów, dodawania ich do koszyka oraz składania zamówienia.  Dane koszyka są zapisywane w `localStorage`, dzięki czemu nie znikają po odświeżeniu strony.

## Funkcje

- Przeglądanie dostępnych produktów
- Dodawanie produktów do koszyka
- Zmiana ilości sztuk (+ / -)
- Usuwanie produktów z koszyka
- Automatyczne obliczanie łącznej kwoty
- Podsumowanie zamówienia
- Finalizacja zamówienia – przejście do osobnej strony HTML
- Przechowywanie koszyka w `localStorage`

## Założenia

- Aplikacja działa całkowicie po stronie klienta (brak backendu)
- Produkty są zdefiniowane statycznie w pliku
- Koszyk zapisuje się w `localStorage` automatycznie przy każdej zmianie

## Jak uruchomić aplikację lokalnie

1. Zainstaluj zależności:
   Otwórz terminal i uruchom poniższą komendę w katalogu, gdzie znajduje się projekt:
   ```bash
   npm install
   ```
   Komenda ta zainstaluje wszystkie zależności zapisane w pliku package.json
2. Uruchom aplikację:
   Aby uruchomić aplikację lokalnie, użyj komendy:
   ```bash
   npm start
   ```
   Po tej komendzie aplikacja powinna zostać uruchomiona, a Ty będziesz mógł/a ją zobaczyć pod adresem: http://localhost:3000



----

## Description

**My shop** is a simple application for browsing products, adding them to a cart, and placing an order. Cart data is stored in `localStorage`, so it doesn't disappear when the page is refreshed.

## Features

- Browsing available products
- Adding products to the cart
- Adjusting product quantity (+ / -)
- Removing products from the cart
- Automatically calculating the total amount
- Order summary
-  Finalizing the order – redirecting to a separate HTML page
- Storing the cart in `localStorage`

## Assumptions

- The application runs entirely on the client side (no backend)
- Products are statically defined in a file
- The cart is automatically saved in `localStorage` after every change

## How to run the application locally

1. Install dependencies:
   Open a terminal and run the following command in the project directory:
   ```bash
   npm install
   ```
   This command will install all dependencies listed in the `package.json` file.

2. Start the application:
   To run the application locally, use the command:
   ```bash
   npm start
   ```
   After running this command, the app should start, and you'll be able to view it at: [http://localhost:3000](http://localhost:3000)
