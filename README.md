# 📚 Evoluce vývoje software: Waterfall → Agile → DevOps → DevSecOps

Tento přehled vysvětluje, jak se postupně vyvíjely metodiky vývoje software a proč vznikla každá další generace.

---

# 🌊 1. Waterfall (Vodopádový model)

> **"Nejdřív všechno naplánuj, potom krok za krokem realizuj."**

Waterfall vznikl v 70. letech a dlouhou dobu byl standardem při vývoji software.

Vývoj probíhá postupně – každá fáze musí být dokončena před zahájením další.

```text
Požadavky
      ↓
Analýza
      ↓
Návrh
      ↓
Vývoj
      ↓
Testování
      ↓
Nasazení
```

## Jak funguje?

Představ si stavbu domu.

1. Vytvoříš celý projekt.
2. Postavíš základy.
3. Postavíš zdi.
4. Uděláš střechu.
5. Nakonec zjistíš, že okno mělo být na druhé straně.

V této chvíli je změna velmi drahá.

Stejně funguje Waterfall.

---

## Výhody

- ✅ jednoduché plánování
- ✅ jasně rozdělené role
- ✅ vhodný pro projekty s pevně danými požadavky

## Nevýhody

- ❌ změny jsou drahé
- ❌ chyby se často objeví až na konci projektu
- ❌ pomalé vydávání nových verzí
- ❌ slabá komunikace mezi týmy

---

# 🚀 2. Agile

> **"Vyvíjej po malých částech a průběžně reaguj na změny."**

Waterfall ukázal, že dlouhé vývojové cykly nejsou efektivní.

Agile proto rozdělil projekt na malé části (iterace nebo sprinty).

Namísto jedné velké verze za rok vznikají malé pravidelné aktualizace.

Například:

- tento týden přihlášení,
- příští týden profil,
- další týden chat.

Každou novou funkci zákazník ihned vyzkouší a poskytne zpětnou vazbu.

```text
Malá změna
      ↓
Vývoj
      ↓
Testování
      ↓
Zpětná vazba
      ↓
Další změna
```

## Agile Manifesto

Agile staví na čtyřech základních hodnotách:

- 👥 Lidé a komunikace jsou důležitější než procesy.
- 💻 Funkční software je důležitější než rozsáhlá dokumentace.
- 🤝 Spolupráce se zákazníkem je důležitější než smlouvy.
- 🔄 Reakce na změny je důležitější než pevný plán.

## Self-organising Teams

Jedním z hlavních principů Agile jsou **self-organising teams**.

To znamená, že tým:

- rozhoduje společně,
- organizuje si práci,
- spolupracuje bez neustálého řízení shora.

---

## Výhody

- ✅ rychlé opravy
- ✅ časté vydávání verzí
- ✅ flexibilita
- ✅ lepší komunikace

## Nevýhody

Přesto stále existoval problém.

Vývojáři, testeři a administrátoři pracovali odděleně.

Developer například dokončil aplikaci a předal ji administrátorům.

Administrátor zjistil, že aplikace na serveru nefunguje.

Vznikaly konflikty mezi jednotlivými týmy.

---

# ⚙️ 3. DevOps

> **"Spoj vývoj, provoz a automatizaci."**

DevOps vznikl kolem roku 2008 jako reakce na nedostatečnou spolupráci mezi týmy.

Místo oddělených oddělení vzniká jeden společně spolupracující tým.

```text
Developer
      ↕
QA
      ↕
Operations
      ↕
System Administrator
```

Všichni sdílejí odpovědnost za celý životní cyklus aplikace.

---

## Hlavní principy DevOps

### 🤝 Collaboration

Vývojáři, testeři i administrátoři spolupracují.

---

### 🤖 Automation

Vše, co lze automatizovat, se automatizuje.

Například:

- build aplikace,
- testování,
- nasazení,
- vytváření serverů.

---

### 🔄 Continuous Integration / Continuous Deployment (CI/CD)

Po každé změně v kódu se automaticky spustí:

- build,
- testy,
- případně i nasazení.

Výhody:

- rychlejší nalezení chyb,
- menší změny,
- jednodušší rollback,
- stabilnější aplikace.

---

### ☁️ Infrastructure as Code (IaC)

Místo ručního vytváření serverů se infrastruktura zapisuje jako kód.

Například pomocí:

- Terraform
- Vagrant

Výhody:

- opakovatelnost,
- konzistence,
- méně lidských chyb.

---

### 📊 Monitoring

Nepřetržité sledování:

- výkonu,
- dostupnosti,
- logů,
- využití CPU a RAM,
- chyb aplikace.

---

## Výhody DevOps

- ✅ lepší spolupráce
- ✅ rychlejší vývoj
- ✅ automatizace
- ✅ menší počet chyb
- ✅ rychlejší nasazování verzí

---

# 🔐 4. DevSecOps

> **"Bezpečnost je součástí vývoje od prvního dne."**

DevOps výrazně zrychlil vývoj.

Objevil se ale nový problém.

Bezpečnost byla často řešena až před nasazením.

Pokud se našla kritická zranitelnost, musela se aplikace vrátit zpět do vývoje.

To znamenalo:

- zpoždění,
- vyšší náklady,
- více práce.

---

## Shift Left

Řešením je **Shift Left**.

Bezpečnost se přesouvá na úplný začátek vývoje.

```text
Plánování
      ↓
Vývoj
      ↓
Bezpečnostní testy
      ↓
Build
      ↓
Další testy
      ↓
Nasazení
      ↓
Monitoring
```

Bezpečnost je kontrolována během celého životního cyklu aplikace.

---

## DevSecOps znamená

- bezpečnost od začátku,
- automatické bezpečnostní testy,
- sdílenou odpovědnost všech členů týmu,
- průběžné hledání zranitelností.

---

## Výhody

- ✅ levnější opravy
- ✅ méně bezpečnostních incidentů
- ✅ vyšší kvalita aplikace
- ✅ bezpečnější nasazování

---

# 📈 Evoluce metodik

```text
Waterfall
     ↓
Agile
     ↓
DevOps
     ↓
DevSecOps
```

## Co každá metodika přinesla?

### 🌊 Waterfall

- pevný plán
- jednotlivé fáze
- minimum změn

↓

### 🚀 Agile

- malé iterace
- rychlá zpětná vazba
- flexibilita

↓

### ⚙️ DevOps

- spolupráce týmů
- automatizace
- CI/CD
- IaC
- Monitoring

↓

### 🔐 DevSecOps

- bezpečnost od začátku
- Shift Left
- bezpečnost jako společná odpovědnost
- automatické bezpečnostní kontroly

---

# 📋 Přehled

| Metodika | Hlavní myšlenka |
|-----------|-----------------|
| 🌊 Waterfall | Nejdřív vše naplánuj, potom realizuj. |
| 🚀 Agile | Vyvíjej po malých částech a reaguj na změny. |
| ⚙️ DevOps | Spoj vývoj, provoz a automatizaci. |
| 🔐 DevSecOps | Přidej bezpečnost od prvního řádku kódu. |

---

# 🧠 Jak si to zapamatovat

**Waterfall** 🏗️

➡️ „Dodrž plán.“

**Agile** 🚴

➡️ „Přizpůsobuj se změnám.“

**DevOps** ⚙️

➡️ „Spolupracuj a automatizuj.“

**DevSecOps** 🛡️

➡️ „Mysli na bezpečnost od samého začátku.“
