# flashcards

## Struktura folderów i plików wygląda następująco:

- `app` pliki związane z logiką aplikacji
    - `controllers` kontrolery obsługujące żądania HTTP i przetwarzające dane
        - HomeController.php
        - FlashcardController.php
    - `models` modele reprezentujące dane związane z fiszkami
        - FlashcardModel.php
    - `views` zawiera szablony HTML używane do generowania stron
        - `templates` znajdują się pliki, które mogą być używane w różnych widokach.
            - header.php
            - footer.php
        - `home.php` szablon strony głównej
        - `flashcard.php` szablon strony wyświetlającej fiszkę
    - `config.php` zawiera konfigurację aplikacji, np. połączenie z bazą danych
    - `routes.php` definiuje ścieżki URL dla różnych żądań HTTP

- `public` pliki publiczne
    - css
        - styles.scss
    - js
        - scripts.js
    - index.php

- `resources` zasoby pomocnicze
    - `database.sql` skrypt SQL do utworzenia tabel i struktury bazy danych
