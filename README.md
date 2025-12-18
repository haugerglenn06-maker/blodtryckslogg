# 🩺 Blodtrycks Logg

**Blodtrycks Logg** är en enkel, snabb och mobilanpassad webbapp (PWA) för att logga blodtryck och puls lokalt på din enhet.  
Appen är byggd för personligt bruk, fungerar offline och lagrar all data lokalt i webbläsaren.

👉 **Ingen inloggning. Ingen backend. Ingen molnlagring.**

---

## ✨ Funktioner

- 📅 Logga blodtryck och puls med manuellt klockslag
- 🗂 Gruppering per dag (nyaste dagen överst)
- ⏱ Sortering av tider inom varje dag
- 🎨 Färgmarkering av värden över rekommenderade gränser
- 📊 Filtrering mellan datumintervall
- 📄 Export till **PDF** (mobil & desktop)
- 📑 Export till **CSV**
- 💾 Säkerhetskopiera data till JSON-fil
- 📱 Mobiloptimerad (Samsung / iPhone / desktop)
- 📶 Fungerar offline (PWA)
- 🖨 Utskriftsvänlig layout
- 🔔 Haptic feedback + visuell bekräftelse vid sparande

---

## 📱 PWA – Installera som app

Appen kan installeras som en **Progressive Web App**:

### Android / Samsung
1. Öppna appen i Chrome
2. Välj **“Lägg till på startskärmen”**
3. Appen fungerar nu som en vanlig mobilapp

### Desktop
- Chrome / Edge → Installera via adressfältet

---

## 🔐 Integritet & säkerhet

- All data lagras **endast lokalt** i din webbläsare (`localStorage`)
- Ingen data skickas till internet
- GitHub Pages används **endast för att leverera koden**
- Varje användare har sin egen isolerade data

👉 Detta gör appen lämplig för personlig hälsologgning.

---

## 📤 Export & backup

### Exportera PDF
- Skapar en **riktig PDF-fil**
- Mobil: dela → spara, mejla eller skriv ut
- Desktop: ladda ner PDF

### Exportera CSV
- Öppnas i Excel, Google Sheets m.fl.

### Säkerhetskopiera
- Exporterar all data som JSON
- Kan användas för framtida återställning

---

## ⚠️ Rekommenderade gränsvärden

Färgmarkering används för att indikera värden över rekommenderade nivåer:

| Värde | Gräns |
|---|---|
| Systoliskt | ≥ 140 |
| Diastoliskt | ≥ 90 |
| Puls | ≥ 100 |

> Appen ersätter **inte** medicinsk rådgivning.

---

## 🛠 Teknik

- HTML5
- CSS3 (mobil-first)
- Vanilla JavaScript
- localStorage
- jsPDF (lokal fil)
- Progressive Web App (PWA)
- GitHub Pages

Ingen extern backend eller databas används.

---

## 🚀 Kör lokalt

```bash
git clone https://github.com/haugerglenn06-maker/blodtryckslogg.git
cd blodtryckslogg

## 📌 Versionshistorik
Se [CHANGELOG.md](CHANGELOG.md)
