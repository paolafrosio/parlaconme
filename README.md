# 🌍 ParlaConMe - Traduttore Live Multilingue per la Scuola (CPIA)

**ParlaConMe** è una Web App Open Source sviluppata per facilitare la comunicazione bilingue e multilingue nelle classi ad alta aderenza migratoria (es. CPIA - Centri Provinciali per l'Istruzione degli Adulti). 

Consente al docente di parlare o scrivere in italiano e di trasmettere contemporaneamente le traduzioni in tempo reale sugli smartphone o PC degli studenti, ognuno nella propria lingua madre.

---

## ✨ Funzionalità Principali

* 🎙️ **Dettato Vocale Live (Docente):** Riconoscimento vocale avanzato con supporto alla punteggiatura automatica.
* 🌐 **Traduzione Multilingue Istantanea:** Supporta oltre 15 lingue (Arabo, Albanese, Bengalese, Cinese, Farsi, Francese, Inglese, Pashto, Spagnolo, Ucraino, Urdu e molte altre).
* 📱 **Connessione tramite QR Code o PIN:** Gli studenti possono collegarsi istantaneamente inquadrando il QR Code sulla LIM o inserendo il codice stanza, senza registrarsi.
* 🔊 **Sintesi Vocale (Text-to-Speech) integrata:** Gli studenti possono ascoltare la pronuncia corretta in italiano o nella loro lingua madre a velocità normale o rallentata (con controllo Avvia / Interrompi).
* 🔄 **Modalità Studente ➔ Docente:** Permette allo studente di parlare nella propria lingua madre per inviare al docente la traduzione in italiano.
* 🌙 **Tema Scuro (Dark Mode) & Accessibilità:** Interfaccia responsive con supporto per la Dark Mode e ingrandimento del testo al volo (Zoom A-/A+).
* 🖨️ **Esportazione Schede Didattiche:** Generazione automatica di PDF stampabili e file di testo (.TXT) con la cronologia delle frasi spiegate in lezione.

---

## 🛠️ Tecnologie Utilizzate

* **HTML5 / CSS3 / JavaScript (Vanilla JS):** Interfaccia ultra-leggera senza framework pesanti.
* **Web Speech API:** Per il riconoscimento vocale e la sintesi vocale nativa del browser.
* **PeerJS (WebRTC):** Per la comunicazione P2P in tempo reale a bassissima latenza tra docente e studenti.
* **Google Translate API (Free endpoint):** Per la traduzione istantanea del testo.
* **QRCode.js:** Per la generazione automatica del QR Code d'aula.

---

## 🚀 Come Utilizzarlo

### Per il Docente:
1. Apri la Web App dal browser (PC o LIM).
2. Premi il pulsante **📱 Trasmetti** per visualizzare il QR Code e il PIN della lezione.
3. Inizia a parlare o a digitare nel box dell'Italiano.

### Per lo Studente:
1. Inquadra il QR Code con lo smartphone oppure apri il link della stanza.
2. Seleziona la tua lingua dal menu a tendina.
3. Leggi e ascolta in tempo reale la traduzione delle spiegazioni dell'insegnante.

---

## 📄 Licenza

Questo progetto è rilasciato sotto licenza **MIT**. Libero di essere utilizzato, modificato e distribuito per fini didattici ed educativi.
