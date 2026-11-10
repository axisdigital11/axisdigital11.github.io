# Screenshots for the marketing site

Real captures of the app from the demo account (invented Israeli data), named exactly
`<name>-<theme>-<device>.png`. The site decides at **build time** whether each file
exists (`virtual:site-assets` in `vite.config.ts`): a missing file renders a neutral
placeholder frame of the same size, never a broken image. Drop the file here and
rebuild.

Sizes: desktop `1280×800` (CSS px, 1x or 2x), phone `390×844` @2x (`780×1688`). PNG,
no browser chrome, no cursor.

| File | Where on the page | What to show |
| --- | --- | --- |
| `whatsapp-dark-phone.png` | בתשע בערב (dark) | A WhatsApp conversation: auto-reply in 6s, the agent qualifying, the meeting set |
| `ai-settings-dark-desktop.png` | בתשע בערב (dark) | The AI assistant settings card |
| `conversations-dark-desktop.png` | בתשע בערב → automations (dark) | The shared inbox with a follow-up stopped because the lead answered |
| `questionnaire-light-desktop.png` | המערכת מרכיבה את עצמה | The onboarding questionnaire |
| `automations-light-desktop.png` | המערכת מרכיבה את עצמה | The automations list the questionnaire built |
| `board-light-desktop.png` | יום בחיים של ליד · 21:47:03 | The lead board: every lead, its stage, who handles it |
| `dashboard-light-desktop.png` | יום בחיים של ליד · attribution, and the video poster | The dashboard: which campaign brought deals, not just leads |
| `calendar-light-phone.png` | יום בחיים של ליד · 10:00 | The calendar on a phone, the meeting set in WhatsApp |
| `quote-signed-dark-phone.png` | יום בחיים של ליד · 12:30 | A signed quote on a phone, the lead moved to "נסגר לקוח" |

## Explainer video

`public/video/axis-explainer.mp4` (+ optional `axis-explainer.webm` and the Hebrew
captions `axis-explainer.he.vtt`). Same rule: detected at build time; until the mp4
exists the video section shows the poster (`dashboard-light-desktop.png`) with a
"הסרטון בדרך" badge.
