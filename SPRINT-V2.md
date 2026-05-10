# Vince-Site v2 — Sprint-Plan

**Auftrag:** Mehr Tiefe, GitHub-Link prominent, Funding raus, bahnbrechende Vision sichtbar machen.

## Gelesen & Verstanden

1. ✅ `VISION-NORTH-STAR.md` — KI ist das Bedienkonzept, nicht ein Feature
2. ✅ `HELLO-VINCE.md` — Tonalität: selbstbewusst, technisch, kein Buzzword-BS
3. ✅ `PITCH-DECK.md` — Markt (27 Anbieter, alle schlecht), unser Differenzierer
4. ✅ `VISION-KI-FIRST.md` — 4 Modi (Ambient/Befund/Briefing/Documentation)
5. ✅ `VISION-COMPETITIVE.md` — 5 Killer-Features vs Dampsoft/CGM/Doctos
6. ✅ `VISION-PATIENT-FLOW.md` — Patientenreise als Choreografie (Sabine-Szene)
7. ✅ `VISION-ZAHNSTATUS-UI.md` — Bubble-Ring-Modell, 0 Klicks Befundaufnahme
8. ✅ `README.md` — 56 Module, 478 Tests, v0.50.5 Stand

## Bahnbrechende Ideen (meine Worte)

1. **KI steuert die Praxis** — nicht "Software mit KI", sondern "KI mit Software-Oberfläche"
2. **Multi-Device = ein System** — iPad, TV, Smartglass arbeiten als Einheit via EventBus
3. **Zero-UI Befundaufnahme** — Voice = Touch = Agent-Call, 0 Klicks für Routine
4. **Selbstlernende Praxis-KI** — jede Praxis entwickelt eigenen Stil (Few-Shot)
5. **Open Source + Lokal = DSGVO-by-Design** — Patientendaten verlassen Praxis NIE

## Was die aktuelle Site hat

- ✅ Sauberes Design (Admin-UI-aligned, Dark-Theme)
- ✅ Stats-Strip (56 Module, 650 Tests, €0 Lizenz)
- ✅ Portfolio-Screenshots (6 Live-Shots)
- ✅ Architektur-Cards (Compliance, Touch, KI, Open Source)
- ✅ Roadmap (Q2-Q4 2026, 2027 clinic)
- ✅ Funding-Sektion (NLnet €49.5k, Prototype Fund €47.5k)

## Was fehlt / was raus muss

- ❌ **Hero-Statement ist schwach** — "Die Praxis-Software, die der KI gehorcht" sagt nichts Konkretes
- ❌ **4 KI-Modi fehlen komplett** (Ambient/Befund/Briefing/Documentation)
- ❌ **Multi-Device-Choreografie fehlt** (iPad+TV+Smartglass)
- ❌ **Zero-UI Befundaufnahme** wird nicht erklärt
- ❌ **Wettbewerbs-Tabelle fehlt** (vs Dampsoft/Z1/Charly/Doctos)
- ❌ **GitHub-Link nicht prominent genug** (nur im Hero-CTA, kein Stats-Badge)
- ❌ **Funding-Sektion muss raus** (D00Dr will das nicht öffentlich)
- ❌ **Open Source ist nur Badge**, kein Verkaufsargument

## Neue Struktur (Top-to-Bottom)

### 1. Hero
**Bold Statement:** "openPlank ist nicht eine Praxis-Software mit KI. openPlank ist die KI, die die Praxis führt."
**Sub:** Ein Satz zum Konkretmachen: "Behandler spricht → KI dokumentiert → Display zeigt → Glasses blenden ein. Ein System, vier Geräte, null Klicks."
**CTAs:** [Auf GitHub ansehen] [Live-Demo buchen]

### 2. Stats-Strip (erweitert)
- 56 Module | 478 Tests | 350+ Endpoints
- **GitHub: 2.4k Commits** | **18 KI-Skills** | **100% Open Source**
- **Live-Badge:** GitHub-Stars via `api.github.com/repos/openplank-dev/openplank-dent`

### 3. Das Problem (Manifest aus PITCH-DECK)
**Eyebrow:** Das Problem
**Headline:** Software aus den 90ern, 27 Anbieter, alle gleich schlecht
**Body:** 3-4 Bullet Points:
- 30% der Behandlungszeit für Doku (MIT/Harvard 2024)
- 3+ Geräte im Behandlungsraum, keines spricht mit dem anderen
- KI = Buzzword (Transkription als Add-on, keine Integration)
- Vendor-Lock-in, Cloud-Zwang, DSGVO-Risiko

### 4. Die 4 KI-Modi (aus VISION-KI-FIRST)
**Eyebrow:** KI-First Architektur
**Headline:** Nicht ein Feature, sondern das Bedienkonzept
**4 Karten:**
1. **Ambient Mode** — KI hört im Hintergrund mit, zeigt kontextbezogene Infos
2. **Befund Mode** — KI erkennt gesprochene Befunde, markiert Zähne, 1-Tap-Bestätigung
3. **Briefing Mode** — Automatisches Patient-Briefing, Risiko-Score, priorisierte Empfehlungen
4. **Documentation Mode** — KI fasst zusammen, generiert §630f BGB-konformen Eintrag

### 5. Bedien-Vision (aus VISION-ZAHNSTATUS-UI)
**Eyebrow:** Zero-UI Befundaufnahme
**Headline:** "Nicht der Mensch lernt das Programm — das Programm lernt den Nutzer."
**Visualisierung:** 4 konzentrische Kreise (Bubble-Ring-Modell)
- **Ring 0:** Ruhe (Zahnschema)
- **Ring 1:** Fokus (Zahn antippen)
- **Ring 2:** Kontext (Befunde/Medien erscheinen)
- **Ring 3:** Aktion (malen/wählen)
- **Ring 4:** Weiterleitung (Auto-Advance)
**Stat:** Klassisch: 6 Klicks | openPlank: 2-3 Tipps

### 6. Multi-Device-Choreografie (aus VISION-PATIENT-FLOW)
**Eyebrow:** Multi-Device
**Headline:** Tablet, TV, Smartglass — ein System
**Body:** 
- Patient kommt → Empfang sieht Patient-Tab auf iPad
- Behandler fokussiert Zahn → TV zeigt Röntgen automatisch
- Smartglass zeigt Allergien im HUD
- **Pairing:** QR scannen → verbunden. Kein IT-Admin.
**Stat:** 1 EventBus | 5 Surfaces | Live-Sync via WebSocket

### 7. Compliance (deutscher Markt = Trumpf)
**Eyebrow:** Compliance
**Headline:** KZBV, BEMA/GOZ, GDPR, EU-AI-Act, MPBetreibV, StrlSchG
**6 Badges:**
- ✅ KZBV 8.2 (Idle-Lock)
- ✅ §630f BGB (Append-Only Treatments)
- ✅ DSGVO Art. 15+20 (Patient-Export)
- ✅ EU-AI-Act 50 (KI-Marker Audit)
- ✅ GOZ/BEMA (Katalog komplett)
- ✅ TI/KIM/ePA/eRezept (Telematik-ready)

### 8. Portfolio: Admin-UI Screenshots
**Eyebrow:** Portfolio
**Headline:** Das Admin-UI in Aktion
**6 Screenshots (bereits da):**
- Dashboard | Fleet | Devices | Pairing | Doctor | Login
**+ NEU:**
- Behandlung-Surface (wenn Screenshot verfügbar)
- Pairing-Flow (QR-Code-Ansicht)

### 9. Wettbewerb (aus VISION-COMPETITIVE)
**Eyebrow:** Wettbewerb
**Headline:** openPlank vs. Dampsoft/Z1/Charly/Doctos
**Vergleichstabelle:**
| Feature | Dampsoft | CGM Z1 | Doctos | openPlank |
|---------|----------|--------|--------|-----------|
| **KI-Modus** | Add-on | Button | Passiv | Proaktiv (Ambient+Predictive) |
| **Voice-First** | ❌ | ❌ | 🟡 (Transkription) | ✅ (Ambient+Touch-Parallel) |
| **Multi-Device** | ❌ | ❌ | ❌ | ✅ (EventBus, Live-Sync) |
| **Open Source** | ❌ | ❌ | ❌ | ✅ (AGPL-3.0) |
| **Cloud-Optional** | ❌ | ❌ | ❌ | ✅ (Lokal-First) |
| **DSGVO-by-Design** | 🟡 | 🟡 | ❌ | ✅ (Daten bleiben in Praxis) |
| **Selbstlernend** | ❌ | ❌ | ❌ | ✅ (Praxis-spezifisch) |

### 10. Roadmap (Q2/Q3/Q4 2026 + 2027)
**Eyebrow:** Roadmap
**Headline:** Was als nächstes kommt
**4 Karten (bereits da, leicht anpassen):**
- Q2 2026 — Konsolidierung (In Progress)
- Q3 2026 — Röntgen-KI (Geplant)
- Q4 2026 — Smart Calendar (Geplant)
- 2027 — openPlank clinic (Konzept)

### 11. Open Source & Community (NEU statt Funding)
**Eyebrow:** Open Source
**Headline:** Werde Teil der Bewegung
**Body:**
- **Lizenz:** AGPL-3.0 (frei nutzen, modifizieren, weitergeben)
- **Repository:** openplank-dev/openplank-dent (GitHub)
- **Live-Stats:** [GitHub-Stars] [Contributors] [Latest Release]
- **Warum Open Source?**
  - Kein Vendor-Lock-in
  - Praxen können Code prüfen (Datenschutz!)
  - Community-getrieben, erweiterbar
  - Wenn wir untergehen, geht die Praxis nicht mit
**CTA:** [Contribute on GitHub] [Join Discord]

### 12. Team
**Eyebrow:** Team
**Headline:** Who builds this
**3 Cards:**
- **D00Dr** — Lead-Dev, Architekt, Visionär | Bruder ist Zahnarzt (Demo-Praxis)
- **Klaus** (🦷) — KI-Assistent (Coding, Doku, Operations, 24/7)
- **Vince** — PR/BWL (TBD)

### 13. Footer
- GitHub | Lizenz MIT | Made in Germany / DSGVO-by-Design
- Kontakt | Newsletter | Discord

## Design-Änderungen

1. **Hero:** radial-gradient subtiler (nicht zu neon)
2. **Section-Breaks:** hairline-border zwischen Sektionen (wie Linear)
3. **Typografie:** h1/h2 in Inter Light, Mono für Code-Snippets
4. **Stats-Strip:** GitHub-Stars live via `fetch('https://api.github.com/repos/openplank-dev/openplank-dent')` → `.stargazers_count`
5. **Wettbewerbs-Tabelle:** auf Mobile als Cards (keine Tabelle)
6. **Kein Emoji-Overflow:** max. 🦷 als Favicon, sonst Icons/SVG

## Akzeptanzkriterien

- ✅ D00Dr sagt: "Das ist die richtige Geschichte."
- ✅ Vince versteht in 30s was bahnbrechend ist
- ✅ GitHub-Link prominent (Hero + Stats-Strip + Open Source Section)
- ✅ Kein Funding-Talk
- ✅ Echte Stats (GitHub API live)
- ✅ Portfolio-Screenshots eingebunden (bereits da)
- ✅ Wettbewerbs-Tabelle drin
- ✅ Mobile responsive

## Workflow

1. ✅ Vision-Docs gelesen
2. ⏳ Sprint-Plan geschrieben (JETZT)
3. ⏳ HTML komplett neu bauen
4. ⏳ features.json aktualisieren (alle 56 Module + Vision-Statements)
5. ⏳ GitHub-Stats live via API
6. ⏳ Commit + Push
7. ⏳ Verify: `curl https://openplank-dev.github.io/openplank-dent-features/`

## Nächster Schritt

HTML neu bauen, Sektion für Sektion.
