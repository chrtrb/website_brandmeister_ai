# website_brandmeister_ai

Statische Seite (Cloudflare Pages, Auto-Deploy bei Push auf `main`).

- `_redirects`: `/pilot` → Brevo-Formular „Pilotpartner werden“ (302). Der QR-Code am Stand zeigt auf `brandmeister.ai/pilot`; zum Tauschen des Formulars nur die Ziel-URL hier ändern.
- `pilot-bestaetigen.html`, `pilot-danke.html`: Bestätigungsseiten des Brevo-Double-Opt-in (noindex).
- Strategie und Entscheide: `ragsource/Strategie/marketing-funnel-2026.md` §8.
