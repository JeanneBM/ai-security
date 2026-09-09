# EU AI Act
> **EU AI Act** (Akt w sprawie sztucznej inteligencji) to rozporządzenie UE 2024/1689 ustanawiające jednolite zasady dotyczące rozwoju, wprowadzania do obrotu, oddawania do użytku i używania systemów AI w Unii Europejskiej.

## 1. Cel regulacji

AI Act ma wspierać innowację i swobodny przepływ rozwiązań AI w UE, jednocześnie chroniąc zdrowie, bezpieczeństwo i prawa podstawowe. Przyjmuje **podejście oparte na ryzyku**: im większe ryzyko wywołane zastosowaniem AI, tym surowsze obowiązki.

Rozporządzenie jest bezpośrednio stosowane w państwach UE. Nie zastępuje RODO, prawa konsumenckiego, prawa pracy ani przepisów sektorowych — działa obok nich.

## 2. Metryka i harmonogram

| Element | Treść |
|---|---|
| Akt prawny | Rozporządzenie Parlamentu Europejskiego i Rady (UE) 2024/1689 |
| Data przyjęcia | 13 czerwca 2024 r. |
| Wejście w życie | 1 sierpnia 2024 r. |
| Zasadnicze stosowanie | od 2 sierpnia 2026 r. |
| Zakazy i obowiązek AI literacy | od 2 lutego 2025 r. |
| Obowiązki dla modeli AI ogólnego przeznaczenia (GPAI) | od 2 sierpnia 2025 r. |
| Systemy wysokiego ryzyka jako komponenty bezpieczeństwa / objęte prawem produktowym (art. 6 ust. 1) | od 2 sierpnia 2027 r. |

## 3. Kogo obejmuje?

AI Act może dotyczyć podmiotów mających siedzibę w UE, ale również podmiotów spoza UE, gdy system lub jego wyniki są używane w UE. Kluczowe role to:

| Rola | Kto to jest? | Przykład |
|---|---|---|
| **Dostawca (provider)** | rozwija system AI lub zleca jego rozwój i oferuje go pod własną nazwą | firma sprzedająca model lub aplikację AI |
| **Wdrażający/użytkownik profesjonalny (deployer)** | używa systemu AI pod własnym nadzorem, poza użyciem czysto osobistym | pracodawca używający AI do selekcji CV |
| **Importer** | wprowadza na rynek UE system AI dostawcy spoza UE | importer rozwiązania AI z USA |
| **Dystrybutor** | udostępnia system w łańcuchu dostaw | reseller oprogramowania |
| **Upoważniony przedstawiciel** | reprezentuje dostawcę spoza UE | podmiot wyznaczony przez producenta |

**Ważne:** organizacja korzystająca z gotowego narzędzia AI nie zawsze jest dostawcą, ale może stać się nim np. gdy zmieni przeznaczenie systemu albo wprowadzi istotną modyfikację.

## 4. Czym jest system AI?

To system maszynowy zaprojektowany do działania z różnym poziomem autonomii, który może wykazywać zdolność do adaptacji po wdrożeniu i na podstawie danych wejściowych wnioskuje, jak generować wyniki — np. predykcje, treści, rekomendacje lub decyzje — mogące wpływać na środowisko fizyczne lub cyfrowe.

Nie każde klasyczne oprogramowanie automatyzujące proste, z góry określone reguły będzie systemem AI w tym znaczeniu.

## 5. Model ryzyka

| Kategoria | Skutek regulacyjny | Przykładowa sytuacja |
|---|---|---|
| **Niedopuszczalne ryzyko** | zakaz używania określonych praktyk | system manipulujący lub wykorzystujący szczególną podatność osoby |
| **Wysokie ryzyko** | rozbudowane wymagania dotyczące systemu i jego użycia | AI do rekrutacji, oceny kredytowej czy dostępu do edukacji |
| **Ograniczone ryzyko / transparentność** | obowiązki informacyjne | chatbot, deepfake, generowanie lub manipulowanie treściami |
| **Minimalne ryzyko** | co do zasady brak szczególnych obowiązków AI Act | większość prostych zastosowań AI, jeśli nie wchodzą w inne kategorie |

Klasyfikacji nie dokonuje się wyłącznie na podstawie technologii (np. „to LLM”), lecz na podstawie **zamierzonego zastosowania**, kontekstu i wpływu na ludzi.

## 6. Praktyki zakazane (art. 5)

AI Act zakazuje m.in. określonych zastosowań AI, takich jak:

- stosowanie technik podprogowych, manipulacyjnych lub wprowadzających w błąd w sposób mogący istotnie zniekształcić zachowanie i wyrządzić szkodę;
- wykorzystywanie podatności związanej z wiekiem, niepełnosprawnością lub szczególną sytuacją społeczno-ekonomiczną w celu istotnego zniekształcenia zachowania i wyrządzenia szkody;
- scoring społeczny prowadzący do niekorzystnego traktowania nieproporcjonalnego lub niezwiązanego z pierwotnym kontekstem;
- ocena ryzyka popełnienia przestępstwa wyłącznie na podstawie profilowania lub cech osobowości;
- nieukierunkowane pozyskiwanie z internetu lub nagrań CCTV wizerunków twarzy do tworzenia baz rozpoznawania twarzy;
- rozpoznawanie emocji w miejscu pracy i placówkach edukacyjnych (z ograniczonymi wyjątkami);
- kategoryzacja biometryczna wnioskująca o cechach wrażliwych, np. rasie, poglądach politycznych, religii lub orientacji seksualnej;
- zdalna identyfikacja biometryczna w czasie rzeczywistym w przestrzeni publicznej dla celów ścigania — poza ściśle określonymi wyjątkami i gwarancjami.

## 7. Systemy AI wysokiego ryzyka

System jest wysokiego ryzyka, gdy:

1. jest komponentem bezpieczeństwa produktu albo sam jest produktem objętym wskazanym unijnym prawem harmonizacyjnym i podlega ocenie zgodności przez stronę trzecią, **lub**
2. należy do obszarów z załącznika III i może stwarzać znaczące ryzyko dla zdrowia, bezpieczeństwa lub praw podstawowych.

### Obszary z załącznika III — przykłady

- biometria;
- infrastruktura krytyczna;
- edukacja i kształcenie zawodowe;
- zatrudnienie, zarządzanie pracownikami i dostęp do samozatrudnienia;
- dostęp do podstawowych usług prywatnych i publicznych oraz świadczeń (np. ocena zdolności kredytowej);
- ściganie przestępstw;
- migracja, azyl i kontrola graniczna;
- wymiar sprawiedliwości i procesy demokratyczne.

Niektóre systemy z załącznika III mogą nie być uznane za wysokiego ryzyka, jeżeli nie stwarzają znaczącego ryzyka (np. wykonują wąskie zadanie proceduralne), ale wymaga to udokumentowanej oceny. Systemy profilujące osoby fizyczne pozostają wysokiego ryzyka.

## 8. Wymagania dla wysokiego ryzyka (art. 8–15)

Przed wprowadzeniem systemu wysokiego ryzyka do obrotu lub użycia dostawca musi zapewnić m.in.:

1. **System zarządzania ryzykiem** — prowadzony przez cały cykl życia.
2. **Jakość danych i zarządzanie danymi** — odpowiednie zbiory treningowe, walidacyjne i testowe; ograniczanie błędów i stronniczości.
3. **Dokumentację techniczną** — umożliwiającą ocenę zgodności.
4. **Rejestrowanie zdarzeń (logi)** — zapewniające śledzalność działania.
5. **Przejrzystość i instrukcje użycia** — wystarczające dla wdrażającego.
6. **Nadzór człowieka** — możliwość rozumienia, nadzorowania i odpowiedniej interwencji.
7. **Dokładność, odporność i cyberbezpieczeństwo** — także względem błędów, ataków i degradacji działania.

Dodatkowo potrzebne są: system zarządzania jakością, ocena zgodności, deklaracja zgodności UE, oznakowanie CE (gdy ma zastosowanie), rejestracja w bazie UE oraz monitoring po wprowadzeniu na rynek.

## 9. Obowiązki wdrażającego system wysokiego ryzyka

Wdrażający powinien używać systemu zgodnie z instrukcją dostawcy i w szczególności:

- wdrożyć środki nadzoru człowieka;
- zapewnić, by dane wejściowe były adekwatne i wystarczająco reprezentatywne dla celu użycia;
- monitorować działanie oraz przechowywać logi pod własną kontrolą, gdy ma do nich dostęp;
- zgłaszać dostawcy incydenty i nieprawidłowości mogące stanowić ryzyko;
- poinformować osoby, że podlegają decyzji lub wsparciu decyzyjnemu przez system wysokiego ryzyka, gdy wymaga tego AI Act;
- wykonać ocenę wpływu na prawa podstawowe, jeśli należy do kategorii wskazanych w art. 27 (np. podmiot publiczny, prywatny podmiot świadczący usługę publiczną lub określone zastosowania kredytowe/ubezpieczeniowe).

## 10. Obowiązki transparentności (art. 50)

W określonych przypadkach osoby muszą otrzymać jasną informację, że mają do czynienia z AI. Dotyczy to m.in.:

- systemów przeznaczonych do bezpośredniej interakcji z człowiekiem (np. chatbotów), chyba że jest to oczywiste z kontekstu;
- systemów rozpoznawania emocji i kategoryzacji biometrycznej — osoby narażone na ich działanie mają być poinformowane;
- treści generowanych lub modyfikowanych przez AI, zwłaszcza deepfake’ów — wymagane jest oznaczanie w formacie umożliwiającym odczyt maszynowy;
- publikowania materiału w interesie publicznym — konieczne jest ujawnienie, że treść została wygenerowana lub zmanipulowana przez AI, z wyjątkami przewidzianymi w regulacji.

## 11. Modele AI ogólnego przeznaczenia (GPAI)

**GPAI** to model AI zdolny kompetentnie wykonywać szeroki zakres różnych zadań i możliwy do zintegrowania z wieloma systemami lub aplikacjami. Nie jest tym samym co każda aplikacja korzystająca z modelu.

### Obowiązki dostawcy GPAI

- sporządzenie i aktualizowanie dokumentacji technicznej;
- przekazywanie dalszym dostawcom informacji i dokumentacji potrzebnych do integracji modelu;
- ustanowienie polityki poszanowania prawa autorskiego UE;
- opublikowanie wystarczająco szczegółowego streszczenia treści użytych do trenowania modelu.

Modele GPAI o **ryzyku systemowym** mają dodatkowe obowiązki: ocena i ograniczanie ryzyk systemowych, testowanie/adversarial testing, raportowanie poważnych incydentów oraz zapewnienie odpowiedniego poziomu cyberbezpieczeństwa.

## 12. AI literacy — kompetencje w zakresie AI

Dostawcy i wdrażający mają podejmować środki zapewniające wystarczający poziom kompetencji AI personelu i innych osób używających systemu w ich imieniu. Zakres powinien odpowiadać roli, wiedzy technicznej, doświadczeniu, edukacji oraz kontekstowi użycia i osobom, których dotyczy system.

W praktyce oznacza to nie tylko szkolenie „z promptowania”, lecz także wiedzę o ograniczeniach modelu, błędach, stronniczości, prywatności, bezpieczeństwie i procedurach eskalacji.

## 13. AI Act a RODO, DSA i prawo pracy

| Obszar | Relacja |
|---|---|
| **RODO** | AI Act nie zastępuje podstawy prawnej przetwarzania danych, obowiązków informacyjnych, oceny DPIA ani praw osób, których dane dotyczą. |
| **Prawo pracy** | Użycie AI wobec pracowników może wymagać spełnienia dodatkowych wymogów krajowych i unijnych. AI Act zakazuje rozpoznawania emocji w pracy poza wąskimi wyjątkami. |
| **DSA** | DSA reguluje obowiązki pośredników i platform; AI Act wprowadza odrębne wymagania związane z AI. |
| **Prawo sektorowe** | W medycynie, finansach, transporcie czy produktach konsumenckich należy stosować równolegle przepisy branżowe. |

## 14. Kary

Najwyższa administracyjna kara za naruszenie zakazanych praktyk wynosi do **35 mln EUR albo 7% całkowitego światowego rocznego obrotu** z poprzedniego roku — stosuje się kwotę wyższą. Pozostałe naruszenia mogą również prowadzić do istotnych sankcji, zależnych od rodzaju obowiązku i statusu podmiotu.

## 15. Praktyczna mapa wdrożenia

1. **Zrób inwentaryzację AI:** narzędzia własne, kupione, chmurowe, eksperymentalne oraz używane przez zespoły.
2. **Przypisz role:** kto jest dostawcą, wdrażającym, importerem lub dystrybutorem.
3. **Sklasyfikuj zastosowania:** zakazane, wysokiego ryzyka, transparentność lub pozostałe.
4. **Zatrzymaj lub przeprojektuj zastosowania zakazane.**
5. **Dla high-risk:** przygotuj zarządzanie ryzykiem, dokumentację, jakość danych, logi, nadzór człowieka i ocenę zgodności.
6. **Dla narzędzi generatywnych:** wdroż zasady oznaczania treści, korzystania z danych i kontroli użytkownika.
7. **Uzupełnij procesy zakupowe:** wymagaj od dostawców dokumentacji, instrukcji, informacji o danych i warunkach wsparcia zgodności.
8. **Przeprowadź AI literacy:** dostosowane do ról szkolenia oraz krótkie zasady używania AI.
9. **Połącz zgodność:** z RODO, bezpieczeństwem, prawem pracy, compliance i zarządzaniem dostawcami.
10. **Monitoruj zmiany:** standardy, wytyczne Komisji i aktów wykonawczych będą doprecyzowywać praktykę stosowania.

## 16. Checklista organizacji

- [ ] Prowadzimy aktualny rejestr systemów i modeli AI.
- [ ] Znamy role organizacji w łańcuchu wartości AI.
- [ ] Dla każdego zastosowania wykonano ocenę ryzyka i udokumentowano klasyfikację.
- [ ] Nie używamy praktyk zakazanych.
- [ ] Personel ma adekwatne kompetencje AI.
- [ ] Dla systemów wysokiego ryzyka istnieją wymagane dokumenty, logi, kontrola ryzyka i nadzór człowieka.
- [ ] Wykonano ocenę wpływu na prawa podstawowe tam, gdzie jest wymagana.
- [ ] Chatboty i treści syntetyczne są właściwie oznaczane.
- [ ] Umowy z dostawcami AI zapewniają potrzebną dokumentację i wsparcie zgodności.
- [ ] Procedury RODO, cyberbezpieczeństwa i zarządzania incydentami obejmują użycie AI.

## 17. Słownik

| Termin | Znaczenie |
|---|---|
| **System AI** | system maszynowy wnioskujący na podstawie danych wejściowych i generujący wyniki mogące oddziaływać na środowisko. |
| **GPAI** | model AI ogólnego przeznaczenia, możliwy do wykorzystania w wielu zadaniach. |
| **Dostawca** | podmiot rozwijający/oferujący system AI pod własną nazwą. |
| **Wdrażający** | podmiot używający systemu AI w działalności zawodowej lub publicznej. |
| **High-risk** | system AI wysokiego ryzyka, objęty szczególnymi wymaganiami. |
| **Nadzór człowieka** | środki pozwalające człowiekowi zrozumieć, monitorować i interweniować w działanie AI. |
| **AI literacy** | umiejętności i wiedza potrzebne do świadomego używania AI oraz rozumienia jej ryzyk. |

## 18. Źródła

1. [Rozporządzenie (UE) 2024/1689 — AI Act, EUR-Lex](https://eur-lex.europa.eu/eli/reg/2024/1689/oj/pol).
2. [Aktualna wersja AI Act w EUR-Lex](https://eur-lex.europa.eu/eli/reg/2024/1689/oj/eng).

> **Uwaga:** notatki mają charakter edukacyjny, nie stanowią porady prawnej. Do konkretnego wdrożenia należy użyć aktualnego tekstu aktu, właściwych wytycznych i przepisów sektorowych.
