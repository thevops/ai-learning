---
title: "The 8 Levels of Agentic Engineering"
source: "https://www.bassimeledath.com/blog/levels-of-agentic-engineering"
author: "Bassim Eledath"
published: 2026-03-11
content_type: blog-summary
language: pl
tags:
  - ai
  - programming
  - ai-agents
  - agentic-engineering
---

# Osiem poziomów inżynierii agentowej

Bassim Eledath opisuje rozwój pracy z AI przy tworzeniu oprogramowania jako osiem kolejnych poziomów.[1] To praktyczna, oparta na obserwacjach autora mapa dojrzałości, a nie formalny standard.[1] Główna teza: sama poprawa modeli nie wystarczy. Duże znaczenie ma sposób przygotowania kontekstu, narzędzi, kontroli jakości i współpracy w zespole.[1]

## Poziomy 1–4: od podpowiedzi do uczenia się na doświadczeniu

1. **Uzupełnianie kodu**: AI podpowiada fragmenty kodu, a programista prowadzi pracę.[1]
2. **IDE z agentem**: asystent otrzymuje kontekst repozytorium i może wprowadzać zmiany w wielu plikach.[1] Planowanie z człowiekiem pomaga utrzymać kontrolę.[1]
3. **Inżynieria kontekstu**: zespół dobiera instrukcje, historię rozmowy, opisy narzędzi i materiały tak, aby agent otrzymał właściwe informacje bez zbędnego szumu.[1]
4. **Inżynieria kumulacyjna**: po każdym zadaniu zespół ocenia wynik i zapisuje wnioski.[1] Reguły, dokumentacja i sprawdzone wzorce poprawiają kolejne sesje.[1] Nie należy jednak zamieniać pliku z instrukcjami w zbiór nadmiernie szczegółowych zakazów.[1]

## Poziomy 5–6: narzędzia i automatyczna pętla informacji zwrotnej

5. **MCP i umiejętności**: agent zyskuje dostęp do usług, danych, CI i wyspecjalizowanych procedur.[1] Wspólne umiejętności mogą standaryzować na przykład przegląd pull requestów.[1] Autor zwraca uwagę, że CLI bywa oszczędniejsze pod względem kontekstu niż MCP, ponieważ agent pobiera tylko wynik potrzebnego polecenia.[1]
6. **Inżynieria środowiska agenta**: zespół tworzy środowisko, w którym agent może sam uruchamiać testy, analizować logi, sprawdzać działanie interfejsu i poprawiać błędy.[1] Testy, typy, lintery i zabezpieczenia stanowią automatyczną informację zwrotną.[1] Im większa autonomia, tym ważniejsze są ograniczenia dostępu oraz oddzielenie agenta od sekretów.[1]

## Poziomy 7–8: praca w tle i zespoły agentów

7. **Agenci działający w tle**: agent sam bada repozytorium, planuje i wykonuje zadanie bez ciągłego nadzoru.[1]
   Orkiestrator może rozdzielać pracę między kilku agentów.[1]
   Autor zaleca dopasować różne modele do różnych ról oraz oddzielić implementację od niezależnego przeglądu.[1]
   Agenci mogą też reagować na zdarzenia CI, na przykład przygotować aktualizację dokumentacji lub poprawkę bezpieczeństwa.[1]
8. **Autonomiczne zespoły agentów**: agenci dzielą się zadaniami i ustaleniami bez centralnego orkiestratora.[1]
   To wciąż obszar eksperymentalny.[1]
   Brak hierarchii może powodować zastój, a słabe testy prowadzą do regresji.[1]
   Autor uważa, że dla większości codziennych zadań poziom 7 daje obecnie większą wartość.[1]

## Wniosek

Kolejne poziomy opierają się na poprzednich.[1] Automatyzacja nie naprawi niejasnych wymagań, słabego kontekstu ani braku testów. Może za to zwiększyć skalę tych problemów.[1] Dlatego warto najpierw poprawić instrukcje, dokumentację, narzędzia i pętle weryfikacji, a dopiero potem zwiększać autonomię agentów.[1]

Autor spekuluje, że następny etap może odejść od interakcji tekstowej, na przykład w stronę rozmowy głosowej z agentem.[1] Nie zakłada jednak, że tworzenie oprogramowania stanie się procesem jednorazowym.[1] Nadal będzie iteracyjne, choć szybsze i z użyciem szerszych form interakcji.[1]

## Sources

[1] Bassim Eledath, [The 8 Levels of Agentic Engineering](https://www.bassimeledath.com/blog/levels-of-agentic-engineering).
