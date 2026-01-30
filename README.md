# 🃏 Zadanie rekrutacyjne – Dobble

## 🎯 Cel
Zaimplementuj logikę gry typu **Dobble** w PHP (wersja 7.4 lub wyższa).

Każda karta:
- zawiera **8 symboli**
- każde dwie karty mają **dokładnie 1 wspólny symbol**
- w talii jest **57 kart**

---

## 📝 Zadanie
Twoim celem jest przygotowanie kodu, który sprawi, że **wszystkie testy w folderze `tests/` przejdą poprawnie**.

Nie dostarczamy gotowej implementacji — sam decydujesz:
- jakie klasy utworzysz
- gdzie umieścisz logikę
- jak zorganizujesz kod

---

## ✅ Wymagania
- PHP ≥ 7.4  
- PHPUnit  
- Możesz użyć frameworka, **tylko Laravel**  
- **Nie modyfikuj testów** (zachowaj logikę wzorcowych testów pseudokodowych)  
- Nie hardkoduj kart  

---

## ⚙️ Zakres implementacji
Musisz zaimplementować:
- generator kart (57 kart, 8 symboli)  
- sprawdzanie wspólnego symbolu  
- logikę gry (losowanie kart, brak powtórzeń)  
- prosty, użyteczny **interfejs użytkownika** w HTML (przyciski / tabelki). Widok nie musi być piękny, ale powinien być czytelny i możliwy do używania przez użytkownika.

---

## 🌟 Dodatkowe punkty
- czytelna architektura  
- możliwość łatwej rozbudowy  
- czytelny kod  
- zabezpieczenie aplikacji przed atakami (np. SQL Injection, XSS)  
- przygotowanie testów typu feature (poza standardowymi testami unitowymi)  
- testy można modyfikować pod własną strukturę projektu, **ale należy zachować ich pierwotną logikę i założenia biznesowe** (testy opisują zachowanie gry i nie powinny być upraszczane ani omijane)

---

## 💡 Wskazówka
Jeśli dwie karty mają **więcej lub mniej niż jeden wspólny symbol**, rozwiązanie jest niepoprawne.

Powodzenia 🚀
