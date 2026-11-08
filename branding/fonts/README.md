# Font del brand

- **Inter** (testi): `inter/Inter-Regular.ttf`, `inter/Inter-Bold.ttf`
- **Merriweather** (titoli): `merriweather/Merriweather-Bold.ttf`

I file `.ttf` con il nome del peso sono statici e sono quelli da installare su Windows, macOS e Linux
(PowerPoint non installa i font variabili). I file `[...]` sono i font variabili originali, per il web
e per generare altri pesi. Licenza OFL 1.1 (vedi `OFL.txt` nelle cartelle).

## Presentazioni

I file `.pptx` in `docs/` **non incorporano** i font: installa prima i tre file statici qui sopra
(tasto destro, *Installa per tutti gli utenti*), poi chiudi e riapri PowerPoint. Senza i font il testo
passa a un carattere di ripiego e l'impaginazione cambia; il `.pdf` accanto mostra il risultato corretto.
