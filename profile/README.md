<p align="left"><img src="https://raw.githubusercontent.com/Energeks/.github/main/profile/energeks_logo.png" alt="Energeks" width="140"></p>

# Energeks

Transformatory SN/nN i kompletne stacje transformatorowe. Tutaj publikujemy otwarty format kodu i danych stacji oraz narzędzia, z których mogą korzystać projektanci, wykonawcy, zamawiający i asystenci AI.

## Kreator stacji Energeks

Bezpłatny kreator stacji SN/nN, bez rejestracji: [energeks.shop/stacje-transformatorowe/kreator-stacji.html](https://energeks.shop/stacje-transformatorowe/kreator-stacji.html?utm_source=github&utm_medium=referral&utm_campaign=standard_ai_2026q4&utm_content=readme_org)

- ponad 15 mln konfiguracji, moce od 63 do 2500 kVA oraz 2 x 400 do 2 x 1000 kVA, sieci 15 i 20 kV,
- standardy 5 operatorów sieci: PGE Dystrybucja, TAURON Dystrybucja, Enea Operator, Energa-Operator, Stoen Operator,
- rozdzielnice SN wyłącznie bez F-gazów (rozporządzenie UE 2024/573),
- do pobrania: projekt techniczny do adaptacji przez projektanta i karta katalogowa w PDF, opis przedmiotu zamówienia do SWZ, rysunki, schemat jednokreskowy, zestawienie, dane JSON.

Każda konfiguracja ma kod, np. `ENG-B630-15S-LPT-06-K`. Link z kodem po znaku `#` otwiera dokładnie tę stację:
[kreator-stacji.html#ENG-B630-15S-LPT-06-K](https://energeks.shop/stacje-transformatorowe/kreator-stacji.html?utm_source=github&utm_medium=referral&utm_campaign=standard_ai_2026q4&utm_content=readme_org#ENG-B630-15S-LPT-06-K)

## API i serwer MCP dla asystentów AI

Publiczne API kreatora, bez klucza (limit 60 zapytań na minutę z jednego adresu IP): https://energeks-stacje-api.energeks.workers.dev

- serwer MCP (Streamable HTTP): `https://energeks-stacje-api.energeks.workers.dev/mcp`, narzędzia: lista opcji, konfiguracja stacji, stacja z kodu, opis przedmiotu zamówienia, link do kreatora,
- opis dla modeli językowych: [llms.txt](https://energeks-stacje-api.energeks.workers.dev/llms.txt), opis API: [openapi.yaml](https://energeks-stacje-api.energeks.workers.dev/openapi.yaml).

## Repozytoria

| Repozytorium | Co zawiera | Licencja |
|---|---|---|
| [energeks-stacja](https://github.com/energeks/energeks-stacja) | specyfikacja kodu i danych stacji `energeks.stacja`, schematy JSON, przykłady, testy, opis API i serwera MCP | CC BY 4.0 |

Nazwa i logo Energeks oraz silnik konfiguratora nie są objęte licencją.

## Kontakt

info@energeks.com, +48 664 951 947, ul. Święty Marcin 29/8, 61-806 Poznań. Błędy i propozycje do formatu: Issues w repozytorium [energeks-stacja](https://github.com/energeks/energeks-stacja/issues).

---

### English

Energeks supplies MV/LV distribution transformers and complete transformer substations. The free [Energeks substation configurator](https://energeks.shop/stacje-transformatorowe/kreator-stacji.html?utm_source=github&utm_medium=referral&utm_campaign=standard_ai_2026q4&utm_content=readme_org_en) (in Polish, for the Polish grid) covers more than 15 million configurations, 63 to 2500 kVA, 15 and 20 kV and the standards of 5 Polish distribution system operators. The station code and data format `energeks.stacja` is open under CC BY 4.0 in [energeks-stacja](https://github.com/energeks/energeks-stacja). Public API and MCP server for AI assistants: https://energeks-stacje-api.energeks.workers.dev (MCP endpoint `/mcp`, [llms.txt](https://energeks-stacje-api.energeks.workers.dev/llms.txt)). Contact: info@energeks.com.
