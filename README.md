# HybridDrive Tracker

PWA per tracciare consumi di auto ibride, plug-in ed elettriche. Calcola km/L, km/kWh, €/100km, CO2 risparmiata e l'incidenza delle ricariche sulla bolletta di casa.

### ✨ Funzionalità
- **Multi-auto**: gestisci ibrida, plug-in, elettrica, benzina in un'unica app
- **Doppio tracking**: rifornimenti benzina/diesel + ricariche elettriche kWh
- **Bollette casa**: calcola il costo reale €/kWh e quanto l'auto incide in bolletta
- **Confronti**: grafici €/100km per capire quale auto conviene davvero
- **PWA installabile**: funziona offline, icona in home su iOS/Android
- **Export CSV**: porta i dati su Excel/Fogli Google
- **100% privacy**: tutti i dati restano sul telefono in localStorage

### 🚀 Prova online
1. Vai su `https://[TUO-USERNAME-GITHUB].github.io/[NOME-REPO]`
2. Da Safari/Chrome → Condividi → "Aggiungi alla schermata Home"

### 📱 Installazione da GitHub Pages
1. Fai fork o scarica questo repo
2. Carica `index.html` nella root
3. Repo Settings → Pages → Deploy from branch `main` / root
4. Fine. L'app è online

### 🤖 Da PWA ad Android
Il codice è pronto per Capacitor. Istruzioni commentate in fondo a `index.html`:
```bash
npm init -y
npm i @capacitor/core @capacitor/cli
npx cap init HybridDrive com.tuonome.hybriddrive
npx cap add android
npx cap sync
npx cap open android
```

### ⚖️ Licenza
Questo progetto è rilasciato sotto **Licenza Personalizzata - No uso commerciale**. 
Vedi file `LICENSE` per i dettagli. In breve: puoi usare, modificare e condividere per uso personale/non-profit. Per qualsiasi uso commerciale serve autorizzazione scritta dell'autore.

### 🛠️ Tech
HTML singolo, Tailwind CSS via CDN, Chart.js 4.4 via CDN, Vanilla JS ES6. No build, no backend, no tracking.

### 📬 Contatti
Per richieste commerciali o collaborazioni: [INSERISCI-LA-TUA-EMAIL]

---
Fatto con ❤️ per ottimizzare la guida ibrida ed elettrica
