# Control Management 

## 1. Kontrole technologiczne, cyber i dane w AI

AI to nie tylko zwykła aplikacja. Kontrole powinny obejmować cały przepływ: dane wejściowe, model, wdrożenie, użytkowników, wyniki i reakcję na incydenty.

Główne ryzyka:

- **Prywatność i poufność danych** — dane wrażliwe w promptach, danych treningowych lub logach.
- **Cybersecurity** — prompt injection, data poisoning, kradzież modelu, nieautoryzowany dostęp do API/modeli.
- **Jakość danych** — niepełne, błędne lub stronnicze dane dają nieprawidłowe wyniki.
- **Access management** — ograniczenie, kto używa modelu, zmienia prompty i wdraża zmiany.
- **Third-party risk** — ryzyko dostawców chmury, modeli SaaS i API.
- **Monitoring i resilience** — model drift, halucynacje, spadek jakości, incydenty i dostępność usługi.

**Dobra odpowiedź na rozmowę:**

> “I would assess AI controls end-to-end: data inputs, model development, deployment, user access, output monitoring and incident response. My focus would be ensuring that controls are proportionate to the AI use case and its customer, regulatory and operational impact.”

## 2. Ryzyka w ekosystemie AI

| Obszar | Główne ryzyko | Przykładowa kontrola |
|---|---|---|
| Model Risk | Niska jakość, niestabilność lub brak wyjaśnialności modelu | niezależna walidacja, testy, monitoring driftu |
| Legal | IP, copyright, prywatność, zobowiązania umowne | legal review, polityka danych, due diligence dostawcy |
| Regulatory | Niezgodność z AI Act, GDPR i regulacjami bankowymi | klasyfikacja use case’u, dokumentacja, audytowalność |
| Fairness / Conduct | Bias i nierówne traktowanie klientów | bias testing, human oversight, challenge process |
| Operational Risk | Błędne decyzje lub zakłócenie usługi | RCSA, KRI, incident management, fallback |

W banku szczególnie ważne są: **explainability, traceability, human oversight, audit trail** oraz wyraźny właściciel biznesowy.

## 3. AI lifecycle, Responsible AI i governance

1. **Use-case intake** — cel biznesowy i dopuszczalność zastosowania.
2. **Risk classification** — wpływ na klienta, dane osobowe, decyzje i materialność.
3. **Data assessment** — źródło, jakość, zgody, privacy, retencja.
4. **Development/testing** — performance, bias, robustness, security, explainability.
5. **Approval przed wdrożeniem** — business, Risk, Compliance, Legal, Model Risk, Technology.
6. **Deployment** — kontrolowane wdrożenie, RBAC, dokumentacja.
7. **Monitoring** — drift, accuracy, incydenty, KPI/KRI, okresowy review.
8. **Change/retirement** — kontrola zmian, wycofanie, zachowanie dowodów.

### Responsible AI

- fairness,
- transparency / explainability,
- accountability,
- privacy and security,
- safety and reliability,
- human oversight.

### AI Governance

Struktura zapewniająca działanie tych zasad: role i odpowiedzialności, policy, komitety, rejestr use case’ów, approvals, monitoring i reporting dla senior management.

## 4. Big-bank / consulting mindset

Warto podkreślać znajomość:

- trzech linii obrony;
- risk appetite i material risk assessment;
- RCSA, issue management, control testing i KRI/KPI;
- współpracy z Technology, Cyber, Data, Legal, Compliance, Model Risk i Internal Audit;
- skalowalnych standardów możliwych do zastosowania globalnie.


## 5. DORA — Digital Operational Resilience Act

Unijne rozporządzenie dotyczące odporności cyfrowej instytucji finansowych; stosowane od **17 stycznia 2025 r.** Bank ma umieć zapobiec incydentowi ICT, wykryć go, zareagować, utrzymać krytyczne usługi i je odtworzyć.

Pięć filarów:

1. **ICT risk management** — governance, kontrole, BCP/DR, monitoring.
2. **Incident management/reporting** — klasyfikacja, rejestracja i raportowanie poważnych incydentów ICT.
3. **Resilience testing** — testy podatności, pen-testy, scenario testing, a dla części podmiotów TLPT.
4. **Third-party ICT risk** — due diligence, umowy, monitoring, exit plans, concentration risk.
5. **Information sharing** — kontrolowana wymiana informacji o cyberzagrożeniach.

**Związek z AI:** AI zależy od infrastruktury ICT, danych i często dostawców zewnętrznych, więc potrzebuje kontroli resilience, cyber, incident response, BCP i vendor risk.

### DORA w DevOps — inne znaczenie

**DevOps Research and Assessment** nie jest regulacją. To metryki efektywności dostarczania oprogramowania:

1. deployment frequency,
2. lead time for changes,
3. change failure rate,
4. time to restore service.

Na rozmowie w banku „DORA” prawie zawsze oznacza regulację UE. W razie niejasności: *“Do you mean the EU Digital Operational Resilience Act or DevOps Research and Assessment metrics?”*

## 6. EU AI Act

Unijne przepisy dla AI oparte na poziomie ryzyka:

- **Prohibited AI** — zastosowania zakazane, np. social scoring i szkodliwa manipulacja.
- **High-risk AI** — np. AI wpływające na zatrudnienie, kredyt, usługi publiczne czy bezpieczeństwo. Wymaga kontroli danych, dokumentacji, testów, human oversight, cyberbezpieczeństwa i logów.
- **Limited-risk AI** — obowiązki transparentności, np. oznaczenie chatbota lub treści wygenerowanej przez AI.
- **Minimal-risk AI** — zasadniczo bez szczególnych obowiązków.

Dla banku szczególnie istotne są zastosowania wpływające na decyzje kredytowe, ocenę klientów, fraud i dostęp do usług. Należy zapewnić governance, dokumentację, data quality, human oversight, auditability i monitoring przez cały lifecycle.

**GPAI/GenAI** ma też własne obowiązki, np. dokumentację, politykę copyright i informacje dotyczące danych treningowych. Modele o ryzyku systemowym mają dodatkowe wymagania risk management i cyberbezpieczeństwa.


## 7. Podstawowe ataki na AI

- **Prompt injection** — próba nadpisania instrukcji modelu przez użytkownika lub niezaufaną treść.
- **Indirect prompt injection** — złośliwa instrukcja jest ukryta np. w dokumencie, stronie internetowej lub e-mailu przetwarzanym przez AI.
- **Jailbreak** — obejście polityk bezpieczeństwa przez manipulację promptem.
- **Data poisoning** — dodanie złośliwych/błędnych danych do danych treningowych, RAG lub knowledge base.
- **Data leakage** — ujawnienie danych wrażliwych, tajemnic lub informacji poufnych.
- **Model extraction** — kopiowanie zachowania modelu przez masowe zapytania API.
- **Adversarial input** — spreparowane dane wywołujące błędną klasyfikację lub odpowiedź.
- **Insecure tool use / agent hijacking** — nakłonienie agenta z dostępem do narzędzi do nieautoryzowanej akcji.

### Prompt injection — kontrolki

- Traktowanie zewnętrznej treści jako **niezaufanych danych**, a nie instrukcji.
- Wyraźne rozdzielenie system instructions, danych i uprawnień narzędzi.
- Least privilege dla narzędzi i danych.
- Human approval przy działaniach o wysokim wpływie.
- Walidacja input/output, filtrowanie, sandboxing narzędzi.
- Logowanie, monitoring oraz red-team/adversarial testing.


## 8. Krótkie pytania rekrutacyjne

**Jak oceniasz ryzyko nowego use case’u GenAI?**  
„Zaczynam od celu biznesowego i wpływu decyzji. Następnie oceniam dane, klientów, materialność, model/vendor risk, cyber exposure, regulatory obligations oraz potrzebę human oversight. Na tej podstawie definiuję approvals, controls i monitoring.”

**Czym AI risk różni się od tradycyjnego IT risk?**  
„AI jest mniej deterministyczne i zależne od danych. Dochodzą bias, explainability, model drift, prompt injection i odpowiedzialność za automatyczne decyzje.”

**Co zrobić po wykryciu halucynacji modelu?**  
„Ocenić impact i dotknięte przypadki, wdrożyć ograniczenia lub human review, znaleźć root cause, poprawić guardraile i testy, zarejestrować incydent oraz sprawdzić podobne use case’y.”


