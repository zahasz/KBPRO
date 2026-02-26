
# KBPRO — Ekosystem Cyfrowy dla Branży Budowlanej

![KBPRO Status](https://img.shields.io/badge/Status-Active%20Development-success)
![Version](https://img.shields.io/badge/Version-2.1.0-blue)
![Tech Stack](https://img.shields.io/badge/Stack-TypeScript%20%7C%20Node.js%20%7C%20Next.js%20%7C%20Microservices-3178C6)

**KBPRO** to zaawansowana platforma SaaS typu ERP/CRM dedykowana branży budowlanej, zintegrowana z niezależnym silnikiem E-Commerce (**E-Shop**). Projekt łączy narzędzia do zarządzania firmą wykonawczą z rynkiem materiałów budowlanych w czasie rzeczywistym.

---

## 🎯 Misja Projektu

Naszym celem jest cyfryzacja małych i średnich przedsiębiorstw budowlanych poprzez dostarczenie im "Systemu Operacyjnego" do prowadzenia biznesu. KBPRO automatyzuje procesy — od pozyskania klienta, przez kosztorysowanie oparte o **żywe ceny rynkowe**, aż po realizację zamówień i fakturowanie.

## 🏗 Architektura Systemu

Projekt oparty jest na nowoczesnej architekturze **Mikroserwisów**, zapewniającej skalowalność, niezawodność i łatwość rozwoju. System podzielony jest na dwa autonomiczne, współpracujące ze sobą filary:

### 1. KBPRO (Contractor Operating System)
"Mózg operacyjny" dla wykonawcy.
*   **Core Stack:** Node.js, Express, PostgreSQL, Redis.
*   **Moduły Główne:**
    *   **Contractor Service:** Zarządzanie profilami, wizytówkami i ekipami.
    *   **Estimate Service & Calculator:** Zaawansowane kosztorysowanie i Kalkulator Budowy Domu zasilane cenami live.
    *   **Contractor Finance:** Pełna księgowość operacyjna (Faktury, Subskrypcje, Magazyn Wewnętrzny).
    *   **Catalog Service:** Marketplace ogłoszeń i produktów B2B.

### 2. E-SHOP (Commerce Engine)
Niezależna platforma handlowa (Retail/B2B).
*   **Rola:** Dostawca danych cenowych i realizator logistyki.
*   **Integracja:** Działa jako odseparowany pakiet, komunikujący się z KBPRO poprzez dedykowany **Integration Adapter**.

---

## 🚀 Kluczowe Funkcjonalności

### Dla Wykonawcy (B2B)
-   **Inteligentne Kosztorysy:** Tworzenie ofert w oparciu o aktualne ceny z E-Shopu (Live Pricing API).
-   **Kalkulator Budowy Domu:** Precyzyjna wycena inwestycji dla klienta końcowego w kilka minut.
-   **Biuro w Kieszeni:** Wystawianie faktur, zarządzanie magazynem narzędzi, kalendarz zleceń.
-   **Wizytówka Online:** Profesjonalny profil wykonawcy z portfolio i opiniami.

### Dla Inwestora (B2C)
-   **Znajdź Fachowca:** Wyszukiwarka zweryfikowanych ekip budowlanych.
-   **Marketplace:** Kupno materiałów budowlanych (nowych i z nadwyżek magazynowych).

---

## 🛠 Status Wdrożenia (Q1 2026)

Projekt znajduje się w fazie zaawansowanego rozwoju (Post-MVP Optimization).

| Obszar | Status | Opis |
| :--- | :--- | :--- |
| **Architektura** | ✅ Gotowe | Zakończono konsolidację domen (Finance, Contractor, Catalog). |
| **Frontend** | ✅ Gotowe | Aplikacja Next.js w pełni zintegrowana z nowym API. |
| **Bazy Danych** | 🔄 W toku | Finalizacja standardyzacji i poolingu połączeń. |
| **Integracja E-Shop** | 🔄 W toku | Wdrożono Adapter i Price Service. Trwają testy synchronizacji stanów. |
| **Mobile App** | 📅 Planowane | Rozpoczęcie prac planowane na Q3 2026. |

---

## 🤝 Współpraca i Sponsoring

Poszukujemy partnerów strategicznych i inwestorów, którzy chcą mieć udział w cyfrowej transformacji sektora budowlanego.

**Dlaczego warto wesprzeć KBPRO?**
1.  **Skala Rynku:** Budownictwo to jeden z najmniej scyfryzowanych sektorów gospodarki.
2.  **Unikalna Technologia:** Jako jedyni oferujemy kosztorysowanie oparte o rzeczywiste stany magazynowe i ceny dystrybutorów w czasie rzeczywistym.
3.  **Gotowy Produkt:** To nie jest makieta — to działający kod, gotowy do skalowania.

### Potrzeby Projektowe
*   Infrastruktura chmurowa (AWS/Azure) dla środowisk produkcyjnych.
*   Wsparcie w marketingu i dotarciu do bazy wykonawców.
*   Finansowanie zespołu deweloperskiego (rozszerzenie funkcjonalności AI).

---

## 📞 Kontakt

Jeśli jesteś zainteresowany współpracą, inwestycją lub chcesz przetestować wersję demo:

**Zespół KBPRO**
*   Email: kbpro@kbpro.pl
*   GitHub: [Private Repository]

---
*Dokumentacja techniczna dostępna dla autoryzowanych partnerów w katalogu `/docs`.*
