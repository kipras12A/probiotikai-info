# Baltic Probiotics – automatiniai laiškai

Galutiniai 7 lietuviški laiškų maketai, eksportuoti 2026-10-16.

| Serija | Laiškas | HTML su viešais paveikslėliais | HTML su vietiniais paveikslėliais |
|---|---|---|---|
| Welcome | 1 | [email.html](welcome-1/email.html) | [newsletter.html](welcome-1/newsletter.html) |
| Welcome | 2 | [email.html](welcome-2/email.html) | [newsletter.html](welcome-2/newsletter.html) |
| Welcome | 3 | [email.html](welcome-3/email.html) | [newsletter.html](welcome-3/newsletter.html) |
| Winback | 1 | [email.html](winback-1/email.html) | [newsletter.html](winback-1/newsletter.html) |
| Winback | 2 | [email.html](winback-2/email.html) | [newsletter.html](winback-2/newsletter.html) |
| Atsiliepimo prašymas | 1 | [email.html](review/email.html) | [newsletter.html](review/newsletter.html) |
| Padėka po pirmo pirkimo, gavus prekę | 1 | [email.html](post-purchase/email.html) | [newsletter.html](post-purchase/newsletter.html) |

## Failų naudojimas

- `newsletter.html` atidaromas naršyklėje kartu su tame pačiame aplanke esančiu `assets` katalogu. Atsisiųskite visą saugyklą, kad veiktų vietiniai paveikslėliai.
- `email.html` naudoja absoliučias viešas šios saugyklos `raw.githubusercontent.com` paveikslėlių nuorodas; tinka kaip HTML importo pagrindas. Neištrinkite ir nepervadinkite naudojamų assetų.
- `newsletter.txt` – tekstinė laiško versija.
- GitHub failo puslapis rodo HTML kodą; peržiūrai atsisiųskite ir atidarykite HTML naršyklėje.

## Prieš paleidžiant siuntimą

- `{{unsubscribe_url}}` pakeisti platformos veikiančia prenumeratos atsisakymo žyma.
- Atsiliepimo laiške `{{review_url}}` pakeisti tikra atsiliepimo palikimo nuoroda.
- Welcome laiškai: 15 % nuolaida, kodas `PRO15`.
- Winback laiškai: 10 % nuolaida, kodas `GRIZAU10`.
- Kuponų veikimą ir sąlygas patikrinti parduotuvėje; šis eksportas kuponų nesukuria.
- Post-purchase tekstas skirtas siųsti po prekės gavimo.
- Tai maketų ir jų assetų archyvas, ne aktyvuotos Omnisend automatizacijos. Prieš siuntimą atlikti bandomąjį siuntimą platformoje.

Atšauktas personalizuoto ExtraPet laiško pavyzdys ir senesnės tarpinių maketų versijos neįtraukti.
