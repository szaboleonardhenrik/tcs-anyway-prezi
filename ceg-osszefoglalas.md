# AIway — Cégalapítási Összefoglaló & Döntési Keretrendszer

> **Weboldal:** aiway.hu
> **Státusz:** Alapítás alatt
> **Dátum:** 2026-03-19

---

## 1. CSAPAT & SZERVEZETI FELÉPÍTÉS

### Alapítók (4 fő, tulajdonosok)

| Név | Szerep (kitöltendő) | Tulajdoni hányad | Tőkebefektetés | Fő felelősségi terület |
|-----|---------------------|-------------------|----------------|----------------------|
| **Amir** | ? | ?% | ? Ft | ? |
| **Jani** | ? | ?% | ? Ft | ? |
| **Attila** | ? | ?% | ? Ft | ? |
| **Leonárd** | ? | ?% | ? Ft | ? |

### Alkalmazott(ak)

| Név | Pozíció | Riportál | Munkaviszony típusa | Bér/kompenzáció |
|-----|---------|----------|---------------------|-----------------|
| **Gergő** | IT Szoftverfejlesztő (vibe coder) | **Leonárd** (direct report) | ? (alkalmazott / szerződéses) | ? |

### Eldöntendő kérdések — Szervezet
- [ ] Milyen cégforma? (Kft. a legvalószínűbb)
- [ ] Tulajdoni arányok: egyenlő 25-25-25-25%, vagy eltérő?
- [ ] Tőkebefektetés: mindenki egyenlően rak bele, vagy arányosan eltérően?
- [ ] Ki a **cégvezető / ügyvezető**? (Egy fő vagy több?)
- [ ] Ki a **technikai vezető** (CTO)?
- [ ] Ki felel az **üzleti fejlesztésért / értékesítésért**?
- [ ] Ki felel a **pénzügyekért / számlázásért**?
- [ ] Ki felel a **marketingért / brandért**?
- [ ] Gergő munkaviszonya: alkalmazott (munkaszerződés) vagy megbízási/vállalkozói?
- [ ] Van-e vesting (fokozatos tulajdonszerzés) az alapítóknak?

---

## 2. JAVASOLT SZEREPKÖRÖK (sablonok — egyeztessetek)

Egy AI szoftverfejlesztő céghez tipikusan ezek a kulcsszerepek:

| Szerep | Felelősség | Javasolt személy |
|--------|-----------|------------------|
| **CEO / Ügyvezető** | Stratégia, cégvezetés, jogi, partnerkapcsolatok | ? |
| **CTO / Tech Lead** | Technológiai döntések, architektúra, code review | ? |
| **Sales / Üzletfejlesztés** | Ügyfélszerzés, ajánlatkészítés, tárgyalás | ? |
| **Projektmenedzsment** | Projektek koordinálása, deadline-ok, ügyfélkommunikáció | ? |
| **Marketing / Brand** | Weboldal, social media, tartalom, SEO | ? |
| **Pénzügy / Operáció** | Könyvelés, számlázás, szerződések, költségvetés | ? |
| **AI / ML Specialist** | AI megoldások tervezése, prompt engineering, modell kiválasztás | ? |
| **Fejlesztő** | Kódolás, implementáció, tesztelés | Gergő + ? |

> **Megjegyzés:** 4 alapítónál egy ember több sapkát is visel. A lényeg, hogy minden terület le legyen fedve és mindenki tudja, miért felel.

---

## 3. SZOLGÁLTATÁSOK (aiway.hu alapján)

### Fő tevékenységi körök

1. **Egyedi szoftverfejlesztés** — Webes és mobil alkalmazások, SaaS termékek
2. **AI alkalmazásfejlesztés** — AI-alapú szoftverek, chatbotok, automatizálás
3. **AI tanácsadás** — Vállalati AI stratégia, bevezetés, oktatás
4. **Mobilalkalmazás fejlesztés** — Android/iOS appok
5. **Automatizálás** — Üzleti folyamatok automatizálása AI-val

### Eldöntendő kérdések — Szolgáltatások
- [ ] Melyik szolgáltatás a **fő bevételi forrás** induláskor?
- [ ] Árazási modell: óradíjas / projektáras / retainer / előfizetéses?
- [ ] Óradíj sáv: ? Ft/óra (piac: 15.000–50.000 Ft/óra fejlesztőtől függően)
- [ ] Célpiac: KKV-k, nagyvállalatok, startubok, vagy vegyes?
- [ ] Iparági fókusz van? (pl. e-commerce, egészségügy, pénzügy...)

---

## 4. SZOFTVERTERMÉKEK — BRAINSTORMING

> Ez a rész a közös brainstorming eredményeit gyűjti. Minden ötletet jegyezzetek fel, utána szűritek.

---

### A) MAGYAR PIACRA FÓKUSZÁLT TERMÉKEK

#### 1. AI Ügyfélszolgálati Asszisztens (magyar KKV-knak)
- **Mi ez:** Magyar nyelvű AI chatbot, amit bármely KKV beágyazhat a weboldalába. Tanulja meg a cég GYIK-jét, termékeket, árakat, és válaszol az ügyfeleknek 24/7.
- **Célpiac:** Magyar KKV-k (webshopok, szolgáltatók, éttermek, szállodák, ügyvédi irodák)
- **Miért jó:** A magyar KKV-k 90%-ának nincs ügyfélszolgálata éjjel/hétvégén. A Tidio, Intercom stb. drága és nem beszél jól magyarul.
- **Bevétel:** SaaS — 9.900 Ft/hó (alap) / 29.900 Ft/hó (pro) / 79.900 Ft/hó (enterprise)
- **MVP idő:** 4–6 hét
- **Tech:** LLM API + RAG (cég dokumentumai alapján) + widget embed
- **Versenyelőny:** Magyar nyelv, egyszerű setup (URL-t beírod és tanul), olcsóbb mint Intercom

#### 2. AI Számlaelemző / Könyvelés Asszisztens
- **Mi ez:** Feltöltöd a számláidat (PDF/kép), az AI kinyeri az adatokat, kategorizálja, és előkészíti a könyvelőnek. NAV kompatibilis export.
- **Célpiac:** Magyar egyéni vállalkozók, kis cégek, könyvelő irodák
- **Miért jó:** Rengeteg EV kézzel viszi be a számlákat. A könyvelők idejük 40%-át adatbevitelre pazarolják.
- **Bevétel:** SaaS — 4.900 Ft/hó (EV) / 19.900 Ft/hó (könyvelő iroda, korlátlan ügyfél)
- **MVP idő:** 6–8 hét
- **Tech:** OCR + LLM + NAV API integráció
- **Versenyelőny:** Magyar NAV-kompatibilis, AI kategorizálás, könyvelő-barát export

#### 3. AI Álláshirdetés & Toborzás Platform
- **Mi ez:** Cég leírja milyen embert keres → AI generálja az álláshirdetést, szűri a beérkező CV-ket, rangsorolja a jelölteket, és javasol interjúkérdéseket.
- **Célpiac:** Magyar KKV-k akik toborznak (HR osztály nélkül)
- **Miért jó:** Profession.hu drága, a KKV-k nem tudnak HR-est fizetni. Az AI leveszi a szűrés terhét.
- **Bevétel:** Per hirdetés (9.900 Ft) + SaaS (29.900 Ft/hó korlátlan)
- **MVP idő:** 6–8 hét
- **Tech:** LLM + CV parser + matching algoritmus

#### 4. AI Marketing Asszisztens magyar KKV-knak
- **Mi ez:** Social media posztok, blog cikkek, hírlevél szövegek, Google Ads szövegek generálása magyarul, a cég brandjéhez igazítva.
- **Célpiac:** Magyar KKV-k marketing csapat nélkül
- **Miért jó:** A ChatGPT generic, nem ismeri a magyar piacot/trendeket. Ez a cég hangjához tanul.
- **Bevétel:** SaaS — 9.900 Ft/hó (alap) / 24.900 Ft/hó (pro, korlátlan)
- **MVP idő:** 3–4 hét (leggyorsabb MVP!)
- **Tech:** LLM + brand profil + ütemező integráció (FB, Insta API)

#### 5. AI Dokumentum Asszisztens / Szerződéselemző
- **Mi ez:** Feltöltöd a szerződésedet, az AI összefoglalja, kiemel kockázatokat, összehasonlítja korábbi szerződésekkel, és javasol módosításokat.
- **Célpiac:** Ügyvédi irodák, ingatlanosok, KKV vezetők
- **Miért jó:** Egy szerződés átnézése ügyvédnél 50-100e Ft. Egy AI előszűrés töredéke.
- **Bevétel:** SaaS — 14.900 Ft/hó / per dokumentum árazás
- **MVP idő:** 5–7 hét
- **Tech:** LLM + RAG + PDF parser
- **Megjegyzés:** Leonárdnak van már tapasztalata ezzel (Legitas projekt!)

---

### B) NEMZETKÖZI PIACRA IS SKÁLÁZHATÓ TERMÉKEK

#### 6. AI Code Review Bot (GitHub/GitLab integráció)
- **Mi ez:** Automatikus AI code review minden PR-hez. Bugokat, biztonsági réseket, code smell-eket talál, és javasol javítást.
- **Célpiac:** Dev csapatok, startubok, SaaS cégek (nemzetközi)
- **Miért jó:** A CodeRabbit, Sourcery stb. még nem uralta le a piacot. $10-50/dev/hó szegmens hatalmas.
- **Bevétel:** SaaS — $15/dev/hó
- **MVP idő:** 6–8 hét
- **Tech:** GitHub App + LLM + AST elemzés
- **Skálázhatóság:** Azonnal nemzetközi, nincs nyelvi korlát

#### 7. AI Meeting Notes & Action Items
- **Mi ez:** Rögzíti a meetinget (audio), átírja szöveggé, AI összefoglalja, kinyeri a teendőket, és beírja a projektmenedzsment toolba (Notion, Linear, Jira).
- **Célpiac:** Remote csapatok, tanácsadó cégek, értékesítési csapatok
- **Miért jó:** Az Otter.ai, Fireflies drágák és rosszul kezelik az EU-s adatvédelmet.
- **Bevétel:** SaaS — $12/user/hó
- **MVP idő:** 8–10 hét
- **Tech:** Whisper/Deepgram (STT) + LLM + PM tool API-k
- **Versenyelőny:** GDPR-kompatibilis, EU hosting, többnyelvű (magyar is!)

#### 8. AI-Powered Form Builder
- **Mi ez:** Leírod szövegesen milyen űrlapot szeretnél → AI legenerálja, logikával, validációval, feltételes mezőkkel. Embed bárhova.
- **Célpiac:** Marketingesek, HR, ügyfélszolgálat, bármely iparág
- **Miért jó:** A Typeform, JotForm szép de manuális. "Csinálj egy rendelés űrlapot pizza kiszállításhoz" → kész.
- **Bevétel:** SaaS — $19/hó (alap) / $49/hó (pro)
- **MVP idő:** 6–8 hét
- **Tech:** LLM + React form renderer + embed widget

#### 9. AI Proposal / Ajánlat Generátor
- **Mi ez:** Beírod az ügyfél igényét + a szolgáltatásaidat → AI generál professzionális ajánlatot, árazással, timeline-nal, PDF-ben.
- **Célpiac:** Freelancerek, ügynökségek, IT cégek (ti is használnátok!)
- **Miért jó:** Mindenki utálja az ajánlatírást. Egy jó AI ajánlat 80%-ban kész, csak finomítani kell.
- **Bevétel:** SaaS — $15/hó vagy per ajánlat
- **MVP idő:** 4–5 hét
- **Tech:** LLM + PDF generálás + template rendszer
- **Megjegyzés:** Ezt ti is használnátok a saját sales-hez — dogfooding!

#### 10. AI Weboldal Auditor
- **Mi ez:** Beírod az URL-t → AI átnézi a weboldalt: SEO, teljesítmény, accessibility, biztonsági problémák, UX javaslatok. Havi riport automatikusan.
- **Célpiac:** Marketing ügynökségek, webfejlesztők, KKV-k
- **Miért jó:** A Lighthouse/Semrush technikai, az AI emberi nyelven magyaráz és priorizál.
- **Bevétel:** Freemium — ingyenes 1 audit/hó, $19/hó korlátlan
- **MVP idő:** 5–6 hét
- **Tech:** Puppeteer/Playwright + Lighthouse + LLM elemzés

---

### C) BELSŐ HASZNÁLATRA + ÉRTÉKESÍTHETŐ

#### 11. AI Projekt Becslő
- **Mi ez:** Leírod a projektet természetes nyelven → AI lebontja feladatokra, becsül óraszámot, technológiát javasol, és generál Gantt-chartot.
- **Célpiac:** Szoftverfejlesztő cégek, PM-ek
- **Miért jó:** Minden dev cég rosszul becsül. Az AI legalább konzisztens baseline-t ad.
- **Bevétel:** SaaS — $29/hó/csapat
- **MVP idő:** 5–6 hét
- **Megjegyzés:** Ezt is ti használnátok először — dogfooding!

#### 12. Vibe Coding Platform
- **Mi ez:** No-code/low-code platform ahol AI-val írsz alkalmazást természetes nyelven. Gergő "vibe coding" tapasztalata alapján produktizálva.
- **Célpiac:** Nem-technikai vállalkozók, belső tooling csapatok
- **Miért jó:** A Replit Agent, Bolt.new trendje — de nincs magyar, és nincs enterprise-ra optimalizálva.
- **Bevétel:** SaaS — $29/hó (alap) / $99/hó (pro)
- **MVP idő:** 10–14 hét (komplexebb)
- **Kockázat:** Nagy verseny (Cursor, Replit, Bolt). Inkább niche-re fókuszálni.

---

### ÖSSZEHASONLÍTÓ MÁTRIX

| # | Termék | MVP idő | Induló költség | Havi bevétel potenciál | Verseny | Skálázhatóság | **SCORE** |
|---|--------|---------|---------------|----------------------|---------|---------------|-----------|
| 1 | Ügyfélszolg. Chatbot | 4-6 hét | Alacsony | ⭐⭐⭐ | Közepes | Magyar → Int. | ⭐⭐⭐⭐ |
| 2 | Számlaelemző | 6-8 hét | Alacsony | ⭐⭐⭐ | Alacsony | Magyar piac | ⭐⭐⭐ |
| 3 | Toborzás AI | 6-8 hét | Közepes | ⭐⭐⭐⭐ | Közepes | Magyar → Int. | ⭐⭐⭐ |
| 4 | Marketing Asszisztens | **3-4 hét** | **Legalacsonyabb** | ⭐⭐ | Magas | Magyar → Int. | ⭐⭐⭐ |
| 5 | Szerződéselemző | 5-7 hét | Alacsony | ⭐⭐⭐ | Alacsony | Magyar → Int. | ⭐⭐⭐⭐ |
| 6 | Code Review Bot | 6-8 hét | Alacsony | ⭐⭐⭐⭐⭐ | Közepes | **Globális** | ⭐⭐⭐⭐ |
| 7 | Meeting Notes AI | 8-10 hét | Közepes | ⭐⭐⭐⭐ | Magas | Globális | ⭐⭐⭐ |
| 8 | AI Form Builder | 6-8 hét | Alacsony | ⭐⭐⭐ | Közepes | Globális | ⭐⭐⭐ |
| 9 | Ajánlat Generátor | **4-5 hét** | **Legalacsonyabb** | ⭐⭐⭐ | Alacsony | Globális | ⭐⭐⭐⭐⭐ |
| 10 | Weboldal Auditor | 5-6 hét | Alacsony | ⭐⭐⭐ | Közepes | Globális | ⭐⭐⭐ |
| 11 | Projekt Becslő | 5-6 hét | Alacsony | ⭐⭐⭐ | Alacsony | Globális | ⭐⭐⭐⭐ |
| 12 | Vibe Code Platform | 10-14 hét | Magas | ⭐⭐⭐⭐⭐ | **Nagyon magas** | Globális | ⭐⭐ |

---

### TOP 3 JAVASLAT (induláshoz)

**1. helyezett: AI Ajánlat Generátor (#9)**
- Leggyorsabb MVP, ti is használjátok (dogfooding), alacsony verseny, globálisan skálázható
- Ez lenne az első termék amit ÉLŐben teszteltek saját ügyfeleken

**2. helyezett: AI Ügyfélszolgálati Chatbot (#1)**
- Hatalmas magyar KKV piac, recurring revenue, viszonylag egyszerű tech
- Ezt lehet értékesíteni a magyar KKV piacon személyes salessel is

**3. helyezett: Szerződéselemző (#5)**
- Leonárd Legitas tapasztalata óriási előny, alacsony verseny Magyarországon
- Ügyvédi irodák jól fizetnek SaaS-ért

**Alternatív stratégia:** A Code Review Bot (#6) a legjobb ha nemzetközi piacra akartok menni rögtön.

### Szoftvertermék értékelési szempontok
Minden ötletet érdemes az alábbiak alapján értékelni:

- **Piaci igény:** Van-e valós kereslet? Fizetnek-e érte?
- **Fejlesztési költség:** Mennyi idő/pénz az MVP?
- **Versenytársak:** Ki csinálja már? Miben lennénk jobbak?
- **Recurring revenue:** Lehet-e előfizetéses (SaaS)?
- **AI érték:** Hol ad hozzá az AI valódi értéket?
- **Időigény:** Mennyi idő alatt lenne piacra dobható MVP?
- **Csapat képessége:** Meg tudjuk-e csinálni a jelenlegi csapattal?

---

## 5. PÉNZÜGYEK

### Induló befektetés

| Tétel | Összeg | Ki fizeti | Megjegyzés |
|-------|--------|-----------|------------|
| **Cégalapítás (jogi)** | ~150.000–300.000 Ft | ? | Ügyvéd, cégbejegyzés |
| **Törzstőke** (Kft. min.) | 3.000.000 Ft | Alapítók | Felosztás: ? |
| **Domain + hosting** | ~50.000 Ft/év | ? | aiway.hu + szerver |
| **AI API költségek** | ~50.000–200.000 Ft/hó | Cég | OpenAI / Anthropic / egyéb |
| **Szoftver licenszek** | ? | Cég | IDE, design tool, stb. |
| **Marketing** | ? | Cég | Hirdetések, SEO |
| **Könyvelő** | ~30.000–80.000 Ft/hó | Cég | |
| **Gergő bére** | ? | Cég | |
| **Iroda** | ? | ? | Coworking / home office / virtuális székhely |
| **Összesen (havi fix)** | ? | | |
| **Összesen (induló)** | ? | | |

### Eldöntendő kérdések — Pénzügy
- [ ] Kezdeti tőke: ki mennyit rak bele? (Egyenlő vagy arányos?)
- [ ] Tőkebefektetés = tulajdoni arány, vagy külön kezelitek?
- [ ] Alapítói fizetés: kap-e valaki fizetést induláskor, vagy csak ha van bevétel?
- [ ] Profit elosztás: tulajdoni arány szerint, vagy más megállapodás?
- [ ] Mi történik, ha valaki ki akar szállni? (Vesting, buyout szabályok)
- [ ] Milyen bankszámlát nyittok? (Wise / OTP / Revolut Business?)
- [ ] Számlázó szoftver: számlázz.hu / billingo / szamlazz.hu?
- [ ] Könyvelő kiválasztása

---

## 6. JOGI & ADMINISZTRÁCIÓ

### Teendők lista

- [ ] Társasági szerződés elkészítése (ügyvéddel)
- [ ] Cégbejegyzés (e-cégeljárás)
- [ ] Adószám, bankszámla
- [ ] ÁSZF a aiway.hu-ra
- [ ] Adatkezelési tájékoztató (GDPR)
- [ ] Munkaszerződés Gergőnek (vagy megbízási szerződés)
- [ ] Alapítói megállapodás (shareholders' agreement) — **NAGYON FONTOS!**
  - Tulajdoni arányok
  - Döntéshozatali mechanizmus
  - Kilépési szabályok
  - Vesting
  - IP (szellemi tulajdon) a cégé
  - Versenytilalom
  - Vitarendezés
- [ ] IP-átruházás: minden fejlesztett szoftver a cégé (nem személyes)
- [ ] Üzleti terv (bankhoz, pályázathoz hasznos)

---

## 7. INFRASTRUKTÚRA & TECH STACK

### Eldöntendő
- [ ] Fő programozási nyelvek / keretrendszerek?
- [ ] Szerver / hosting: saját VPS, AWS, Hetzner?
- [ ] Kódtárolás: GitHub (org fiók), GitLab?
- [ ] Projektmenedzsment tool: Linear, Notion, Jira, Trello?
- [ ] Kommunikáció: Slack, Discord, Teams?
- [ ] Design: Figma?
- [ ] AI API-k: mely szolgáltatók? (Anthropic, OpenAI, stb.)
- [ ] CI/CD pipeline

---

## 8. ELSŐ 3 HÓNAP — MÉRFÖLDKÖVEK (javaslat)

| Hét | Teendő |
|-----|--------|
| **1–2. hét** | Cégalapítás, jogi papírok, bankszámla, alapítói megállapodás |
| **3–4. hét** | Tech stack véglegesítés, GitHub org, fejlesztői környezet |
| **5–6. hét** | Első szoftvertermék MVP specifikáció |
| **7–8. hét** | MVP fejlesztés elkezdése + első ügyfélkereső kampány |
| **9–12. hét** | MVP alpha verzió, első ügyfél próbák, feedback |

---

## 9. SZERVEZETI ÁBRA (javasolt)

```
                    ┌─────────────────┐
                    │   AIway Kft │
                    │   (4 alapító)   │
                    └────────┬────────┘
                             │
              ┌──────────────┼──────────────┐
              │              │              │
        ┌─────┴─────┐ ┌─────┴─────┐ ┌─────┴─────┐
        │  Üzlet /  │ │  Tech /   │ │ Operáció/ │
        │  Sales    │ │ Fejlesztés│ │ Pénzügy   │
        │    ?      │ │    ?      │ │    ?      │
        └───────────┘ └─────┬─────┘ └───────────┘
                            │
                    ┌───────┴───────┐
                    │   Leonárd     │
                    │ (dev vezető?) │
                    └───────┬───────┘
                            │
                    ┌───────┴───────┐
                    │    Gergő      │
                    │  (fejlesztő)  │
                    └───────────────┘
```

---

## 10. ÖSSZEFOGLALÓ — MIT KELL ELDÖNTENI ELŐSZÖR?

### 🔴 Kritikus (azonnal)
1. Tulajdoni arányok és tőkebefektetés
2. Alapítói megállapodás (ügyvéddel!)
3. Ki az ügyvezető?
4. Szerepkörök elosztása (ki mit csinál)

### 🟡 Fontos (1-2 héten belül)
5. Cégforma és cégalapítás indítása
6. Gergő munkaviszonya és kompenzációja
7. Első szoftvertermék kiválasztása
8. Költségvetés és pénzügyi terv
9. Tech stack és eszközök

### 🟢 Később is jó (1 hónapon belül)
10. Marketing stratégia
11. Részletes üzleti terv
12. Első ügyfél acquisition

---

*Ez egy élő dokumentum. A brainstorming eredményei és döntések alapján frissíteni kell.*
