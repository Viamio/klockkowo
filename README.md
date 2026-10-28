# Klockowo

Gra 3D w stylu Minecrafta. Na łące leży 5 kupek po 1000 klocków (drewno, kamień, cegła, szkło, dachówka), z których budujesz domy razem ze znajomymi. Do gry nie trzeba się logować.

## Jak wrzucić grę na GitHub Pages

1. Załóż konto na github.com, jeśli go nie masz.
2. Kliknij **+** → **New repository**, nazwij je np. `klockowo`, zaznacz **Public** i kliknij **Create repository**.
3. Kliknij **uploading an existing file**, przeciągnij plik `index.html` i kliknij **Commit changes**.
4. Wejdź w **Settings** → **Pages**. W polu *Branch* wybierz `main` i folder `/ (root)`, potem kliknij **Save**.
5. Po 1–2 minutach gra będzie pod adresem `https://TWOJA-NAZWA.github.io/klockowo/`.

## Jak grać ze znajomymi

1. Otwórz grę, wpisz nick i kliknij **Załóż serwer**. Twój komputer staje się serwerem.
2. W rogu ekranu pojawi się kod, np. `K7QM2`. Naciśnij **Esc**, żeby zobaczyć link z zaproszeniem i przycisk **Kopiuj link**.
3. Wyślij link znajomym. Po otwarciu kod wpisze się sam, wystarczy kliknąć **Dołącz**.

Serwer działa, dopóki masz grę otwartą. Świat zapisuje się w Twojej przeglądarce, więc po ponownym założeniu serwera budowle zostaną. Kod będzie wtedy nowy.

Połączenie idzie bezpośrednio między komputerami (WebRTC przez PeerJS). W rzadkich przypadkach może go zablokować sieć szkolna albo firmowa. Wtedy spróbujcie z innego internetu, np. z domowego Wi-Fi.

## Sterowanie

| Klawisz | Akcja |
|---|---|
| W A S D | chodzenie |
| Mysz | rozglądanie się |
| Spacja | skok |
| F | tryb lotu (Spacja w górę, Shift w dół) |
| Lewy przycisk | zabierz klocek (przytrzymaj, żeby zbierać szybko) |
| Prawy przycisk | postaw klocek |
| 1–5 / kółko | wybór klocka |
| Środkowy przycisk | weź typ celowanego klocka |
| Esc | pauza |
