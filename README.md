# quaderno-aggiornamenti

Solo gli APK firmati dell'app Quaderno e i file dei canali che l'app legge una volta al giorno:

- `stabile.txt`: il tablet di lei
- `prova.txt`: il Pad di Davide, mai più indietro di stabile
- `collaudo.txt`: gli emulatori, APK di debug

Ogni file dice `versionCode`, `versionName`, `apk` (l'asset della release) e `sha256`. Si scrivono con
`scripts/rilascia.sh` del repo dell'app, non a mano. Il codice sta altrove.
