# JSON Schema

Questa cartella conterrà uno schema JSON separato per ogni messaggio
applicativo:

- misura di telemetria;
- richiesta di lettura;
- risposta con l'elenco delle misure;
- messaggio di errore.

Le buste cifrate avranno inoltre uno schema dedicato per verificare la
presenza di `session_id`, `ciphertext` e `tag`.
