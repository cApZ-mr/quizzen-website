# quizzen-website

Website der iOS-App **Quizzen** – reines HTML/CSS, gehostet auf Vercel.

| Seite | Datei |
|---|---|
| Startseite | `index.html` |
| Datenschutz | `datenschutz.html` → `/datenschutz` |
| Nutzungsbedingungen | `nutzungsbedingungen.html` → `/nutzungsbedingungen` |
| Support | `support.html` → `/support` |
| Impressum | `impressum.html` → `/impressum` |

Lokal ansehen:

```bash
python3 -m http.server 8000
```

Dann http://localhost:8000 öffnen (ohne `.html` funktionieren die Links erst auf Vercel – lokal `/datenschutz.html` aufrufen).

Jeder Push auf `main` wird von Vercel automatisch veröffentlicht.
