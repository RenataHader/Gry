# Gry (Charades + Memory)

Projekt w **Javie** zawierający dwie gry multiplayer: **Charades** oraz **Memory**.
Gry są uruchamiane w tzw. *pokojach* — można prowadzić kilka rozgrywek równocześnie.

Projekt jest zbudowany w **Gradle** (w repo znajduje się Gradle Wrapper).

---

## 🎮 Zawartość

### 1) Memory 
Gra dla **2 osób**.
Celem jest dopasowywanie kart w pary — gracze odkrywają karty i próbują odnaleźć wszystkie pasujące pary znajdujące się na planszy.
Wygrywa osoba, która jako pierwsza dopasuje / odnajdzie wszystkie pary.

**Najważniejsze elementy:**
- rozgrywka 2-osobowa
- dobieranie kart w pary aż do ukończenia wszystkich par
- logika wyłaniania zwycięzcy po zakończeniu gry

### 2) Charades
Gra dla **kilku osób**.
Każdy gracz dostaje **inne hasło** do narysowania. Następnie rysunki są prezentowane pozostałym graczom, a każdy próbuje odgadnąć hasła narysowane przez innych.

**Najważniejsze elementy:**
- wielu graczy w jednym pokoju
- każdy gracz rysuje swoje hasła (unikalne dla gracza)
- faza zgadywania rysunków innych uczestników

---

## 🏠 Pokoje

- Każda gra działa w osobnym *pokoju* (sesji).
- Możliwe jest uruchomienie kilku pokoi jednocześnie, np.:
  - równolegle 2 pokoje z Memory
  - albo jeden pokój z Charades i drugi z Memory w tym samym czasie

Dzięki temu kilka grup może grać niezależnie, bez mieszania się rozgrywek.

---

## 🛠 Technologie
- Java
- Gradle (wrapper w repo)
