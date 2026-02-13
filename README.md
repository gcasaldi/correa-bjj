# Correa Brazilian JiuJitsu Accademy

Landing page semplice e curata, mobile-first.

## File principali

- `index.html`
- `styles.css`

## Link ufficiali integrati

- Instagram scuola: `https://www.instagram.com/correajiujitsu/`
- Facebook scuola: `https://www.facebook.com/correajiujitsu`
- Atleta: Giordano `@giordano_bjj`
- Atleta: Giulia Casaldi `@giuliacasal`

## Cosa personalizzare subito

- Link reali Facebook e Instagram
- Foto hero/storia/atleti con immagini ufficiali del team
- Nomi, gradi e titoli dei 4-5 atleti principali
- Email e recapiti finali

## Funzionalità incluse

- Hero con video background in loop (senza audio)
- Pulsante `Scrivici in Direct` verso Instagram
- Sezione `Live from the Mat` con wall Instagram (ultime 3 card)
- Doppio floating button: WhatsApp + Direct
- CTA `Prenota Lezione di Prova` presente in ogni sezione chiave

## Attivare feed Instagram automatico (ultimi post reali)

1. Crea un access token Instagram Basic Display (long-lived).
2. Apri `index.html` e cerca `const instagramToken = "";`.
3. Inserisci il token tra le virgolette.
4. Salva: il wall caricherà automaticamente gli ultimi 3 contenuti.

Se il token è vuoto o non valido, il sito mostra un fallback elegante che rimanda al profilo ufficiale.

## Avvio locale

Apri `index.html` nel browser oppure usa una preview locale dal tuo editor.
