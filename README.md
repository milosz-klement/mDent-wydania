# mDent – wydania

To repozytorium zawiera **tylko pliki aktualizacji** programu mDent. Nie ma w nim kodu źródłowego.

Program mDent pobiera stąd aktualizacje automatycznie. Nie trzeba niczego pobierać ręcznie.

## Wydania

- **stabilna**: wersja dla wszystkich gabinetów.
- **beta**: wersja testowa dla wybranych gabinetów.

Każde wydanie zawiera:

- `stabilna.xml` / `beta.xml`: informacja o wersji,
- `stabilna.xml.sig` / `beta.xml.sig`: podpis cyfrowy tej informacji,
- `mDent_<wersja>.zip`: paczka z programem.

mDent instaluje paczkę tylko wtedy, gdy podpis jest prawidłowy, a skrót SHA-256 paczki zgadza się z podpisaną informacją.
