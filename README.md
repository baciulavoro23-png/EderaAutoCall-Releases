# EderaAutoCall

Distribuzione ufficiale e aggiornamenti automatici di EderaAutoCall.

## Installazione corretta

1. Apri la [versione più recente](https://github.com/baciulavoro23-png/EderaAutoCall-Releases/releases/latest).
2. Nella sezione **Assets**, scarica `Installa-EderaAutoCall-VERSIONE.exe` (per la 2.3.1: `Installa-EderaAutoCall-2.3.1.exe`).
3. Esegui l’installer e usa il collegamento **EderaAutoCall** creato sul Desktop.

> Non scaricare **Code → Download ZIP** o **Source code**: contengono solo i file di distribuzione del repository, non l’installer. Lo ZIP `EderaAutoCall-VERSIONE.zip` negli Assets è invece il pacchetto tecnico dell’aggiornamento: non avviare direttamente l’EXE estratto perché non passa dal launcher.

## Aggiornamenti

Aprendo EderaAutoCall dal collegamento installato, il launcher controlla la presenza di nuove versioni. Quando ne trova una mostra le novità e permette di scegliere **Riavvia e aggiorna** oppure **Ricordamelo più tardi**. Il rinvio dura quattro ore; chiudere semplicemente l’avviso non registra il rinvio.

Chi ha usato in precedenza l’EXE estratto dallo ZIP deve eseguire una sola volta l’installer della versione più recente. L’aggiornamento conserva dati e impostazioni dell’installazione; l’accesso ricordato resta valido finché non scade o viene revocato.

Se un aggiornamento non compare, chiudi l’app e riaprila dal collegamento installato, verifica la connessione a GitHub e l’eventuale rinvio scelto. È sempre disponibile l’installer nella pagina della versione più recente. Non è necessario disattivare le protezioni di Windows.

## Novità della 2.3.1

Barre di scorrimento sottili e senza frecce in tutto il Calendario e nelle finestre dei promemoria, con colori coordinati al tema. Il menu laterale mostra l’icona calendario; il nome del cliente nell’elenco è in grassetto e usa un colore più acceso con contrasto adattato alla selezione. Selezione, rotella, tastiera, doppio clic, comando Elimina e permessi restano disponibili.

## Novità della 2.3.0

Calendario condiviso con promemoria, assegnazioni fra colleghi e collegamenti Easy; notifiche discrete di Eddy; Personalizza con 17 avatar pubblici indipendenti dal tema e suono MP3. Con Autocall completamente chiuso gli avvisi vengono recuperati alla riapertura. Chi usa il precedente Ricordami può dover collegare Agenda una prima volta con la propria password Autocall. La gestione degli account richiede il client aggiornato.

## Call Bridge mobile

L'APK Android **EderaCallBridge 1.1.5** è incluso nella [release 2.3.1](https://github.com/baciulavoro23-png/EderaAutoCall-Releases/releases/tag/v2.3.1), con gli stessi byte della 2.3.0. Mantiene la stessa identità e firma della 1.1.4: installarlo sopra la precedente, senza disinstallare l'app. Il collaudo dell'aggiornamento su un telefono fisico resta da completare.

Il Bridge iPhone aggiunto alla Home si aggiorna dal Portal: chiudere e riaprire la pagina per caricare i nuovi file. Grafica, logo e Eddy seguono le preferenze di Autocall. Il server supporta il nuovo canale di risveglio Android; il polling rimane disponibile come riserva.

## Tema ANTO

Nella normale versione di Autocall inserire il codice **ANTO** dal menu segreto di Eddy. Il tema scaricabile rimane nascosto fino allo sblocco del singolo account. Scegliere un avatar in Personalizza non sblocca il tema corrispondente.

Le precedenti build separate AntoPistolero-Call restano nel [repository storico](https://github.com/baciulavoro23-png/AntoPistolero-Call-Releases/releases/latest). I nuovi aggiornamenti e il tema ANTO sono distribuiti nella versione standard; nessuna nuova edizione separata viene pubblicata.

## Verifiche della distribuzione

Installer, ZIP e APK riscaricati e confrontati tramite SHA-256. Aggiornamento Windows dalla 2.3.0 alla 2.3.1 verificato con dati sintetici e conservazione di account, appuntamenti condivisi, modifiche in attesa di sincronizzazione, promemoria, preferenze e file di associazione Bridge. Nessuna chiamata reale è stata avviata durante i collaudi. I tempi telefonici e il comportamento sui dispositivi fisici restano da verificare.
