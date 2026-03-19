# ELITEQUEST // SHADOW DECK & MISSION EDITOR PRO 🚀

Benvenuto in **EliteQuest**, un sistema avanzato di overlay e gestione missioni personalizzate per piloti spaziali. 
Progettato per espandere l'esperienza di gioco tramite campagne narrative ("Shadow Deck"), il software legge in tempo reale gli eventi del tuo diario di bordo (Journal) e ti guida attraverso obiettivi complessi con un HUD in sovrimpressione e avvisi vocali (TTS).

---

## 🌟 Funzionalità Principali

* **HUD Overlay Dinamico:** Un'interfaccia trasparente in-game (disponibile a Sinistra o al Centro dello schermo) che mostra i tuoi obiettivi attuali, i progressi e le notifiche di completamento.
* **Gestione Campagne:** Gioca missioni indipendenti o affronta intere campagne narrative strutturate in capitoli, con salvataggio persistente dei progressi.
* **Pannello di Controllo Integrato:** Regola istantaneamente il volume della Voce di bordo (TTS), degli effetti sonori (Bip/Wav) e la posizione del radar senza dover uscire dal gioco.
* **Mission Editor Pro:** Un software stand-alone (`EQEditor.py`) dotato di interfaccia grafica (GUI) intuitiva per creare le tue missioni. Non serve saper programmare: aggiungi lore, obiettivi, contatori e fail-state con pochi clic ed esportali in JSON.
* **Audio e TTS:** Briefing letti dalla voce di sistema e segnali acustici per ogni fase della missione superata.
* **Dev Mode & Telemetria:** Terminale integrato per sviluppatori per il debug in tempo reale del Journal e degli eventi di gioco.

---

## 🚀 Come Iniziare (Per i Giocatori)

1.  Scarica l'ultima versione compressa dalla sezione **Releases** di questa pagina.
2.  Estrai la cartella sul tuo PC in una posizione a tua scelta.
3.  Avvia l'eseguibile principale (`EliteQuest.exe` o esegui `main.py` se hai i sorgenti).
4.  Usa l'icona dell'ingranaggio ⚙️ per calibrare l'HUD e il volume della voce prima di decollare.
5.  Seleziona una missione dall'archivio e premi **INIZIA SEQUENZA OPERATIVA**.

---

## 📝 Come Creare Missioni (Per i Creatori)

1.  Avvia `EQEditor.py` (o il relativo eseguibile).
2.  Compila i Metadata (Titolo, Difficoltà, Ricompensa).
3.  Usa il menu a tendina per aggiungere "Eventi" di gioco (es. Abbattimento, Salto, Scansione).
4.  Esporta la missione e salvala nella cartella `/missions/` dell'applicazione principale.

---

## ⚠️ Requisiti di Sistema (Per Sviluppatori)

Se stai scaricando il codice sorgente per modificarlo o compilarlo da zero, assicurati di avere installato Python 3.x e le seguenti librerie:
* `PyQt6` (Per le interfacce grafiche)
* `pywin32` (Per il motore TTS SAPI.SpVoice su Windows)

---

> **© 2026 Dusker Dark. ALL RIGHTS RESERVED.** > *Sviluppato con precisione chirurgica per veri Comandanti. Unauthorized copying of source code is prohibited.*
