# OpenCoopCloud

**Cloud cooperativo decentralizzato e open source.**

Metti a disposizione spazio disco (es. 100 GB) e in cambio ottieni uno spazio cloud personale (es. 75 GB) distribuito sui nodi di tutto il mondo. I file sono cifrati end‑to‑end, erasure‑coded e nessuno può leggerne il contenuto tranne te. La rete si autoregola: se smetti di condividere, il tuo spazio cloud viene ridotto automaticamente. Più partecipi (spazio e traffico), più tempo puoi restare offline senza penalità.

Basato su Substrate, libp2p, IPFS/BitTorrent e crittografia AES‑256‑GCM.

## Caratteristiche

- ✅ **Crittografia client‑side** – i tuoi file sono cifrati prima di uscire dal tuo dispositivo.
- ✅ **Erasure coding (4+2)** – ogni file viene diviso in 6 pezzi, ne bastano 4 per ricostruirlo. Massima resilienza.
- ✅ **Account basato su chiave privata** – nessuno può rubare la tua identità o i tuoi dati.
- ✅ **Condivisione sicura** – genera link temporanei protetti da password per condividere file.
- ✅ **Dashboard web** – monitora crediti, nodi, sincronizza cartelle, gestisci condivisioni e aggiornamenti.
- ✅ **Aggiornamenti multi‑versione** – installa nuove versioni senza perdere dati o identità, puoi tenere più versioni e rimuovere quelle vecchie.
- ✅ **Installazione semplificata** – script automatici per Linux, macOS e Windows.
- ✅ **Nessun controllo centrale** – la blockchain (Substrate) gestisce la contabilità e le penalità in modo distribuito.
- ✅ **Accesso da smartphone** – scannerizza un QR code per accedere alla tua dashboard dal telefono.

## Architettura

## Requisiti

- **Sistema operativo:** Linux (testato su Ubuntu 22.04), macOS, Windows (con WSL2 o PowerShell)
- **Dipendenze base:** Git, curl, Python 3.8+, pip, Node.js 16+, npm, Rust (ultima stabile)
- **Spazio disco:** almeno 10 GB liberi per compilazione e test

## Installazione rapida (automatica)

### Su Linux o macOS

```bash
git clone https://github.com/tuo-utente/opencoopcloud.git
cd opencoopcloud
chmod +x install.sh
./install.sh
