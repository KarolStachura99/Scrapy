# 🕷️ OLX Scraper using Scrapy

Projekt do scrapowania ogłoszeń ze strony [OLX.pl](https://www.olx.pl) przy użyciu frameworka [Scrapy](https://scrapy.org/) w Pythonie.

## 🚀 Funkcje

- Pobieranie danych z OLX.pl (np. tytuł, cena, lokalizacja, link).
- Możliwość rozbudowy o kolejne pola.
- Modularna struktura Scrapy: `items`, `middlewares`, `settings`, `spiders`.

## 🧰 Technologie

- Python 3.x
- Scrapy

## 📦 Instalacja

1. Sklonuj repozytorium lub pobierz ZIP:
   git clone https://github.com/KarolStachura99/Scrapy.git
   cd Scrapy

2. Zainstaluj wymagane biblioteki:
   pip install scrapy

## ⚙️ Użycie

1. Uruchom spidera:
   scrapy runspider olx_spider.py -o wyniki.json

   Dane zostaną zapisane w pliku `wyniki.json`.

## 📁 Struktura projektu
```
Scrapy/
├── items.py         # Definicje pól danych
├── middlewares.py   # Middleware Scrapy (opcjonalnie)
├── olx_spider.py    # Główny spider scrapujący OLX
├── settings.py      # Konfiguracja Scrapy
└── README.md        # Ten plik
```
## 📝 Przykład danych

{
  "title": "Mieszkanie 2-pokojowe, 45m²",
  "price": "450 000 zł",
  "location": "Kraków, Małopolskie",
  "link": "https://www.olx.pl/d/oferta/mieszkanie-krakow-xyz"
}

## 🛡️ Uwaga prawna

Ten projekt jest przeznaczony wyłącznie do celów edukacyjnych. Upewnij się, że przestrzegasz regulaminu OLX przed rozpoczęciem scrapowania danych z ich strony.

## 👨‍💻 Autor

Karol Stachura – https://github.com/KarolStachura99
