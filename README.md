# Firstshore clock

Timer pubblico per il mondo Firstshore. Contiene solo la chiamata periodica al sito: codice della simulazione e chiavi AI restano privati.

Il workflow viene eseguito circa ogni cinque minuti; GitHub puo ritardare le esecuzioni. Ogni chiamata aggiorna soltanto il tempo realmente trascorso. Gli errori fanno fallire il controllo e vengono registrati in Actions.

Secret richiesto: WORLD_HEARTBEAT_SECRET, limitato all'endpoint del timer. Nessuna chiave OpenAI e presente in questo repository.
