# Plac BDF — Symulator Manewrów Ciężarówką z Nadwoziem Wymiennym

Realistyczny symulator precyzyjnych manewrów samochodem ciężarowym z nadwoziem wymiennym (BDF C745) – w wersji **Solo** oraz z **przyczepą centralnoosiową na sztywnym dyszlu (tandem)**.

Aplikacja jest pełnoprawną aplikacją **PWA (Progressive Web App)** gotową do instalacji na telefonach (np. iPhone, Android) oraz komputerach i uruchomienia w trybie pełnoekranowym bez połączenia z internetem.

---

## 🎮 Sterowanie

### ⌨️ Klawiatura (PC / Mac)
| Akcja | Klawisze |
|---|---|
| **Przód (Bieg D)** | `W` lub `Strzałka w górę` |
| **Tył / Cofanie (Bieg R)** | `S` lub `Strzałka w dół` |
| **Skręt kół** | `A` / `D` lub `Strzałka w lewo` / `w prawo` |
| **Wyprostuj koła** | `C` |
| **Czynność (podnoszenie zawieszenia, nogi, rampa)** | `Spacja`, `E` lub `Enter` |
| **Powrót do menu** | `Escape` |

### 📱 Ekran dotykowy (iPhone / Smartfony)
* **Kierownica:** suwak na dole ekranu – koła pozostają w pozycji, w której puścisz suwak. Przycisk **Prosto** natychmiast centruje koła.
* **Pedały:** przytrzymaj **Przód** lub **Tył**, puść aby wyhamować.
* **Przycisk akcji (środek):** aktywuje się w zielonej strefie (podnoszenie zawieszenia, opuszczanie/składanie nóg kontenera, rozładunek przy rampie, wpinanie/odpinanie przyczepy).

---

## 📱 Instalacja jako aplikacja PWA na iPhone (np. iPhone 17 Pro Max)

1. Otwórz stronę gry w przeglądarce **Safari**.
2. Kliknij ikonę **Udostępnij** (kwadrat ze strzałką w górę na dole ekranu).
3. Wybierz opcję **„Do ekranu początkowego”** (Add to Home Screen).
4. Kliknij **Dodaj**. Na pulpicie pojawi się dedykowana ikona **Plac BDF**.
5. Gra uruchamia się bez pasków przeglądarki w pełnym trybie pełnoekranowym z obsługą Safe Area (Dynamic Island i dolny pasek) oraz działa w 100% offline!

---

## 🚀 Jak wrzucić projekt na GitHub i włączyć GitHub Pages

Projekt jest już przygotowany z plikiem wejściowym `index.html`.

### Krok 1: Wypchnięcie plików do repozytorium GitHub
Otwórz terminal w katalogu projektu lub użyj GitHub Desktop:

```bash
git add .
git commit -m "Wersja PWA, ikony i naprawa sterowania"
git remote add origin https://github.com/TWOJ_LOGIN/TWOJE_REPOZYTORIUM.git
git branch -M main
git push -u origin main
```

*(Jeśli masz już utworzone repozytorium, podmień link na swój).*

### Krok 2: Włączenie GitHub Pages
1. Przejdź do swojego repozytorium na **GitHub.com**.
2. Kliknij zakładkę **Settings** (Ustawienia) ➔ z lewego menu wybierz **Pages**.
3. W sekcji **Build and deployment** ➔ **Source** wybierz `Deploy from a branch`.
4. W polu **Branch** wybierz `main` oraz katalog `/ (root)`, a następnie kliknij **Save**.
5. Po kilkudziesięciu sekundach Twoja gra będzie dostępna publicznie pod adresem:
   `https://TWOJ_LOGIN.github.io/NAZWA_REPOZYTORIUM/`

---

## 📁 Zawartość projektu

* `index.html` / `plac-bdf.html` – Główna gra i logika symulatora
* `manifest.webmanifest` – Konfiguracja PWA dla smartfonów i desktopu
* `sw.js` – Service Worker umożliwiający grę offline i szybkie ładowanie
* `icons/` – Dedykowane ikony PWA (SVG, 192x192, 512x512, maskable, Apple Touch Icon)
* `apple-touch-icon.png` – Ikona wysokiej rozdzielczości dla urządzeń Apple (iOS)
* `favicon.png` – Ikona karty przeglądarki
* `LICENSE` – Licencja prawna i zastrzeżenie praw autorskich

---

## ⚖️ Prawa autorskie i licencja (Copyright & Ownership)

**© 2026 Maciej. Wszelkie prawa zastrzeżone / All Rights Reserved.**

Niniejsza aplikacja, jej koncepcja, kod źródłowy, logika fizyki symulatora, interfejs oraz oprawa graficzna stanowią wyłączną własność intelektualną autora (**Maciej**).

* ⛔ **Zakaz kopiowania:** Zabrania się kopiowania, powielania, redystrybucji, modyfikowania, dekompilacji lub wykorzystywania całości lub jakiejkolwiek części kodu źródłowego i zasobów aplikacji bez uprzedniej pisemnej zgody autora.
* 🔒 **All Rights Reserved:** No part of this software may be copied, reproduced, distributed, or modified in any form without express written permission.

