# Agency — publiczna witryna

**Strona główna:** https://michalmatu.github.io/

To jedyne docelowe repozytorium zawierające **publiczny kod strony Agency**. Witryna przedstawia działające bety IleStoi.pl i PhotoMap.pl, wybrane projekty w rozwoju oraz podejście do tworzenia produktów. Od 2026-11-05 nacisk jest na ich sprawdzanie przez użytkowników, zamiast rozwoju kolejnych funkcji.

## Publikacja

- Plik: `index.html`
- Hosting: GitHub Pages
- Źródło: `main` / `(root)`
- Build: zbędny (statyczny HTML i CSS)
- Bez JavaScriptu, formularzy, zewnętrznych bibliotek i narzędzi analitycznych.
- Kontakt: bezpośredni link `mailto:` do podłączonego konta Gmail (adres publiczny w HTML); brak serwera i składowania treści wiadomości przez stronę.
- Osobne tematy e-mail pozwalają rozróżniać ogólny kontakt, opinie o IleStoi, opinie o PhotoMap oraz zapytania partnerskie. Nie stanowią analityki kliknięć ani dowodu wysłania wiadomości.
- Linki do obu produktów przekazują osobne `utm_campaign` i `utm_content` (bez identyfikatorów użytkownika). Samo dodanie UTM **nie uruchamia** analityki w produktach.

**Publikacja:** GitHub Pages działa z `main / (root)`. Właściciel 2026-11-05 potwierdził ręcznie działanie wcześniejszej wersji i podstawowego kontaktu. Nowy commit `b64dfa2` zmienił copy, CTA i UTM zgodnie z przejściem do walidacji rynku; statyczny HTML/CSS QA PASS przed zapisem. **Render nowego commitu, jego publiczny HTTP i pomiar UTM pozostają osobną bramką.**

## Podział repozytoriów

- `MichalMatu/agency` — **prywatne** centrum zarządzania projektami, kampaniami i dokumentacją strategiczną.
- `MichalMatu/MichalMatu.github.io` — **publiczne** repo z aktualną wersją strony.
- `MichalMatu/agency-website` — usunięte i potwierdzone jako niedostępne (404). Nie odtwarzać.

Nie kopiuj prywatnych planów, rejestrów ani danych klientów na stronę.

## Rozwój

Zmiany w witrynie wprowadzamy wyłącznie tutaj, a nie w prywatnym `agency/site/index.html`. Każda aktualizacja powinna mieć reaudyt treści, linków i responsywności. Podstawowy kontakt e-mail jest dostępny w witrynie. Przed uznaniem publikacji za zweryfikowaną potrzebny jest niezależny odczyt HTTP oraz test mobilny/klawiaturowy. W przyszłości można rozważyć analitykę z poszanowaniem prywatności; obecnie brak skryptów śledzących i pomiaru kliknięć. Plan pomiaru i materiałów jest w prywatnym `agency/campaigns/MARKET_VALIDATION_2026-11.md` — nie kopiować prywatnych plików do repo strony.
