# Peter von Marienburg

Strona artykułów przygotowana dla GitHub Pages. Jasne tło, szeryfowy tekst, przypisy, streszczenia i bibliografia. Bez reklam, śledzenia, zewnętrznych fontów i zależności JavaScript.

## Uruchomienie

1. Utwórz publiczne repozytorium `PetervonMarienburg.github.io` na koncie PetervonMarienburg i zaznacz Add README.
2. Umieść zawartość tej paczki w głównym katalogu repozytorium. Nie przesyłaj samego ZIP-a ani nadrzędnego folderu.
3. Otwórz Settings → Pages. W Source wybierz Deploy from a branch, następnie main oraz /(root) i Save.
4. Po poprawnym zakończeniu budowania strona będzie pod adresem https://petervonmarienburg.github.io/ .

Oficjalna instrukcja: https://docs.github.com/en/pages/quickstart

## Dodanie artykułu w przeglądarce

1. Otwórz repozytorium. Wybierz Add file → Create new file.
2. Jako nazwę podaj `_posts/2026-09-18-tytul-artykulu.md`, wpisując rzeczywistą datę i krótki tytuł bez spacji i polskich znaków.
3. Skopiuj zawartość SZABLON-ARTYKULU.md. Zastąp wszystkie przykładowe dane swoim tekstem i prawdziwymi źródłami.
4. Ustaw `published: true`, kiedy tekst jest gotowy, i zapisz przez Commit changes. Data artykułu nie powinna być przyszła.
5. Po automatycznej przebudowie tekst pojawi się na liście.

Przypis w tekście: `[^1]`. Na końcu: `[^1]: Opis źródła, s. 12.` Numerowanie i powrót do tekstu powstaną automatycznie.

Ilustracje: dodaj plik do assets, potem w tekście wpisz `![Opis ilustracji](/assets/nazwa-pliku.jpg)`. Pod ilustracją podaj źródło i wymagane informacje o prawach.

Aktualizacja: popraw plik artykułu i opcjonalnie dodaj w górnej części `updated: 2026-09-19`. Zachowaj pierwotną datę i nazwę pliku, aby link się nie zmienił.

Uwaga: pliki publicznego repozytorium są widoczne także wtedy, gdy `published: false`. Nie przechowuj w nim poufnych szkiców.

## Stan pierwszej wersji

Nie dodano ani nie opublikowano rzeczywistych artykułów. Podgląd dostarczony osobno zawiera tylko jawnie oznaczony przykład układu. Na właściwej stronie przed pierwszą publikacją wyświetla się komunikat o przygotowywanych tekstach.

Szablony są przeznaczone dla standardowego Jekyll/Kramdown w GitHub Pages. Pełna weryfikacja budowania nastąpi po umieszczeniu w repozytorium i uruchomieniu Pages.
