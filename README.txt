MUSA TAXI — demo PWA

Contenuti: index.html, manifest.json, sw.js.

INSTALLAZIONE SU IPHONE
1) Pubblica questi file su un hosting HTTPS (ad esempio GitHub Pages).
2) Apri l'URL pubblicato in Safari su iPhone.
3) Tocca Condividi → Aggiungi alla schermata Home.
Il file ZIP non si installa direttamente come app iOS e non è un'app App Store nativa.

PREZZI CARBURANTE
La demo tenta una ricerca tramite API pubblica di terze parti basata su dati open data MIMIT, filtrando i risultati Q8 e usando la media dei prezzi trovati. L'endpoint può cambiare/essere indisponibile e non garantisce un filtro Q8 perfetto. La ricerca è effettuata all'apertura/pressione del pulsante, non con un processo garantito in background ogni giorno.
Per aggiornamento giornaliero garantito, notifiche o robustezza production serve un backend schedulato, e una fonte/API stabile con termini d'uso/CORS verificati.

VEICOLO
Consumo preimpostato 7,5 L/100 km come valore provvisorio modificabile. Verifica il consumo reale della tua specifica Musa (motore/versione e guida urbana) e sostituisci il valore. Il rapporto kW/t non determina da solo il consumo.

CALCOLO
Prezzo = costo carburante + guadagno impostato + supplemento per passeggeri oltre il primo + 5 € se il margine pre-supplemento è inferiore a 5 €, arrotondato per eccesso all'euro.
Questa demo è un preventivatore indicativo, non una tariffa taxi ufficiale.
