# ⚡ Energy Dashboard

## Descrizione

**Energy Dashboard** è una semplice applicazione web che permette di **monitorare e analizzare i consumi energetici domestici** nel tempo.

L'applicazione consente di registrare ogni mese:

* costo della **luce**
* costo del **gas**
* **consumo elettrico (kWh)**
* **consumo gas (m³)**
* **produzione fotovoltaica non autoconsumata (KWh NO FV)**

Tutti i dati vengono salvati localmente nel browser tramite **LocalStorage**, quindi **non è necessario alcun server o database**.

La dashboard offre una visione immediata dei consumi attraverso riepiloghi, confronti tra anni e grafici.

---

# 🎯 Scopo della dashboard

Questa dashboard è stata creata per:

* monitorare **spese energetiche mensili**
* controllare **consumi elettrici e gas**
* analizzare **l'andamento annuale**
* confrontare **diversi anni tra loro**
* verificare la **differenza tra produzione fotovoltaica e consumo**

È particolarmente utile per chi possiede un **impianto fotovoltaico** e vuole capire:

* quanta energia viene consumata
* quanta energia viene prodotta
* se i consumi stanno aumentando o diminuendo nel tempo

---

# 📊 Funzionalità principali

## Inserimento dati mensili

Per ogni mese è possibile inserire:

* costo della luce (€)
* costo del gas (€)
* consumo elettrico (kWh)
* consumo gas (m³)
* produzione fotovoltaica non autoconsumata (kWh NO FV)

Ogni mese può essere salvato **una sola volta** per evitare duplicazioni.

---

## Riepilogo mensile

La dashboard mostra automaticamente:

* costo luce del mese
* costo gas del mese
* costo totale
* consumo kWh
* consumo gas m³
* differenza tra produzione FV e consumo

---

## Riepilogo annuale

Calcola automaticamente:

* totale spesa luce
* totale spesa gas
* spesa totale annua
* consumo elettrico totale
* consumo gas totale
* differenza tra produzione FV e consumi

---

## Confronto tra anni

Permette di confrontare due anni e visualizzare:

* differenza spesa energia
* differenza consumo kWh
* differenza costo gas

I colori indicano immediatamente:

* 🔴 aumento dei consumi
* 🟢 riduzione dei consumi

---

## Confronto dello stesso mese tra anni

È possibile confrontare ad esempio:

* Gennaio 2025 vs Gennaio 2026

per vedere le differenze di:

* costo luce
* consumo elettrico
* costo gas

---

## Grafici

La dashboard include due grafici:

### Andamento consumi elettrici

Grafico lineare dei **kWh mensili**

### Andamento costi energetici

Grafico a barre dei **costi mensili (luce + gas)**

---

## Backup dati

Per evitare la perdita dei dati è possibile:

### Esportare i dati

Scaricare un file JSON con tutti i dati salvati.

### Importare i dati

Ripristinare i dati caricando un file JSON precedentemente esportato.

---

# 💾 Archiviazione dati

I dati vengono salvati tramite:

* **LocalStorage del browser**

Questo significa che:

* i dati restano nel dispositivo
* non vengono inviati a server esterni
* l'app funziona **anche offline**

⚠️ Se si cancella la cache del browser i dati verranno eliminati.

Per sicurezza è consigliato usare la funzione **Esporta dati**.

---

# 📱 Compatibilità

La dashboard è progettata per funzionare su:

* computer desktop
* tablet
* smartphone
* iPhone (con layout responsive)

Può anche essere installata come **PWA (Progressive Web App)** per essere usata come una vera app.

---

# 🛠 Tecnologie utilizzate

* **HTML**
* **CSS**
* **JavaScript**
* **Chart.js** (per i grafici)
* **LocalStorage** (per il salvataggio dei dati)

Non sono necessari:

* backend
* database
* connessione internet

---

# 🚀 Come utilizzare la dashboard

1. Aprire il file `index.html` nel browser
2. Inserire i dati mensili
3. Salvare i dati
4. Analizzare riepiloghi e grafici
5. Utilizzare i confronti tra anni per monitorare i consumi

---

# 🔐 Privacy

Tutti i dati:

* rimangono **solo nel browser**
* non vengono inviati a servizi esterni
* non vengono raccolti o condivisi

---

# 👤 UiPY

Dashboard realizzata per il **monitoraggio domestico dei consumi energetici** e l'analisi della produzione fotovoltaica.
