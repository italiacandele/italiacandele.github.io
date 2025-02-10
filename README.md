# Readme

## Git commands

```bash
git pull origin main
git add .
git commit -m "Edit"
git push -u origin main
```
## Jekyll commands
```bash
bundle exec jekyll serve
```


## TO DO

- ✅ Implementazione di jekyll in locale, connessione a git motaggio prima 'impalcatura' del progetto
- ✅ Creare heroes con immagine bg caricata in html no in css
- ✅ implementare jekyll_picture_tag
- ✅ SEO strutturare la seo del sito, attenzione ai meta tags e alle immagini di anteprima '_incudes/seo.html'
- ✅ Completare la clonazione dei contenuti del sito
- 🔜 Editing di menu e footer per rispecchiare l'originale --> quasi fatto
- 🔜 analizzare e creare lo script di deploy [https://kiwi.italiacandele.com/antonio/jekyll-ItaliaCandele/wiki/script-di-deploy](wiki)
- 🔜 Ideare uno script per effettuare il minify del sito di produzione [https://kiwi.italiacandele.com/antonio/jekyll-ItaliaCandele/wiki/script-di-deploy](wiki)

### 1. Verifica se sei nella directory corretta
Assicurati di essere nella directory del progetto dove intendi configurare il repository Git. Usa il comando:
```bash
pwd
```
Questo comando mostrerà il percorso corrente. Assicurati che sia il percorso del tuo progetto.

### 2. Inizializza un repository Git
Se non hai ancora inizializzato Git nella directory, fallo con:
```bash
git init
```
Questo creerà una directory `.git` nel tuo progetto, rendendolo un repository Git.

### 3. Aggiungi il remote
Dopo aver inizializzato il repository, aggiungi il remote:
```bash
git remote add origin https://kiwi.italiacandele.com/antonio/jekyll-ItaliaCandele.git
```

### 4. Conferma l'operazione
Per verificare che il remote sia stato aggiunto correttamente, usa:
```bash
git remote -v
```
Dovresti vedere qualcosa come:
```
origin  https://kiwi.italiacandele.com/antonio/jekyll-ItaliaCandele.git (fetch)
origin  https://kiwi.italiacandele.com/antonio/jekyll-ItaliaCandele.git (push)
```

### 5. Aggiungi file e fai il primo commit (se necessario)
Se è la prima configurazione del repository:
```bash
git add .
git commit -m "Initial commit"
```

### 6. Pusha al repository remoto
Infine, puoi caricare i tuoi file al repository remoto con:
```bash
git push -u origin main
```
### 7. recupera modifiche dal repository remoto

```bash
git pull origin main
```

Sostituisci `main` con il nome del branch principale se utilizzi un altro branch (es. `master`).

Stimare i costi di produzione, packaging e marketing per un e-commerce di candele profumate in cera di soia richiede di considerare diverse variabili. Ti fornirò una stima basata su costi medi e un prezzo di vendita suggerito per mantenere una buona marginalità.

1. Costi di Produzione per Candela

(Stima per una candela da 200g in una forma creativa)

Voce	Costo stimato (€ per unità)
Cera di soia (200g)	1,00 – 1,50
Olio essenziale/profumo	0,50 – 1,50
Stoppino in cotone	0,20 – 0,50
Coloranti (opzionale)	0,10 – 0,30
Stampo in silicone (ammortizzato)	0,30 – 1,00
Lavorazione e manodopera	1,00 – 2,00
Totale produzione	3,10 – 6,80

2. Costi di Packaging per Candela

(Considerando un packaging curato per e-commerce)

Voce	Costo stimato (€ per unità)
Contenitore (vetro, latta, o plastica riciclata)	0,80 – 2,00
Etichetta personalizzata	0,30 – 1,00
Scatola regalo/cartone	0,50 – 1,50
Filler (paglia, carta, ecc.)	0,20 – 0,50
Totale packaging	1,80 – 5,00

3. Costi di Marketing e Logistica

(Distribuiti su un volume di produzione)

Voce	Costo stimato (€ per unità)
Fotografia prodotto	0,30 – 1,00
Pubblicità online (Instagram, Google Ads)	2,00 – 5,00
Spedizione media (passata al cliente o inclusa)	3,00 – 7,00
Piattaforma e-commerce (commissioni, hosting)	1,00 – 3,00
Totale marketing/logistica	6,30 – 16,00

4. Prezzo Finale e Margine di Vendita

Costo totale stimato per candela
	•	Minimo: 11,20 €
	•	Massimo: 27,80 €

Prezzo di vendita suggerito
	•	Con un margine del 50%: 16,80 – 41,70 €
	•	Con un margine del 100%: 22,40 – 55,60 €

Prezzo medio consigliato: 25 – 40 € per candela, in base alla qualità percepita e al posizionamento del brand.

Se punti a un mercato premium con packaging di lusso e profumi pregiati, il prezzo può arrivare anche a 50-60 € a candela.

Strategia di Prezzo e Consigli
	1.	Offri opzioni bundle: Es. set da 3 candele a 70-90 € per aumentare il valore medio dell’ordine.
	2.	Posizionamento Premium: Foto professionali, storytelling del brand e ingredienti di qualità aiutano a giustificare prezzi più alti.
	3.	Strategia di spedizione: Considera la spedizione gratuita sopra un certo importo (es. sopra i 50 €).
	4.	Cross-selling: Offri accessori (accendini eleganti, piattini decorativi, ecc.) per aumentare il carrello medio.

Ti servono dati più precisi in base a un fornitore specifico?
