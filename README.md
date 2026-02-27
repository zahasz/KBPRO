# KBPRO — Ekosystem Cyfrowy dla Branży Budowlanej

![KBPRO Status](https://img.shields.io/badge/Status-Active%20Development-success)
![Version](https://img.shields.io/badge/Version-2.2.0-blue)
![Tech Stack](https://img.shields.io/badge/Stack-TypeScript%20%7C%20Node.js%20%7C%20Next.js%20%7C%20Microservices-3178C6)

**KBPRO** to przełomowa platforma SaaS, która redefiniuje sposób prowadzenia biznesu w branży budowlanej. Łączymy zaawansowany system ERP/CRM dla wykonawców z potężnym silnikiem E-Commerce (**E-Shop**), tworząc spójne środowisko pracy oparte na danych w czasie rzeczywistym.

---

## 🚀 Odkryj Możliwości KBPRO + E-SHOP

Niezależnie od tego, czy jesteś profesjonalnym wykonawcą, czy inwestorem budującym swój wymarzony dom, KBPRO dostarcza narzędzi, które oszczędzą Twój czas i pieniądze. **Z nami budowanie staje się proste, przewidywalne i dochodowe.**

### 🛠 Dla Wykonawców: Twój Biznes pod Pełną Kontrolą
*   **Pozyskiwanie Klientów:** Aktywnie zdobywaj zlecenia na nowoczesnej **Giełdzie Zleceń Budowlanych**.
*   **Profesjonalne Ofertowanie:** Twórz oferty, które wygrywają, w oparciu o aktualne ceny rynkowe.
*   **Zaawansowane Kosztorysowanie:** Wykonuj proste kalkulacje oraz złożone kosztorysy z niezwykłą precyzją.
*   **Analityka Cen:** Analizuj ceny materiałów i robocizny innych wykonawców, aby zawsze być konkurencyjnym.
*   **Zarządzanie Zasobami:** Prowadź **własny magazyn** narzędzi i materiałów oraz zarządzaj spersonalizowanymi cennikami usług.

### 🏠 Dla Użytkowników i Inwestorów: Budowa bez Niespodzianek
*   **Transparentność Cen:** Uzyskaj dostęp do aktualnych cenników prac i materiałów budowlanych.
*   **Szybkie Zlecenia:** Składaj zlecenia budowlane bezpośrednio do zweryfikowanych fachowców.
*   **Kalkulator Budowy Domu:** Twój osobisty asystent z **roadmapą, kosztorysem, dziennikiem budowy i kalendarzem**.
*   **Baza Wykonawców:** Przeszukuj bazę cen i opinii o wykonawcach, aby wybrać najlepszą ofertę.
*   **Pełna Integracja:** Otrzymuj oferty materiałów bezpośrednio z E-Shopu, idealnie dopasowane do Twojego projektu.

---

## 🏗 Architektura Mikroserwisów

System KBPRO składa się z wyspecjalizowanych serwisów, które współpracują, aby zapewnić najwyższą wydajność i niezawodność:

| Serwis | Funkcja i Opis |
| :--- | :--- |
| **Auth Service** | Bezpieczne uwierzytelnianie, zarządzanie użytkownikami i uprawnieniami (JWT/RBAC). |
| **Contractor Service** | Serce platformy dla wykonawców: profile firm, profesjonalne wizytówki, zarządzanie ekipami. |
| **Pricing Service** | Silnik cenników, integracja z E-Shopem dla pobierania cen "live" i analiza stawek rynkowych. |
| **Offer Service** | Moduł generowania i zarządzania ofertami handlowymi dla klientów. |
| **Estimate Service** | Zaawansowany moduł kosztorysowania z obsługą pozycji katalogowych i narzutów. |
| **Invoice Service** | Automatyczne wystawianie faktur VAT, proforma oraz zarządzanie płatnościami. |
| **Finance Service** | Monitoring przepływów pieniężnych, analiza rentowności zleceń i koszty operacyjne. |
| **Contract Service** | Generator umów budowlanych i zarządzanie dokumentacją prawną projektów. |
| **Catalog Service** | Marketplace produktów B2B, ogłoszenia materiałowe i katalog rozwiązań systemowych. |
| **Warehouse Service** | Ewidencja stanów magazynowych, rezerwacje materiałów i historia wydań. |
| **Dashboard Service** | Centrum dowodzenia: agregacja statystyk, powiadomienia i widoki zarządcze. |
| **Building Calculator** | Interaktywny kalkulator budowy domu z generatorem harmonogramów (Roadmap). |
| **Subscription Service** | Zarządzanie planami abonamentowymi i dostępem do funkcji premium platformy. |
| **Suppliers Service** | Baza dostawców materiałów budowlanych z integracją logistyczną. |
| **Messaging Service** | System komunikacji wewnątrzplatformowej między wykonawcą a inwestorem. |
| **Integration Adapter** | Inteligentny most łączący KBPRO z systemem **E-Shop**, zapewniający synchronizację danych. |

---

## 🛒 E-SHOP: Potęga Zakupów Budowlanych

E-Shop to nie tylko sklep, to silnik handlowy zintegrowany z procesem budowlanym:
*   **Product Service:** Zarządzanie tysiącami produktów z pełną specyfikacją techniczną.
*   **Inventory Service:** Śledzenie stanów magazynowych w wielu lokalizacjach.
*   **Order Service:** Procesowanie zamówień od koszyka po dostawę na plac budowy.
*   **Analytics Service:** Raportowanie trendów cenowych i optymalizacja zakupów.

---

## 🛠 Status Wdrożenia (Q1 2026)

| Obszar | Status | Opis |
| :--- | :--- | :--- |
| **Backend Core** | ✅ Gotowe | Wszystkie mikroserwisy uruchomione i skomunikowane. |
| **E-Shop Integration** | ✅ Gotowe | Pełna synchronizacja cen i stanów magazynowych przez Adapter. |
| **Frontend Web** | ✅ Gotowe | Intuicyjny interfejs Next.js dla Wykonawcy i Inwestora. |
| **Giełda Zleceń** | 🔄 W toku | Optymalizacja algorytmów dopasowania wykonawców. |
| **AI Estimator** | 📅 Planowane | Automatyczne kosztorysowanie na podstawie rzutów PDF (Q4 2026). |

---

## 🤝 Wizja Inwestycyjna i Partnerstwo Strategiczne

KBPRO to projekt o ogromnym potencjale wzrostu w sektorze **ConTech**. Obecnie poszukujemy **Inwestora Strategicznego** (np. dużej sieci handlowej materiałów budowlanych), który przejmie kontrolę nad modułem **E-Shop** i w pełni zintegruje go z ekosystemem KBPRO.

### 💎 Korzyści dla Dużej Sieci Handlowej:
*   **Bezpośredni Kanał do Profesjonalistów:** Twoje produkty stają się domyślnym wyborem dla tysięcy wykonawców na etapie tworzenia kosztorysu.
*   **Live Pricing & Stock Integration:** Pełna synchronizacja Twoich stanów magazynowych i cen z procesem ofertowania wykonawcy – klient kupuje to, co faktycznie masz na półce.
*   **Predykcja Popytu (Big Data):** Dzięki wglądowi w harmonogramy budów i "dzienniki budowy" inwestorów, wiesz z wyprzedzeniem, jakie materiały będą potrzebne za 2-4 tygodnie.
*   **Automatyzacja Supply Chain:** Zamówienia z kosztorysów trafiają bezpośrednio do Twojego systemu logistycznego, eliminując błędy i skracając czas realizacji.
*   **Budowa Lojalności:** Dostarczenie wykonawcom narzędzia ERP, które "samo zamawia" materiały w Twojej sieci, drastycznie zwiększa tzw. *customer stickiness*.

**Kontakt dla Inwestorów:**
*   Email: [kbpro@kbpro.pl](mailto:kbpro@kbpro.pl)
*   Website: [www.kbpro.pl](http://www.kbpro.pl)

---
*Dokumentacja techniczna i instrukcje uruchomienia znajdują się w katalogu `/docs`.*
