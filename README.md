# ✒ PromptPad — rubrica personale di prompt

App web super leggera (un solo file HTML, nessuna installazione) per memorizzare,
e trovarsi, i prompt da usare in **ConFiUI** (e altrove).

## Cosa fa
- Inserimento di un prompt (titolo + testo + categoria)
- Salvataggio / modifica / cancellazione / duplicazione
- Ricerca full-text e filtro per categoria
- Copia negli appunti (`Ctrl+Invio` salva, `Ctrl+Maiusc+C` copia)
- Esporta / importa i prompt in formato JSON
- I dati restano **solo nel tuo browser** (localStorage): niente server, niente account.

## Come si usa
1. Apri il file `index.html` nel browser (doppio clic).
2. Clicca **+ Nuovo**, scrivi titolo / categoria / testo e premi **Salva** (o `Ctrl+Invio`).
3. Per riutilizzare un prompt: clicca sulla voce nella lista, poi **Copia**.
4. Per portarti i prompt su un altro computer: **Esporta** (JSON) e **Importa** sul nuovo posto.

## Le tue modifiche future
- Il codice è tutto in `index.html` (HTML + CSS + JS).
- Modifica il file, poi:
  `git add . && git commit -m "descrizione della modifica"`
  `git push`
- Vedi la sezione **Pubblica su GitHub** qui sotto.

## Pubblica su GitHub / condividila
1. Crea un repository vuoto su [github.com](https://github.com/new) (es. `promptpad`).
2. Dalla cartella `promptpad`:
   ```
   git remote add origin https://github.com/<tu-utente>/promptpad.git
   git push -u origin main
   ```
3. Per far sì che **tutti** possano scaricarla: scegli **Public** quando crei il repo.
   Chiunque può scaricarla dalla pagina del repo (`Code` → `Download ZIP`) o clonarla.
4. Opzionale: attiva GitHub Pages (Settings → Pages → Deploy from branch → `main` / root)
   per avere un link web acceso dell'app.

## Note
- Le categorie sono libere (anche ripetibili): ogni prompt può avere la sua.
- Il file è autosufficiente: non richiede server, framework né account.
- Ogni utente vede i propri prompt: non esiste sincronizzazione condivisa (è per design).
