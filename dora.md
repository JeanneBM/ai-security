# DORA — kompletne notatki

> **DORA** (*Digital Operational Resilience Act*) to rozporządzenie UE 2022/2554 dotyczące cyfrowej odporności operacyjnej sektora finansowego. Obowiązuje bezpośrednio we wszystkich państwach UE od **17 stycznia 2025 r.**

## 1. Po co powstała DORA?

Sektor finansowy działa w silnej zależności od systemów IT, danych, chmury i zewnętrznych dostawców. Awaria, atak ransomware, błąd wdrożenia albo niedostępność dostawcy może przerwać świadczenie usług finansowych i wywołać ryzyko systemowe.

**Cel DORA:** zapewnić, że podmiot finansowy potrafi **zapobiegać**, **wykrywać**, **reagować**, **odtwarzać działalność** i **uczyć się** po zakłóceniu związanym z ICT (*Information and Communication Technology*).

To nie jest wyłącznie regulacja cyberbezpieczeństwa. Obejmuje także ciągłość działania, zarządzanie dostawcami IT, testowanie odporności, raportowanie incydentów oraz odpowiedzialność zarządu.

## 2. Najważniejsze informacje

| Element | Treść |
|---|---|
| Akt prawny | Rozporządzenie Parlamentu Europejskiego i Rady (UE) 2022/2554 |
| Data przyjęcia | 14 grudnia 2022 r. |
| Stosowanie | od 17 stycznia 2025 r. |
| Charakter | rozporządzenie — stosuje się bezpośrednio, bez „wdrożenia” do prawa krajowego |
| Główna zasada | instytucja finansowa zachowuje pełną odpowiedzialność za zgodność także wtedy, gdy korzysta z usług zewnętrznego dostawcy ICT |
| Podejście | proporcjonalność: wymagania uwzględniają wielkość, profil ryzyka oraz skalę i złożoność działalności |

## 3. Kogo obejmuje?

DORA obejmuje przede wszystkim regulowane podmioty finansowe, m.in.:

- banki i instytucje kredytowe;
- firmy inwestycyjne, platformy obrotu, CCP, depozyty papierów wartościowych i repozytoria transakcji;
- instytucje płatnicze, instytucje pieniądza elektronicznego i dostawców usług dostępu do informacji o rachunku;
- zakłady ubezpieczeń i reasekuracji oraz część pośredników;
- fundusze, zarządzających funduszami i instytucje pracowniczych programów emerytalnych;
- agencje ratingowe, dostawców usług raportowania danych, dostawców crowdfundingu;
- dostawców usług w zakresie kryptoaktywów i emitentów tokenów powiązanych z aktywami;
- administratorów kluczowych wskaźników referencyjnych.

Zakres ma wyjątki i uproszczenia, np. dla niektórych mikroprzedsiębiorstw. Uproszczenie nie oznacza braku obowiązków — oznacza ramy dostosowane do ryzyka.

## 4. Pięć filarów DORA

### 4.1. Zarządzanie ryzykiem ICT

Podmiot ma ustanowić, utrzymywać i regularnie przeglądać ramy zarządzania ryzykiem ICT. Powinny one obejmować cały cykl życia ryzyka:

1. **Identyfikację** aktywów, procesów, zależności i zagrożeń.
2. **Ochronę i prewencję** — polityki bezpieczeństwa, kontrolę dostępu, zarządzanie podatnościami i zmianą, szkolenia oraz kopie zapasowe.
3. **Wykrywanie** anomalii, incydentów i pojedynczych punktów awarii.
4. **Reagowanie i odtworzenie** usług — plany reagowania, BCP/DRP, odtwarzanie danych i komunikacja kryzysowa.
5. **Uczenie się** — analiza przyczyn źródłowych, działania naprawcze i aktualizacja zabezpieczeń.

### 4.2. Zarządzanie i odpowiedzialność zarządu

Organ zarządzający (np. zarząd) nie może „oddać” odpowiedzialności za ryzyko ICT działowi IT lub dostawcy. Musi m.in.:

- zatwierdzić i nadzorować ramy zarządzania ryzykiem ICT;
- zapewnić odpowiednie zasoby, kompetencje i budżet;
- znać główne ryzyka, incydenty i zależności od dostawców;
- zapewnić szkolenia i aktualną wiedzę w zakresie ryzyka ICT;
- okresowo oceniać skuteczność ram oraz ich zgodność z DORA.

**Wniosek praktyczny:** cyber- i odporność cyfrowa stają się tematem ładu korporacyjnego, a nie wyłącznie operacji IT.

### 4.3. Obsługa, klasyfikacja i raportowanie incydentów ICT

Podmiot musi posiadać udokumentowany proces wykrywania, rejestrowania, obsługi i zgłaszania incydentów ICT.

- Rejestrowane są **wszystkie** incydenty ICT oraz istotne cyberzagrożenia.
- Incydenty klasyfikuje się według wspólnej metodologii, m.in. przez wpływ na funkcje krytyczne lub istotne, klientów, transakcje, dane, czas trwania i zasięg geograficzny.
- **Poważne incydenty ICT** podlegają zgłoszeniu do właściwego organu nadzoru w etapach: zgłoszenie wstępne, pośrednie i końcowe.
- Istotne cyberzagrożenia można zgłaszać dobrowolnie, gdy podmiot uzna to za przydatne dla nadzoru lub ekosystemu.
- Dla podmiotów świadczących usługi płatnicze istnieją także obowiązki dotyczące poważnych incydentów operacyjnych lub bezpieczeństwa związanych z płatnościami.

**Dobra praktyka:** przygotować runbook incydentowy z jasnymi rolami, progami eskalacji, wzorami zgłoszeń i kanałami komunikacji z nadzorem, klientami oraz dostawcami.

### 4.4. Testowanie cyfrowej odporności operacyjnej

Testy mają potwierdzać nie tylko, że kontrolki istnieją, ale że działają w praktyce. Program testów powinien być oparty na ryzyku, niezależny i obejmować usuwanie wykrytych słabości.

Przykładowe testy:

- skany i oceny podatności;
- testy konfiguracji, bezpieczeństwa sieci i kodu źródłowego (gdy wykonalne);
- testy scenariuszowe, wydajnościowe i end-to-end;
- testy odtwarzania kopii zapasowych, przełączenia awaryjnego i planów ciągłości działania;
- testy penetracyjne.

Systemy i aplikacje wspierające funkcje krytyczne lub istotne należy testować co najmniej raz w roku. Wybrane podmioty są objęte zaawansowanym testowaniem **TLPT** (*Threat-Led Penetration Testing*), czyli testami penetracyjnymi prowadzonymi z perspektywy rzeczywistych zagrożeń.

### 4.5. Ryzyko związane z zewnętrznymi dostawcami ICT

DORA obejmuje outsourcing IT, w szczególności usługi chmurowe, hosting, SaaS, centra danych, usługi cyberbezpieczeństwa i podwykonawców.

Podmiot finansowy powinien:

- prowadzić **rejestr informacji** o umowach z dostawcami ICT;
- przed zawarciem umowy ocenić ryzyko, krytyczność usługi, koncentrację i możliwość zastąpienia dostawcy;
- monitorować dostawcę przez cały okres współpracy;
- posiadać strategie wyjścia, plany przejścia i alternatywne rozwiązania dla funkcji krytycznych lub istotnych;
- zapewnić w umowach odpowiednie prawa audytu, dostęp do informacji, wymogi bezpieczeństwa, SLA, obowiązki notyfikacyjne i warunki podwykonawstwa.

**Kluczowa zasada:** outsourcing usługi nie oznacza outsourcingu odpowiedzialności regulacyjnej.

## 5. Funkcje krytyczne lub istotne

To funkcje, których zakłócenie mogłoby istotnie pogorszyć ciągłość działalności, wyniki finansowe, stabilność lub zgodność podmiotu z przepisami. Ich identyfikacja jest ważna, ponieważ determinuje m.in. poziom zabezpieczeń, częstotliwość testów i wymagania wobec dostawców.

Przykłady: obsługa płatności, autoryzacja transakcji, systemy tradingowe, dostęp klientów do rachunków, przetwarzanie danych wymagane do działalności regulowanej.

## 6. Umowy z dostawcami ICT — co powinno się w nich znaleźć?

Zakres zależy od rodzaju usługi, ale dla usług wspierających funkcje krytyczne lub istotne umowa powinna szczególnie regulować:

- pełny opis usługi, lokalizacje przetwarzania i danych oraz uzgodnione poziomy usług;
- zasady poufności, integralności, dostępności i ochrony danych;
- obowiązek pomocy przy incydentach, monitorowaniu i raportowaniu;
- prawa dostępu, inspekcji i audytu dla podmiotu finansowego oraz właściwych organów;
- wymogi dotyczące podwykonawstwa i uprzedniego informowania o zmianach;
- obowiązki w zakresie testów bezpieczeństwa;
- warunki wypowiedzenia, okresy przejściowe, zwrot danych i wsparcie migracji;
- strategię wyjścia oraz możliwość zachowania ciągłości działania po zakończeniu współpracy.

## 7. Nadzór nad krytycznymi dostawcami ICT

DORA ustanawia na poziomie UE ramy nadzoru nad **krytycznymi zewnętrznymi dostawcami ICT**. Europejskie Urzędy Nadzoru (EBA, EIOPA i ESMA) mogą wyznaczać takich dostawców i nadzorować ich w zakresie usług świadczonych dla sektora finansowego.

Dotyczy to szczególnie dostawców, których awaria lub zakłócenie mogłoby mieć szeroki wpływ na wiele instytucji finansowych, np. z powodu dużej koncentracji usług.

## 8. DORA a NIS2, RODO i MiCA

| Regulacja | Relacja do DORA |
|---|---|
| **NIS2** | DORA jest dla objętych nią podmiotów finansowych regulacją sektorową (*lex specialis*) w obszarze objętym DORA. Nie eliminuje potrzeby koordynacji z krajowym systemem cyberbezpieczeństwa. |
| **RODO** | DORA nie zastępuje zasad ochrony danych osobowych. Incydent może wymagać równoległej analizy obowiązków DORA i RODO. |
| **MiCA** | MiCA reguluje m.in. rynek kryptoaktywów; DORA obejmuje odporność cyfrową wskazanych podmiotów z tego rynku. |
| **Wytyczne sektorowe** | DORA harmonizuje wiele wymogów ryzyka ICT, lecz trzeba nadal sprawdzać przepisy sektorowe, krajowe i akty wykonawcze. |

## 9. Jak wdrażać DORA — praktyczna mapa działań

1. **Ustal zakres:** określ podmioty, procesy, systemy, dane i dostawców objętych DORA.
2. **Zidentyfikuj funkcje krytyczne lub istotne** oraz ich zależności ICT.
3. **Wykonaj analizę luk:** porównaj obecny stan z wymogami DORA i właściwymi RTS/ITS.
4. **Nadaj odpowiedzialności:** zaangażuj zarząd, risk, compliance, IT, bezpieczeństwo, zakupy, prawników i właścicieli biznesowych.
5. **Zbuduj/uzupełnij ramy ICT risk management:** polityki, ewidencje aktywów, monitoring, backup, BCP/DRP, zarządzanie zmianą i podatnościami.
6. **Uspójnij incydenty:** klasyfikacja, rejestr, komunikacja, raportowanie i analiza przyczyn źródłowych.
7. **Wprowadź program testów:** harmonogram, niezależność testerów, dowody wykonania oraz śledzenie działań naprawczych.
8. **Przejrzyj dostawców i umowy:** rejestr informacji, oceny ryzyka, koncentracja, audytowalność, podwykonawcy i exit plans.
9. **Zbieraj dowody zgodności:** uchwały, polityki, protokoły testów, wyniki audytów, rejestry, raporty zarządcze i działania naprawcze.
10. **Utrzymuj zgodność ciągle:** DORA to proces operacyjny, nie projekt „jednorazowego wdrożenia”.

## 10. Minimalna lista kontrolna

- [ ] Zarząd zatwierdził i nadzoruje ramy ryzyka ICT.
- [ ] Istnieje aktualny wykaz aktywów ICT i zależności od dostawców.
- [ ] Zidentyfikowano funkcje krytyczne lub istotne.
- [ ] Działają procesy wykrywania, rejestracji i klasyfikacji incydentów.
- [ ] Są przygotowane procedury raportowania poważnych incydentów.
- [ ] Sprawdzono kopie zapasowe, odtworzenie oraz plany ciągłości działania.
- [ ] Jest oparty na ryzyku, udokumentowany program testów odporności.
- [ ] Prowadzony jest rejestr informacji o usługach ICT dostawców zewnętrznych.
- [ ] Umowy z dostawcami zawierają wymagane klauzule, w tym audyt i exit.
- [ ] Analizowane są ryzyko koncentracji oraz zastępowalność dostawców.
- [ ] Działania naprawcze mają właścicieli, terminy i potwierdzenie zamknięcia.

## 11. Słownik pojęć

| Pojęcie | Znaczenie |
|---|---|
| **ICT** | technologie informacyjno-komunikacyjne: systemy, sieci, aplikacje, infrastruktura i usługi wspierające działalność. |
| **Odporność operacyjna cyfrowa** | zdolność do utrzymania integralności i niezawodności działania oraz ciągłego świadczenia usług mimo zakłóceń ICT. |
| **Incydent ICT** | zdarzenie zakłócające bezpieczeństwo sieci lub systemów informacyjnych albo mające niekorzystny wpływ na dane lub usługi. |
| **Poważny incydent ICT** | incydent o wysokim negatywnym wpływie na systemy wspierające funkcje krytyczne lub istotne. |
| **Istotne cyberzagrożenie** | realne zagrożenie, które może istotnie wpłynąć na podmiot, użytkowników lub kontrahentów. |
| **Ryzyko koncentracji ICT** | ryzyko nadmiernej zależności od jednego lub powiązanych dostawców ICT. |
| **TLPT** | zaawansowany, oparty na zagrożeniach test penetracyjny. |
| **RTS/ITS** | regulacyjne/wykonawcze standardy techniczne doprecyzowujące stosowanie DORA. |

## 12. Najczęstsze błędy

- traktowanie DORA wyłącznie jako projektu cyberbezpieczeństwa;
- brak realnego zaangażowania zarządu;
- niepełna inwentaryzacja usług SaaS, chmury i podwykonawców;
- uznanie certyfikatu dostawcy za substytut własnej oceny ryzyka;
- testowanie tylko infrastruktury, bez procesów biznesowych i odtwarzania usług;
- brak ćwiczeń raportowania incydentu pod presją czasu;
- plany wyjścia z chmury bez praktycznie wykonalnej migracji i zabezpieczenia danych;
- brak dokumentowania dowodów wykonania kontroli i działań naprawczych.

## 13. Źródła

1. [Rozporządzenie (UE) 2022/2554 — tekst w EUR-Lex](https://eur-lex.europa.eu/eli/reg/2022/2554/oj/pol).
2. [EUR-Lex — wersja angielska aktu](https://eur-lex.europa.eu/eli/reg/2022/2554/oj/eng) — przydatna do odwołań do artykułów i materiałów EBA/EIOPA/ESMA.

> **Uwaga:** to materiał edukacyjny i organizacyjny, a nie porada prawna. Przy wdrożeniu należy stosować aktualne brzmienie DORA, właściwe RTS/ITS, przepisy sektorowe oraz oczekiwania właściwego organu nadzoru.
