# ETL System - Automatyzacja agregacji danych z rynku pracy

* Data rozpoczęcia: 2025-03-01<br>
* Data ukończenia: 2025-06-30<br>
* Rola: **Lider zespołu** / Data Engineer<br>
* Firma: GOTOIT sp. z o.o.

## 🎯 Opis projektu

Kompleksowy system ETL (Extract, Transform, Load) do automatycznego pozyskiwania, przetwarzania i udostępniania danych ofertowych z rynku pracy. Projekt obejmował budowę skalowalnej infrastruktury chmurowej, która codziennie przetwarza duże wolumeny danych i udostępnia je przez dedykowane API.

### 🚀 Główne funkcjonalności

- **🔄 Automatyczne pobieranie danych** - Codzienne pozyskiwanie tysięcy ofert pracy z zewnętrznych źródeł
- **⚡ Asynchroniczne przetwarzanie** - Wykorzystanie Dramatiq i Redis dla wysokiej wydajności
- **📊 Standaryzacja i wzbogacanie** - Automatyczne czyszczenie i normalizacja danych
- **🔌 REST API** - Udostępnienie danych dla innych zespołów przez FastAPI
- **☁️ Infrastruktura chmurowa** - Wdrożenie na Digital Ocean z Docker
- **📈 Monitoring i optymalizacja** - System monitorowania wydajności i diagnostyki

## 🛠️ Moje kluczowe zadania jako lidera zespołu

### 1. **Architektura systemu ETL**
- Projektowanie i implementacja modułu pobierania danych z asynchronicznym kolejkowaniem
- Wdrożenie systemu Dramatiq + Redis dla wysokiej wydajności i odporności na przeciążenia
- Optymalizacja przepływu danych i zarządzanie pamięcią RAM

### 2. **DevOps i wdrożenia**
- Konfiguracja i utrzymanie infrastruktury na Digital Ocean
- Automatyzacja procesów CI/CD z wielokrotnymi wdrożeniami
- Testowanie lokalne z MinIO (emulacja S3) i Docker

### 3. **Zarządzanie zespołem**
- Analiza i przegląd pull requestów zespołu
- Wsparcie techniczne w rozwoju kodu
- Koordynacja prac nad różnymi modułami systemu

### 4. **Optymalizacja wydajności**
- Diagnoza i rozwiązanie problemu nadmiernego zużycia pamięci RAM przez workerów Dramatiq
- Implementacja systemu monitoringu wydajności
- Optymalizacja zapytań do bazy danych

## 🎯 Zakres techniczny projektu

### **Backend & API**
- **Python** - Główny język programowania
- **FastAPI** - REST API dla udostępniania danych
- **Dramatiq** - Asynchroniczne kolejkowanie zadań
- **Redis** - Cache i kolejkowanie

### **Baza danych & Storage**
- **PostgreSQL** - Główna baza danych
- **MinIO** - Emulacja S3 dla testów lokalnych

### **Infrastruktura & DevOps**
- **Digital Ocean** - Platforma chmurowa
- **Docker** - Konteneryzacja aplikacji
- **Git** - Kontrola wersji

## 📊 Efekty projektu

### **Ilościowe rezultaty**
- ✅ **Codzienne automatyczne przetwarzanie** tysięcy ofert pracy
- ✅ **Skalowalny system** obsługujący duże wolumeny danych
- ✅ **Wysoka dostępność** API dla innych zespołów
- ✅ **Znaczące przyspieszenie** analizy rynku pracy

### **Jakościowe korzyści**
- 🎯 **Standaryzacja danych** - Spójny format dla wszystkich ofert
- 🔄 **Automatyzacja procesów** - Eliminacja ręcznej pracy
- 📈 **Wysoka jakość danych** - Wzbogacone i zwalidowane informacje
- 🚀 **Szybki dostęp** - API dla innych zespołów

## 🎓 Rozwój umiejętności

Projekt pozwolił mi rozwinąć kluczowe kompetencje:

- **🏗️ Architektura systemów** - Projektowanie skalowalnych rozwiązań ETL
- **☁️ Cloud Computing** - Wdrażanie i utrzymanie aplikacji w chmurze
- **⚡ Performance Engineering** - Optymalizacja wydajności i diagnostyka
- **👥 Leadership** - Zarządzanie zespołem i koordynacja prac
- **🔧 DevOps** - Automatyzacja wdrożeń i monitoring

## 🏆 Wnioski

Jako lider zespołu w tym projekcie udowodniłem, że potrafię:
- **Zarządzać złożonymi projektami** technicznymi
- **Optymalizować wydajność** systemów produkcyjnych
- **Wdrażać nowoczesne rozwiązania** chmurowe
- **Prowadzić zespół** do realizacji ambitnych celów

Ten projekt stanowi doskonały przykład mojej zdolności do łączenia umiejętności technicznych z kompetencjami przywódczymi w środowisku korporacyjnym.

---

**Technologie:** Python, Dramatiq, Redis, PostgreSQL, Digital Ocean, Docker, FastAPI, Git, MinIO 