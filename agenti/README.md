# Agenti AI del Dipartimento

Questa cartella contiene i **prompt e le configurazioni** per gli agenti AI
usati dal dipartimento nella pianificazione didattica.

Gli agenti non sostituiscono i docenti: li **affiancano** nelle attività ripetitive
o che richiedono una visione di insieme difficile da costruire manualmente.

---

## Agenti disponibili

| File | Agente | Uso principale |
|------|--------|---------------|
| [agente-curricolo.md](./agente-curricolo.md) | Agente Curricolo | Progettare unità di apprendimento, verificare copertura disciplinare |
| [agente-progettazione.md](./agente-progettazione.md) | Agente Progettazione | Strutturare nuovi progetti didattici, stimare tempi |
| [agente-valutazione.md](./agente-valutazione.md) | Agente Valutazione | Generare rubriche, feedback su elaborati, auto-valutazione |

---

## Come usare gli agenti

1. Apri il file dell'agente che vuoi usare
2. Copia il **System Prompt** nella sezione `[SYSTEM PROMPT]`
3. Incolla il prompt in ChatGPT, Claude, o qualsiasi LLM disponibile
4. Usa le istruzioni nella sezione `[COME USARLO]` per formulare la tua richiesta

---

## Principi di uso degli agenti

- **Verifica sempre** l'output dell'agente prima di usarlo
- **Modifica** ciò che non si adatta al tuo contesto specifico
- **Documenta** come hai usato l'agente e cosa hai modificato
- **Condividi** i prompt migliorati aprendo una PR su questo repository

---

## Workflow consigliato per i docenti

```
1. Identifica il bisogno (progettare un UDA? Creare una rubrica? Strutturare un progetto?)
2. Scegli l'agente appropriato
3. Usa il prompt con il tuo LLM preferito
4. Rivedi e adatta l'output
5. Salva il risultato nel repository (nella cartella appropriata)
6. Condividi con il dipartimento
```

---

## Modelli LLM consigliati

| LLM | Accesso | Punti di forza |
|-----|---------|---------------|
| **ChatGPT (GPT-4o)** | chat.openai.com | Equilibrato, ottimo italiano |
| **Claude (Anthropic)** | claude.ai | Eccellente per testi lunghi, ragionamento |
| **Gemini (Google)** | gemini.google.com | Integrazione Google Workspace |
| **Copilot (Microsoft)** | copilot.microsoft.com | Integrato con Microsoft 365, citazioni web |
| **Ollama (locale)** | ollama.ai | Privacy totale, nessun dato inviato online |

---

## Aggiungere un nuovo agente

1. Crea un nuovo file `agente-NomeFunzione.md`
2. Segui la struttura degli agenti esistenti
3. Testa il prompt con almeno 3 richieste diverse
4. Documenta i risultati ottenuti
5. Apri una PR per revisione collegiale
