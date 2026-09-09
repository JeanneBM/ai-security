# Control Management – AI, Risk & Governance

---

## 1. Control Framework

### Definicja
Control Framework to ustrukturyzowany system zasad, procesów, kontroli i odpowiedzialności, który umożliwia:
- identyfikację ryzyk
- projektowanie i wdrażanie kontroli
- monitorowanie skuteczności kontroli
- raportowanie i eskalację
- zapewnienie zgodności z regulacjami oraz risk appetite organizacji

### Główne elementy
1. **Risk Identification & Assessment**  
   RCSA (Risk & Control Self-Assessment), process mapping, risk taxonomy, materiality / risk tiering

2. **Control Design & Implementation**  
   - Preventive / Detective / Corrective  
   - Automated vs manual  
   - Key Controls vs compensating controls

3. **Control Testing & Assurance**  
   Design Effectiveness + Operating Effectiveness

4. **Monitoring & Metrics**  
   KRI / KPI, continuous monitoring, dashboards, issue tracking

5. **Governance & Accountability**  
   3 Lines of Defence, RACI, policies, standards, ścieżki eskalacji

6. **Issue Management & Remediation**  
   Finding → Action Plan → Tracking → Closure

### Popularne odniesienia
- COSO Internal Control – Integrated Framework
- 3 Lines of Defence model
- NIST AI RMF
- FSB Sound Practices
- DORA (ICT risk)
- EU AI Act

---

## 2. Kontrole technologiczne, cyber i dane w AI

AI to nie tylko zwykła aplikacja. Kontrole powinny obejmować cały przepływ: dane wejściowe, model, wdrożenie, użytkowników, wyniki i reakcję na incydenty.

### Główne ryzyka
- **Prywatność i poufność danych** — dane wrażliwe w promptach, danych treningowych lub logach
- **Cybersecurity** — prompt injection, data poisoning, kradzież modelu, nieautoryzowany dostęp do API/modeli
- **Jakość danych** — niepełne, błędne lub stronnicze dane dają nieprawidłowe wyniki
- **Access management** — ograniczenie, kto używa modelu, zmienia prompty i wdraża zmiany
- **Third-party risk** — ryzyko dostawców chmury, modeli SaaS i API
- **Monitoring i resilience** — model drift, halucynacje, spadek jakości, incydenty i dostępność usługi

### Podejście end-to-end
Kontrole AI należy oceniać kompleksowo: data inputs → model development → deployment → user access → output monitoring → incident response.  
Kontrole powinny być **proporcjonalne** do use case’u oraz jego wpływu na klienta, regulacje i operacje.

---

## 3. Ryzyka w ekosystemie AI

| Obszar             | Główne ryzyko                                              | Przykładowa kontrola                                  |
|--------------------|------------------------------------------------------------|-------------------------------------------------------|
| Model Risk         | Niska jakość, niestabilność lub brak wyjaśnialności modelu | Niezależna walidacja, testy, monitoring driftu        |
| Legal              | IP, copyright, prywatność, zobowiązania umowne             | Legal review, polityka danych, due diligence dostawcy |
| Regulatory         | Niezgodność z AI Act, GDPR i regulacjami sektorowymi       | Klasyfikacja use case’u, dokumentacja, audytowalność  |
| Fairness / Conduct | Bias i nierówne traktowanie                                | Bias testing, human oversight, challenge process      |
| Operational Risk   | Błędne decyzje lub zakłócenie usługi                       | RCSA, KRI, incident management, fallback              |

Szczególnie istotne: **explainability, traceability, human oversight, audit trail** oraz wyraźny właściciel biznesowy.

### Kluczowe ryzyka GenAI / Agentic AI
- Hallucination / confabulation
- Bias i dyskryminacyjne wyniki
- Ograniczona explainability
- Data leakage / prompt injection
- Model drift / degradation
- Autonomy risk
- Tool-use risk
- Third-party / concentration risk
- Adversarial attacks (poisoning, model theft)
- Brak human oversight

---

## 4. AI Lifecycle Management

1. **Use-case intake** — cel biznesowy i dopuszczalność zastosowania  
2. **Risk classification** — wpływ na klienta, dane osobowe, decyzje i materialność  
3. **Data assessment** — źródło, jakość, zgody, privacy, retencja  
4. **Development / testing** — performance, bias, robustness, security, explainability  
5. **Approval przed wdrożeniem** — Business, Risk, Compliance, Legal, Model Risk, Technology  
6. **Deployment** — kontrolowane wdrożenie, RBAC, dokumentacja  
7. **Monitoring** — drift, accuracy, incydenty, KPI/KRI, okresowy review  
8. **Change / retirement** — kontrola zmian, wycofanie, zachowanie dowodów  

Kontrole powinny być stosowane proporcjonalnie do materialności i poziomu ryzyka na każdym etapie.

---

## 5. Responsible AI & AI Governance

### Responsible AI – kluczowe zasady
- Fairness
- Transparency / explainability
- Accountability
- Privacy and security
- Safety and reliability
- Human oversight

### AI Governance
Struktura zapewniająca działanie powyższych zasad:
- Role i odpowiedzialności (RACI)
- Policy i standards
- Komitety
- Rejestr use case’ów (AI Inventory)
- Approvals
- Monitoring i reporting dla senior management
- Integracja z istniejącym risk management frameworkiem
- Continuous learning i adaptacja do ewolucji technologii

---

## 6. 3 Lines of Defence w kontekście AI

| Linia   | Rola |
|---------|------|
| **1LOD** | Business / Technology – właściciel ryzyka, projektowanie i wdrażanie kontroli, codzienne zarządzanie ryzykiem |
| **2LOD** | Risk / Compliance – niezależny oversight, challenge, definiowanie standardów, monitoring |
| **3LOD** | Internal Audit – niezależna ocena skuteczności całego systemu kontroli |

AI nie zmienia modelu 3LoD – wymaga jedynie jasnego przypisania odpowiedzialności i unikania sytuacji, w której nikt nie jest właścicielem ryzyka AI.

---

## 7. DORA – Digital Operational Resilience Act

Unijne rozporządzenie dotyczące odporności cyfrowej instytucji finansowych (stosowane od 17 stycznia 2025 r.).  
Organizacja ma umieć zapobiec incydentowi ICT, wykryć go, zareagować, utrzymać krytyczne usługi i je odtworzyć.

### Pięć filarów
1. **ICT risk management** — governance, kontrole, BCP/DR, monitoring  
2. **Incident management / reporting** — klasyfikacja, rejestracja i raportowanie poważnych incydentów ICT  
3. **Resilience testing** — testy podatności, pen-testy, scenario testing, a dla części podmiotów TLPT  
4. **Third-party ICT risk** — due diligence, umowy, monitoring, exit plans, concentration risk  
5. **Information sharing** — kontrolowana wymiana informacji o cyberzagrożeniach  

**Związek z AI:** AI zależy od infrastruktury ICT, danych i często dostawców zewnętrznych, dlatego wymaga kontroli resilience, cyber, incident response, BCP i vendor risk.

> Uwaga: „DORA” w kontekście DevOps oznacza DevOps Research and Assessment (metryki: deployment frequency, lead time for changes, change failure rate, time to restore service). W kontekście regulacyjnym prawie zawsze chodzi o Digital Operational Resilience Act.

---

## 8. EU AI Act

Przepisy oparte na poziomie ryzyka:

| Kategoria          | Charakterystyka                                      | Wymagania |
|--------------------|------------------------------------------------------|---------|
| **Prohibited AI**  | Zastosowania zakazane (np. social scoring, szkodliwa manipulacja) | Zakaz |
| **High-risk AI**   | Wpływ na zatrudnienie, kredyt, usługi publiczne, bezpieczeństwo | Kontrola danych, dokumentacja, testy, human oversight, cyberbezpieczeństwo, logi |
| **Limited-risk AI**| Obowiązki transparentności (np. oznaczenie chatbota lub treści AI) | Transparentność |
| **Minimal-risk AI**| Zasadniczo bez szczególnych obowiązków               | — |

Szczególnie istotne zastosowania wpływające na decyzje kredytowe, ocenę klientów, fraud i dostęp do usług.  
Należy zapewnić: governance, dokumentację, data quality, human oversight, auditability i monitoring przez cały lifecycle.

**GPAI / GenAI** mają dodatkowe obowiązki (dokumentacja, polityka copyright, informacje o danych treningowych). Modele o ryzyku systemowym – dodatkowe wymagania risk management i cyberbezpieczeństwa.

---

## 9. Podstawowe ataki na AI

- **Prompt injection** — próba nadpisania instrukcji modelu przez użytkownika lub niezaufaną treść  
- **Indirect prompt injection** — złośliwa instrukcja ukryta w dokumencie, stronie lub e-mailu przetwarzanym przez AI  
- **Jailbreak** — obejście polityk bezpieczeństwa przez manipulację promptem  
- **Data poisoning** — dodanie złośliwych/błędnych danych do danych treningowych, RAG lub knowledge base  
- **Data leakage** — ujawnienie danych wrażliwych, tajemnic lub informacji poufnych  
- **Model extraction** — kopiowanie zachowania modelu przez masowe zapytania API  
- **Adversarial input** — spreparowane dane wywołujące błędną klasyfikację lub odpowiedź  
- **Insecure tool use / agent hijacking** — nakłonienie agenta z dostępem do narzędzi do nieautoryzowanej akcji  

### Kontrole przeciw prompt injection
- Traktowanie zewnętrznej treści jako **niezaufanych danych**, a nie instrukcji  
- Wyraźne rozdzielenie system instructions, danych i uprawnień narzędzi  
- Least privilege dla narzędzi i danych  
- Human approval przy działaniach o wysokim wpływie  
- Walidacja input/output, filtrowanie, sandboxing narzędzi  
- Logowanie, monitoring oraz red-team / adversarial testing  

---

## 10. Kluczowe ramy i standardy

- **FSB Sound Practices for Responsible AI Adoption** — 12 praktyk obejmujących governance i lifecycle  
- **NIST AI Risk Management Framework (AI RMF)** + sector-specific (Financial Services AI RMF)  
- **EU AI Act** — szczególnie wymagania dla high-risk systems  
- **DORA** — ICT risk management (w tym systemy AI)  
- **COSO** — klasyczna baza Internal Control Framework  
- Guardrails: enterprise-level (governance, training, policies) vs system-level (red teaming, monitoring, human-in-the-loop, prompt design)

---

## 11. NISP

**National Industrial Security Program (USA)**  
Program rządowy (Executive Order 12829 z 1993 r.) regulujący dostęp prywatnego przemysłu do informacji niejawnych (classified information).

- Główny dokument: **NISPOM** (NISP Operating Manual / DoD 5220.22-M)
- Administruje: Defense Counterintelligence and Security Agency (DCSA)
- Zakres: facility clearances, personnel security clearances, ochrona informacji niejawnych, wymagania cyber security dla systemów przetwarzających informacje niejawne

Inne znaczenia: NATO Interoperability Standards and Profiles, Number of Identified Specimens, NextGenPSD2 Implementation Support Program.

---

## 12. Kluczowe pojęcia

- RCSA (Risk & Control Self-Assessment)
- Risk taxonomy & materiality
- Design Effectiveness vs Operating Effectiveness
- Key Risk Indicators (KRI) / Key Performance Indicators (KPI)
- Human-in-the-Loop (HITL)
- Data lineage & provenance
- Continuous monitoring & drift detection
- Guardrails (enterprise vs system-level)
- Least privilege (szczególnie dla agentów AI)
- Issue management & remediation tracking
- Risk appetite alignment
- Explainability / Traceability / Audit trail

---

## 13. Dobre praktyki budowy kontroli

- Kontrole powinny być **proporcjonalne** do materialności ryzyka
- Preferowane podejście: **outcome-focused** zamiast czysto proceduralnego
- Unikać zarówno braku kontroli, jak i nadmiernych / nieefektywnych kontroli
- AI controls należy **embedować** w istniejące frameworki, a nie budować osobnego silosu
- Łączyć design effectiveness z continuous monitoring
- Zapewniać jasną accountability (szczególnie w 1LOD)
- Regularnie weryfikować, czy framework nadąża za ewolucją technologii (szczególnie GenAI i agentic AI)
- Traktować zewnętrzną treść jako niezaufaną (szczególnie w kontekście prompt injection)
- Stosować least privilege i human approval przy działaniach o wysokim wpływie

---

*Notatki – Control Management, AI Risk, Governance, DORA, EU AI Act*
